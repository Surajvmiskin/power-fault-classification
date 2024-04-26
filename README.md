# Power System Fault Classification

Welcome to the Power System Fault Classification project! This repository contains code and resources for classifying electrical faults in power transmission lines using neural networks.
     
## Introduction
   
The transmission line is a critical component of the power system, responsible for transmitting electric power from the source area to the distribution network. This project focuses on the classification of electrical faults in transmission lines using machine learning techniques. 
 
## Data and Overview 
  
This project involves binary and multiclass classification of electrical faults. The dataset includes information about different types of faults and their characteristics. The goal is to predict whether there is a fault and, if so, determine the type of fault.

### Binary Classification

The first part of the project focuses on binary classification to predict the presence of a fault. The output class is either 'Fault' or 'No Fault'.

### Multiclass Classification

The second part of the project involves multiclass classification to predict the specific type of fault. There are six types of faults: No Fault, LG Fault, LLG Fault, LL Fault, LLL Fault, and LLLG Fault.

## Getting Started

To run this project on your local machine, follow these steps:

1. Clone this repository:
   ```git clone https://github.com/your-username/power-system-fault-classification.git```
   

3. Install the required dependencies:
```pip install numpy pandas matplotlib seaborn tensorflow scikit-learn```



3. Download the dataset files: `classData1.csv`.

4. Run the main scripts for binary and multiclass classification:
- For binary classification: `python binary_classification.py`
- For multiclass classification: `python multiclass_classification.py`

## Models and Results

### Binary Classification Neural Network Model

The binary classification model uses a neural network architecture with multiple layers to predict the presence of a fault.

### Multiclass Classification Neural Network Model

The multiclass classification model uses a neural network with multiple hidden layers to classify the type of fault.

## Evaluation and Metrics

The models are evaluated using various metrics such as accuracy, precision, recall, F1-score, and confusion matrix.

## Contributing

Contributions are welcome! If you find any issues or want to enhance the project, feel free to submit a pull request.


## Acknowledgments

We would like to express our gratitude to the developers of scikit-learn and TensorFlow for providing the tools necessary to complete this project.

## Contact

For any inquiries or questions, please contact surajvmiskin@gmail.com
