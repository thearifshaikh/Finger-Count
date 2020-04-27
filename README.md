# COUNT FINGERS
This is a Computer Vision Project where it detects the hand first,segment the hand ,and then it counts the number of fingers being held up!


## TECHNOLOGY STACK
- Image Processing and Deep Learning
- Libaries- OpenCV,Numpy,


## INSTRUCTIONS
- Before run the program ensure that you have a good lighting on hand
- Run the code and wait for the Region of Interest(ROI) to get selected (here top right corner) .A red rectangle box will be visible as   shown below.
- Gently place your hand inside the box.

![Reference 1](https://user-images.githubusercontent.com/56214309/80414842-46867680-88ef-11ea-84dc-929e0adc0c85.png)


## WORKING PROCEDURE
-	Grab a Region of Interest (ROI) from the frame and calculate the average running value for some amount of frames.
-	Then once a hand enters, changes are detected and thresholding is applied.
- Convex Hull is used to draw a polygon around the hand.
- The centre of the hand is calculated against the angle of outer points to infer finger count.
- A circle is drawn from the centre of the hand.
- Any points of the convex polygon lying outside the circle is counted as a finger.

![hand_convex](https://user-images.githubusercontent.com/56214309/80427579-b43d9d00-8905-11ea-8d58-a734412c2ff7.png)

## RESULTS











