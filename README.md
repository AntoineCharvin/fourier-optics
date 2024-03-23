# fourier-optics
# Image Filtering Application

This Python application uses the Fourier transform for image processing, specifically applying low-pass and high-pass filters to an image. It provides a graphical user interface (GUI) for users to interactively adjust the filters and visualize the results. The application is built using `Tkinter` for the GUI, and utilizes `matplotlib` and `numpy` (through `pylab`) for processing and displaying images.

## Features

- Load an image and perform its Fourier transform.
- Apply low-pass and high-pass filters to the Fourier-transformed image.
- Adjust the filter parameters (diaphragm size for low-pass and cache size for high-pass) through interactive sliders.
- Visualize the original, low-pass filtered, and high-pass filtered images alongside their respective Fourier transforms.

## Prerequisites

Before running this application, ensure you have Python installed on your system. You will also need the following Python libraries:
- `tkinter` for the GUI.
- `matplotlib` for image processing and visualization.
- `numpy` (usually comes with `matplotlib` installation).

## Installation

1. Ensure Python is installed on your system.
2. Install the required Python libraries using pip:

```bash
pip install matplotlib
```

## Note

The application is hardcoded to load an image named oiseau.png from the same directory as the script. To process a different image, either rename the image to oiseau.png or modify the script to load the desired image file.
