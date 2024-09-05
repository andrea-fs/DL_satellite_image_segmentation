
# Satellite Images Segmentation Project

This project involves multi-class segmentation of satellite images using deep learning techniques. The input images and the corresponding masks are 1000x1000 pixels, and the masks classify each pixel by assigning a real number.
The project aims to perform image segmentation, where the goal is to classify each pixel in a satellite image into different categories. This is done using a neural network that is trained on a set of satellite images and their corresponding segmentation masks.


## Installation

To run the project, follow these steps:

1. Clone the repository or download the project files.
2. Ensure you have Python 3.8 or later installed.
3. Install the required dependencies:

```bash
pip install numpy matplotlib tensorflow keras opencv-python Pillow patchify
```

4. Download the dataset and place it in the appropriate folder structure:
none

ign ( annotations ( training(img..), validation(img..) ), images ( training(img..), validation(img..) ) )

## Dependencies

The following Python libraries are used in the project:

- `numpy`
- `matplotlib`
- `tensorflow`
- `keras`
- `keras_cv`
- `opencv-python`
- `Pillow`
- `patchify`
- `random`
- `datetime`
- `glob`
- `os`
- `zipfile`

Make sure all the libraries are installed using the command provided above.

## Usage

1. Open the provided Jupyter notebook.
2. Run the cells step by step to load the dataset, preprocess the images, and train the model.
3. You can modify the model parameters and dataset paths according to your needs.

## Results

After training the model, the output will include the segmented images where each pixel is classified into the respective class based on the trained model.
