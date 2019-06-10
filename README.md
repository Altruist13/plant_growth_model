# plant_growth_model
HYDROPONICS  GROWTH MODEL

Image Data Set:

The  low-cost microcomputer (RasPi; Raspberry Pi 3) and a webcam to collect data set for the machine learning model.
Two RasPi units were used to allow the capturing of an image of the hydroponics panel .
These data were transferred automatically to azure blob storage . The images are taken from various views top view, front view , 
back view and side view .The images taken are  incorporated with variety features to build a rich data set including greyscale , invert , 
rotate and resolution changing capabilities . The resolution of each image was 1900 × 1080  pixels. Since the day of plantation for every  
mins the growth of plant is monitored by collecting images . And thus creating a rich image data set .

Nomenclature:

To predict the growth of the individual plant we name the hydroponics as 1_1, 1_2…..based on their row and column number .
 Initially it consist of 4*10 matrix with 4 rows and 10 columns . 
