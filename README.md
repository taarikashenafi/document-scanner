## Document Scanner

A simple document scanner using OpenCV and Python.

## Description
This project uses OpenCV to scan documents from images. It applies a perspective transform to the image to correct for skew and distortion, and then saves the transformed image as a new file.

## Installation
To install the dependencies, run the following command:

```
pip install -r requirements.txt
```

## Usage
To use the document scanner, simply run the following command:

```
python scan.py -i input_image.jpg
```

Replace input_image.jpg with the path to the image you want to scan.

## Output
The transformed image will be saved as a new file named output_image.jpg in the same directory as the input image.

## Notes
This project is based on the tutorial by PyImageSearch. The four_point_transform function is implemented using OpenCV.
