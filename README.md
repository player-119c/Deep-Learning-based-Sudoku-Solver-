# Sudoku Solver and Digit Recognition

This project is a Sudoku solver and digit recognition system using Convolutional Neural Networks (CNNs). The program processes a Sudoku puzzle image, identifies and recognizes the digits, and then solves the puzzle using a backtracking algorithm. The solution is overlaid on the original image, and the final result is saved as an image file.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Setup and Installation](#setup-and-installation)
3. [Data Preprocessing](#data-preprocessing)
4. [Model Creation and Training](#model-creation-and-training)
5. [Predicting Cells and Solving Sudoku](#predicting-cells-and-solving-sudoku)
6. [Results and Visualization](#results-and-visualization)
7. [Usage](#usage)
8. [License](#license)

## Project Overview

This project uses a Convolutional Neural Network (CNN) to recognize handwritten digits within a Sudoku puzzle. The system consists of several steps:

1. **Data Loading and Preprocessing**: Loads images of digits, preprocesses them for training, and splits the dataset into training, validation, and test sets.

2. **Model Training**: A CNN is trained on the preprocessed digit images to recognize handwritten numbers. The trained model is saved for later use.

3. **Predicting Cells**: The model predicts the digits from the cropped cells of the Sudoku puzzle image.

4. **Solving Sudoku**: A backtracking algorithm solves the Sudoku puzzle using the predicted digits.

5. **Results Visualization**: The solved Sudoku puzzle is overlaid on the original image and saved as a new image file.

## Setup and Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/sudoku-solver.git
   cd sudoku-solver
