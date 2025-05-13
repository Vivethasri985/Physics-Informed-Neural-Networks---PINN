
# Physics-Informed Neural Networks (PINNs)

This repository demonstrates a Physics-Informed Neural Network (PINN) for solving 2D heat transfer equations using two different datasets (Void and Square). It leverages TensorFlow to model and solve the heat transfer problem efficiently.

## Project Overview
- **Project Name:** Physics-Informed Neural Networks (PINNs) for Heat Transfer
- **Technology Stack:** Python, TensorFlow, NumPy, Matplotlib
- **Problem Solved:** Solves heat transfer equations using a neural network model constrained by physics laws.
- **Datasets:**
  - **Void Dataset (void.xlsx):** Represents heat transfer data for a region with a void.
  - **Square Dataset (square.xlsx):** Represents heat transfer data for a square-shaped region.

## Project Structure
```
Physics-Informed-Neural-Networks-PINNs/
├── dataset/                # Datasets used
│   ├── void.xlsx        # Void dataset
│   └── square.xlsx      # Square dataset
├── codes/                 # Source code (Python scripts)
│   ├── Copy_of_Final_void(1).ipynb        # Notebook for void dataset
│   ├── Final_square(2).ipynb      # Notebook for square dataset
├── README.md            # Project description
```

## How to Run
- Open the Colab Notebooks (`Copy_of_Final_void(1).ipynb` and `Final_square(2).ipynb`) to see the results for each dataset.

## Results
- The model predicts the temperature distribution accurately across the domain for each dataset.
- Sample results are shown in the notebooks.
