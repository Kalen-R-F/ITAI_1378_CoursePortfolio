# Problem
The problem chosen for our project was analyzing what kinds of birds are in an area at different times of the year, as birds are an important part of the ecosystem and it is important to know when something about their behaviour or timings is off.

# Solution
To solve this issue we used a camera to watch a bird feeder to see different types of birds that show up at the feeder throughout the day, we used a CV model to provide an output with boudning boxes and metadata export for research data collection.

# Results
The results show that everything is working smoothly within the model with the given inputs after training, with the YOLO model being able to correctly identify 92% of birds that do come into frame, the only small issue is that it could use some fine tuning and most of the slack is from hardware limits.

# Key Findings
I learned a lot about how to train CV models to be able to identify birds on a live camera, then be able to identify what type of bird it is correctly, as knowing the type of bird is very important for what we want to use the data for.

# Technologies Used
We are using YOLO11 Large for our model because it provided the most consistent detection on the birds after comparing 6 different models, even outperforming the modern version of itself, YOLO26. We are using a camera for direct video input into the detection model, the cameras native framerate is 25 fps allowing for plenty of data for a bird coming into the picture to be accurately identified.

# How to Run

Step by Step process we took when developing the program

https://drive.google.com/drive/folders/1Az2sX6fY5jJ2O6aMfUaFZ2xWbRjn2rWM
