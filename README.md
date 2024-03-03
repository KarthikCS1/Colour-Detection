This script (color_detector.py) is designed to identify colors in an image using Python's OpenCV library (cv2) and a provided CSV file containing color data (colors.csv). It allows users to double-click on any pixel in the image, upon which the script will display the color name along with its RGB values.

Prerequisites:
Python 3.x
OpenCV (cv2)
Pandas
colorpic.jpg (a sample image)
colors.csv (a CSV file containing color data)
Usage:
Ensure that all required dependencies are installed (cv2, Pandas).
Place the sample image (colorpic.jpg) in the same directory as the script.
Prepare the colors.csv file containing color data. The file should have the following columns: "color", "color_name", "hex", "R", "G", "B".
Run the script (python color_detector.py).
Upon running the script, a window displaying the sample image will appear.
Double-click on any pixel in the image to identify its color.
Description:
get_color_name: This function calculates the closest color name from the provided CSV data based on the RGB values of the clicked pixel.
draw_function: This function handles the mouse event. When the left mouse button is double-clicked, it retrieves the RGB values of the clicked pixel.
The script continuously displays the image. When a pixel is double-clicked, it draws a rectangle displaying the selected color along with its name and RGB values.
Note:
The script assumes that the sample image (colorpic.jpg) and the CSV file (colors.csv) are present in the same directory.
Ensure the CSV file (colors.csv) follows the specified format with appropriate column names.
Press the Esc key to exit the application.
Feel free to modify the script to suit your specific requirements or integrate it into your projects as needed.# Colour-Detection
