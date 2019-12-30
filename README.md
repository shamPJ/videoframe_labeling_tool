# videoframe_labeling_tool
Short ugly script for frame-to-frame analyses of animal behavior. Uses keyboard input to label video frames with a specific behavior and exports final data (frame, time and behavior) as .csv

Recorded video of mouse behavioral "open field" test loaded with OpenCV library. Navigation between the frames could be done with a trackbar or with a right-left arrows. 
Analyzed behaviors and corresponding keyboard input are specified and displayed also.

Whenever frame is viewed it could be labeled with a specific behavior, otherwise it will be labeled as "none" (meaning: frame was seen, but not marked). Frames which haven't been viewed are not marked (e.g. when you fo through frames with a trackbar and skip some of the frames).  

![alt text](https://github.com/shamPJ/videoframe_labeling_tool/blob/master/screenshots/video.png)

Keyborad input is detected and respective behavior stored in a list, along with a frame number and time, which are stored in two other lists.
After quitting the windows (by pressing esc) dataframe from these lists is created and exported as .csv

![alt text](https://github.com/shamPJ/videoframe_labeling_tool/blob/master/screenshots/outputFile.png)

