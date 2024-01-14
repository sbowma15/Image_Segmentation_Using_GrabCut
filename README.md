
Image Segmentation using GrabCut

This Python script, grabCut_image_segmentation.py, demonstrates the application of the GrabCut algorithm for image segmentation. The GrabCut algorithm separates the foreground and background of an image, and in this script, we focus on a specific rectangular region for initialization.

Prerequisites

Before running the script, ensure you have the necessary libraries installed. You can install them using the following:

bash
Copy code
pip install numpy opencv-python matplotlib
Usage
Open the script in your Python environment.

Adjust the file path in the cv.imread function to the location of the image you want to process.

python
Copy code
img = cv.imread('/path/to/your/image.jpg')
Set the parameters in the script as needed:

rect: Define the rectangular window by specifying (x-coordinate, y-coordinate, height, width). This window serves as the initial approximation for GrabCut.
bgdModel and fgdModel: Arrays for background and foreground modeling. No need to modify these unless you have specific requirements.
Run the script.

Output

The script will display the segmented image, and you can visualize the result with a color spectrum bar. The output shows the foreground of the image, separated from the background based on the specified rectangular window.

Feel free to experiment with different images and adjust the parameters to achieve the desired segmentation results.

