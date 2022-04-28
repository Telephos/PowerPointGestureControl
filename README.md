# PowerPointGestureControl
Control a powerpoint through right and left gesture, holding your arms to the left or right. 

Requires open-cv, keras, tensorflow, pyautogui. 

Run the code chunks installing the necessary dependancies, and run the chunk importing all the needed libraries. Place the trained model "imageClassifier10.h5" within the directory where you have the UserStudyPlatform.ipynb notebook. Execute the 2nd to last chunk and a frame should be visible indicating the current prediction and counters for left and right. This is still a very rough prototype and extremely sensitive to background conditions and lighting. 

Another notebook is included here to create a datapipeline. Don't bother with it, unless you want to creat your own dataset and trained model. 
