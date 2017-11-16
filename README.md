# Web_Camera_Motion_Detection
• Using Open CV (computer Vision) Python build an application that detects moving objects from computer Camera.
• After quitting the application, it creates interactive graph which shows time and frame when object entered and existed the video frame.
• In order to detect motion, we calculate the difference between the first frame and other frames. The first frame is calculated when the video starts recording and that is the base frame (we will be comparing other frames of the video with this base frame). 
• We convert all the frames to gray image and blur it using Gaussian curve in order to achieve high accuracy.
• After motion is detected in the frame, a rectangle is created on the object. By pressing "q" the camera quits and destroys all the windows.
• And times of entry and exist are added to the Excel file (.csv), if the file does not exist it will be created.
