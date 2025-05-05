# Face Mask Detection Project

This project uses a Convolutional Neural Network (CNN) to detect face masks in images. The model is built using TensorFlow and Keras.

## Setup

1. Create a virtual environment using `uv`:
   ```bash
   uv venv .venv
   ```

2. Activate the virtual environment:
   - On Windows:
     ```bash
     .venv\Scripts\activate
     ```
   - On Unix or MacOS:
     ```bash
     source .venv/bin/activate
     ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Jupyter notebook:
   ```bash
   jupyter notebook MFRS.ipynb
   ```

## Data

The dataset should be organized in the following structure:
- `Train/`: Contains training images.
- `Validation/`: Contains validation images.

## Model

The model architecture is defined in the `MFRS.ipynb` notebook. It includes convolutional layers, max pooling layers, and dense layers for classification. 