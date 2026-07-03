# \# Color Detection System using OpenCV

## Overview

This project detects and extracts colors, their RGB values, and the color name of a pixel in an image. By utilizing a dataset of 865 colors, the program identifies the closest color match based on RGB values. The project is useful for various image editing and drawing applications where precise color matching is required.

## Features

* Detects and identifies colors from an image.
* Matches the pixel's RGB value with the closest color from a pre-defined dataset.
* Displays the name and RGB value of the detected color.
* Verifies if the selected color is correct.

## Data Collection

The dataset contains 865 colors stored in a CSV file, with each entry consisting of:

* Color name
* Hexadecimal color value
* RGB values

## Pattern Recognition

The program reads the RGB values from the dataset and compares them with the input color values. It then finds the closest match by determining the smallest difference between the RGB values.

## Color Detection

There are over 16 million possible colors, making it difficult to find an exact match. This project picks the closest match from the 865 color dataset and provides the user with the RGB values and the color name.

## Color Verification

Once a color is selected by the user, the program verifies whether it matches the expected color, providing feedback on accuracy.

## Output Format

When a user clicks on a specific color in the given image (JPG file), the program displays the name and RGB values of the color in string format.

## Screenshot

!\[color-ss](https://chatgpt.com/backend-api/estuary/content?id=file_00000000bef071f8ac9a34fa28f70cb2&ts=495300&p=fs&cid=1&sig=3c522ec61cb511433c8945ee9bf03ece547fa8901c3d870e042ac0e714e19a14&v=0)



## Requirements

* Python 3.x
* OpenCV
* Pandas

## Installation

To get started with this project, follow these steps:

1. Clone the repository:

```bash
   git clone https://github.com/your-username/color-detection-python-opencv.git

