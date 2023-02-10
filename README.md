# **Blur Removal with OpenCV**

This repository contains a Python script that uses OpenCV to remove blurs from an image. The script applies a series of filters to the input image, including a Gaussian blur filter, to produce a clear and sharp output image. ![image](https://user-images.githubusercontent.com/66618776/218005738-8dc1f883-f1d3-4bc7-9658-b71c4fac8657.png)I have shrpen the Image and then I have use gaussian Filter, Bilateral filter, median etc. to achive the end goal 
I have used open cv2 for following purposes. 

## **Prerequisites**

- Python 3.x
- OpenCV
- Numpy
- PIL (Python Imaging Library)

## **Getting Started**

1. Clone or download the repository to your local machine.
2. Install the required packages using `pip install -r requirements.txt`.
3. Replace the `input.jpeg` file with the blurred image you want to process.
4. Run the script by executing `python blur_removal.py` in your terminal.
5. The output image will be displayed and saved with the name `output.jpeg`.

## **How it works**

The script starts by reading the input image using `cv2.imread`. The input image is then processed using a series of filters, including a filter2D with a mean kernel, a sharpen kernel, and a Gaussian blur filter. The script applies these filters in a specific order to produce the final, clear output image. The output image is then displayed and saved.

## **Conclusion**

This repository demonstrates the use of OpenCV and its filters for removing blurs from an image. The script provides a basic example that can be further extended and improved for more advanced use cases.





# Image-Blur-Removal
I have removed blur and enhanced image quality using 2D convolutional Filtering
Check out this link https://docs.opencv.org/4.x/d4/d13/tutorial_py_filtering.html🔗
First I have shrpen the Image and then I have use gaussian Filter, Bilateral filter, median etc. to achive the end goal 
I have used open cv2 for following purposes. 

