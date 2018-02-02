# Self Driving Car in GTA 5
This project is  done with the help of sentdex tutorial.
#### PreProcessing:
    1.In this project we first grab the image from the live window of GTA 5 screen.
    2.Preprocessing of the screen captured
        Resizing of the image.
        Gray Scale conversion.
        Using Gaussian Blur to smoothen the image and to remove noise 
        Select the region of interest in the area so that we can concentrate on the region of road and driving path.
    3.Sending input to the game using python.
    4.Line finding
        Using Canny Edge Detection we find the edges which are bright (White lines on the road).
        Using Hough Lines to draw the detected edges.
 
#### Training the model:
    We select the ALEXNET model and start training the car to drive on the path selected by us.
    Next we save the trainig data and use this training data to train our model.

#### Testing the model:
    We use a new path to test our model.Without traffic on the road the model performed decently well.With traffic the model has som problems.
    Using Tensorflow YOLO Object Detction API We can warn the self driving car to slow down or press the brake.
    
# Finding Car for the Player in GTA 5 game

    Using Tensorflow YOLO Object Detction API we find the car.
    Next the player will choose the car which is closest to him.
    Next go near to the car and enter the car.


