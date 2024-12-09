# Custom Text Classifier Using Markov Models

This project implements a custom text classifier that distinguishes between the writing styles of Edgar Allan Poe and Robert Frost using Markov Models. The classifier is built from scratch without relying on machine learning libraries, demonstrating fundamental probability theory and algorithmic implementation.

## Description

The project develops a custom Markov-based text classification system that analyzes the unique patterns in the writing styles of two distinct poets. Instead of using pre-built machine learning libraries, the system implements:

-Custom transition matrices for probabilistic modeling
-Add-one smoothing for probability estimation
-Data balancing techniques for improved performance
-Custom prediction functions based on Markov chains

The classifier achieved 82% accuracy on the test set, showcasing the effectiveness of fundamental probabilistic approaches to text classification.

## Getting Started

### Dependencies

Before installing and running this project, please ensure you meet the following requirements:

### Operating System:

-Windows: Windows 10 or later
-macOS: Catalina or later
-Linux: Any modern distribution (Ubuntu 20.04 LTS or later)

### Python Environment:

-Python 3.8+
-Jupyter Notebook

#### Required libraries:

-numpy
-pandas
-scikit-learn (for data splitting and evaluation metrics)
-nltk (for tokenization)
-matplotlib (for visualization)


## Installation

Clone the repository:

bashCopygit clone [your-repository-url]
cd [repository-name]

Install required packages:

bashCopypip install numpy pandas scikit-learn nltk matplotlib

Download the required NLTK data:

pythonCopyimport nltk
nltk.download('punkt')
Usage

Open the Jupyter notebook:

bashCopyjupyter notebook Text_Classifier.ipynb

The notebook contains detailed sections for:

Data preprocessing
Markov model implementation
Transition matrix creation
Model evaluation
Performance optimization



## Technical Implementation

The classifier uses:

Markov chain transition matrices to capture writing style patterns
Log probabilities for numerical stability
Add-one smoothing to handle unseen transitions
Data balancing to improve model performance

Key features:

Custom implementation of probabilistic text classification
No reliance on pre-built ML classification libraries
Efficient handling of sparse transition matrices
Balanced dataset creation for improved accuracy

## Results
The model achieves:

82% accuracy on the test set
Effective style differentiation between two distinct authors
Robust performance without complex deep-learning approaches

## Authors

Yuri Lazzeretti

ylazz001@gmail.com

www.linkedin.com/in/yuri-lazzeretti-b63a22220
