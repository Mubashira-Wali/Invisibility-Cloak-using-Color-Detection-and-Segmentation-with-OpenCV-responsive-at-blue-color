# Invisibility Cloak using Color Detection and Segmentation with OpenCV responsive at blue color

If you are a Harry Potter fan like me, you would know what an Invisibility Cloak is. Yes! It’s the cloak which Harry Potter uses to become invisible. Of course, we all know that an invisibility cloak is not real — it’s all graphics trickery.

In this repository, you will find the code to create our own ‘Invisibility Cloak’ using simple computer vision techniques in OpenCV and numpy.

# How does it work ?
The algorithm is very similar in principle to green screening. But unlike green screening where we remove the background, in this application, we remove the foreground!

## Algorithm
1. Capture and store the background frame [ This will be done for some seconds ]
2. Detect the blue colored cloth using color detection and segmentation algorithm.
3. Segment out the blue colored cloth by generating a mask. [ used in code ]
4. Generate the final augmented output to create a magical effect.

## Requirement
1.Python(3)
2.Numpy
3.OpenCV

## How to run the code
1. Run the ipynb file in your jupyter notebook. (make sure to set the background first the backgroung must be still nobody is in front of the webcam.)
2. A window will pop up showing the video.
3. Now take a blue piece of cloth is front of the web cam and see the magic.
