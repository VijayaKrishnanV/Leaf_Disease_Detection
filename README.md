# Plant Health Detection Project

## Project Overview

The Plant Health Detection project aims to classify leaf images into three categories: Healthy, Powdery, and Rusty. This README file provides an overview of the project structure, setup, and instructions to run the code using a Jupyter notebook.

## Project Structure

The project directory is organized as follows:

```
Plant-Health-Detection/
├── Train/
│   ├── Healthy/
│   ├── Powdery/
│   └── Rust/
├── Test/
│   ├── Healthy/
│   ├── Powdery/
│   └── Rust/
├── Validation/
│   ├── Healthy/
│   ├── Powdery/
│   └── Rust/
├── model_training.ipynb
└── README.md
```

- `Train/`: Contains training images for each category.
- `Test/`: Contains testing images for each category.
- `Validation/`: Contains validation images for each category.
- `model_training.ipynb`: Jupyter notebook for training the model and making predictions.
- `README.md`: This file.


## Running the Code

### 1. Open Jupyter Notebook

To start the Jupyter notebook, run the following command in your terminal:

```bash
jupyter notebook
```

This will open the Jupyter notebook interface in your web browser. Navigate to the `model_training.ipynb` file and open it.

### 2. Run the Notebook

Follow the instructions in the notebook to:
1. Count the number of images in each category.
2. Display sample images from each category.
3. Prepare the data generators for training and validation.
4. Define and compile the CNN model.
5. Train the model and save the training history.
6. Plot the accuracy and loss curves.
7. Make predictions on new images.

## Code Explanation

### Model Training and Prediction (model_training.ipynb)

The notebook performs the following steps:
1. **Counting Files**: Counts the number of images in each category.
2. **Displaying Sample Images**: Displays sample images from each category.
3. **Data Preparation**: Prepares the data generators for training and validation.
4. **Model Architecture**: Defines a Convolutional Neural Network (CNN) with layers for feature extraction and classification.
5. **Model Compilation**: Compiles the model with Adam optimizer and categorical cross-entropy loss.
6. **Model Training**: Trains the model using the training and validation data.
7. **Performance Evaluation**: Plots the accuracy and loss curves to visualize the training process.
8. **Prediction**: Loads and preprocesses a new image, and outputs the predicted class label.

## Results

The model's performance is evaluated on the validation set. The accuracy and loss curves are plotted to visualize the training process.

