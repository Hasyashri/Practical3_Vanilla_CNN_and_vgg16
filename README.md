# Dogs vs Cats Classification: Vanilla CNN and Fine-Tune VGG16

## Project Overview
This project focuses on classifying images of dogs and cats using two different deep learning approaches:  
1. A custom-built Vanilla Convolutional Neural Network (CNN) trained from scratch.  
2. Fine-tuning a pre-trained VGG16 model, leveraging transfer learning to improve accuracy.

The goal is to compare these models' performances and analyze their strengths and weaknesses.

---

## Dataset
- **Source:** Kaggle Dogs vs Cats dataset  
- **Subset Used:** 5,000 images (2,500 dogs and 2,500 cats)  
- **Folder Structure:**  
  - `data/kaggle_dogs_vs_cats_small` contains the images used for training and testing.

---

## Project Structure
Practical3_Vanilla_CNN_and_vgg16/

Dataset folder: - data/kaggle_dogs_vs_cats_small/  
Main notebook : - Lab3_VanillaCNN_VGG_dogsandcats.ipynb 
Best model weights for Vanilla CNN :- vanilla_best.h5  
Best model weights for VGG16 :- vgg16_best.h5 #
Python dependencies :- requirements.txt 
.gitignore
Project documentation :- README.md 


---

## How to Run
1. Create a Python virtual environment and install dependencies:  
   ```bash
   python -m venv venv
   source venv/bin/activate       # On Windows: venv\Scripts\activate
   pip install -r requirements.txt

----
2. Open and run the notebook Lab3_VanillaCNN_VGG_dogsandcats.ipynb in Jupyter or VSCode.

3. The notebook contains all steps: data loading, exploration, model training, evaluation, and analysis.

## Key Results

- The pre-trained VGG16 model significantly outperformed the Vanilla CNN in accuracy, precision, and recall.
- VGG16’s transfer learning allowed it to learn faster and generalize better with limited training data.
- Analysis of misclassified images highlighted challenges such as blurry photos, strange angles, and visually similar animals.
- Detailed metrics including confusion matrix, precision-recall curves, and F1 scores are provided in the notebook.

## Insights and Conclusions

- Transfer learning with pre-trained models is a powerful approach for image classification tasks with limited data.
- Custom models trained from scratch require more data and tuning to reach similar performance levels.
- Misclassifications often stem from ambiguous or poor-quality images, emphasizing the importance of good data.
- This project provides a foundation for real-world applications like pet recognition, security cameras, and mobile apps.

---

**Hasyashri Bhatt**
