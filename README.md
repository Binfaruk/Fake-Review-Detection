

# Fake Review Detection  

This project is focused on identifying fake reviews using various machine learning algorithms. By analyzing textual features of reviews, the system can distinguish between genuine and fake reviews with high accuracy.  

## Table of Contents  
1. [Overview](#overview)  
2. [Dataset](#dataset)  
3. [Algorithms Used](#algorithms-used)  
4. [Installation](#installation)  
5. [Usage](#usage)  
6. [Contributing](#contributing)  

## Overview  
Fake reviews can mislead customers and harm the reputation of businesses. This project aims to detect fake reviews using multiple machine learning classifiers. The system is designed to evaluate reviews based on their text features and classify them as real or fake.  

## Dataset  
The project uses the [Fake Reviews Dataset](https://www.kaggle.com/datasets/mexwell/fake-reviews-dataset). This dataset contains reviews labeled as fake or genuine, along with other textual information.  

## Algorithms Used  
The following machine learning algorithms are implemented and evaluated:  
1. Multinomial Naive Bayes  
2. Support Vector Machines (SVM)  
3. Random Forest Classifier  
4. Decision Tree Classifier  
5. K-Nearest Neighbors (KNN)  
6. Logistic Regression  

## Installation  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-username/fake-review-detection.git  
   cd fake-review-detection  
   ```  
2. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  

## Usage  
1. Prepare the dataset: Download the Fake Reviews Dataset and place it in the `data/` folder.  
2. Preprocess the data:  
   ```bash  
   python preprocess.py  
   ```  
3. Train models:  
   ```bash  
   python train.py  
   ```  
4. Test models and view results:  
   ```bash  
   python test.py  
   ```  

## Contributing  
Contributions are welcome! If you have suggestions or improvements, feel free to open an issue or submit a pull request.  

