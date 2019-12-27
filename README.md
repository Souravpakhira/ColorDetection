# ColorDetection
In this color detection Python project, we can automatically get the name of the color by clicking on them. So for this, we will have a data file that contains the color name and its values. Then we will calculate the distance from each color and find the shortest one.

# The Dataset
Colors are made up of 3 primary colors; red, green, and blue. In computers, we define each color value within a range of 0 to 255. So in how many ways we can define a color? The answer is 256*256*256 = 16,581,375. There are approximately 16.5 million different ways to represent a color. In our dataset, we need to map each color’s values with their corresponding names. But don’t worry, we don’t need to map all the values. We will be using a dataset that contains RGB values with their corresponding names. The CSV file for our dataset has been taken from this link:

## Colors Dataset
The colors.csv file includes 865 color names along with their RGB and hex values.

# Prerequisites
OpenCV, Pandas, and numpy are the Python packages that are necessary for this project in Python. To install them, simply run this pip command in your terminal:

> pip install opencv-python numpy pandas

# The project folder contains 3 files:
- Color_detection.py – main source code of our project.
- Colorpic.jpg – sample image for experimenting.
- Colors.csv – a file that contains our dataset.

# Run Python File
> python color_detection.py -i 'add your image path here'

![](color-detection-python-project.gif)
