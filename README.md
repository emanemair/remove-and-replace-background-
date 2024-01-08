# Remove-Replace-Background

## Introduction
This script utilizes the `rembg` library to remove the background of an image and replace it with a new background. It fetches an image from a specified URL, removes its background, and then overlays the subject onto a different background image.

## Requirements
- Python 3.x
- `pillow`
- `easygui`
- `rembg`

## Installation
Install the required libraries by running the following commands:
```bash
pip install -U pillow
pip install easygui
pip install rembg

``` 
## Usage
- Run the script in a Python environment.
- The code fetches an image from a specified URL and saves it in the 'original' directory.
- It uses rembg to remove the background of the fetched image and saves the masked image in the 'masked' directory.
- A background image is fetched and resized to match the dimensions of the original image.
- The masked image is overlaid onto the new background, and the resulting image is saved in the 'masked' directory as 'background.jpg'.
