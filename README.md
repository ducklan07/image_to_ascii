# Image to ASCII Converter

This project is a Python script that converts an image to ASCII art. The script takes an image file path as a command-line argument, processes the image, and prints the resulting ASCII art to the console.

## Features

- Resizes the image while preserving the aspect ratio.
- Converts the image to grayscale.
- Maps grayscale pixels to ASCII characters to create the ASCII art.

## Requirements

- Python 3.x
- Pillow library

## Installation

1. Clone the repository or download the script.
2. Install the required dependencies using pip:

    ```sh
    pip install pillow
    ```

## Usage

Run the script from the command line with the path to the image file as an argument:

```sh
python main.py <image_path>
