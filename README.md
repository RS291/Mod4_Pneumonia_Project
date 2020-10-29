# Predicting Pneumonia with CNNs
## Module 4 Machine Learning Project

### Business Problem: <br/>
For this project, I assumed the role of a Data Scientist working with a medical research firm. The goal is to train a machine learning model to classify whether a patient has pneumonia or not, given images of their chest x-rays. I opted to use convolutional neural networks to attack this problem.  
Pneumonia is an inflammatory infection that primarily affects small air sacks in the lungs known as alveoli. In more severe cases, these sacks may fill with fluid. Symptoms include coughing, chest pain, fever, and labored breathing. Each year, ~450 million people are infected globally and about 4 million of those die.  <br>

While generally the overall goal is to build the best model possible, I will be forgoing the use of a TPU or other distributed computing system and will focus more on demonstrating my understanding of neural networks. I will be working with a downsampled dataset in this case, and look to use AWS or a Google TPU in the future to continue where this project left off.

The final CNN model had an accuracy of 92.3 and recall of 28.1. All analysis and modeling is present in the Predicting_Pneumonia.ipynb file.  

### Methods: 
I used a modified version of the OSEMN data science process(Obtain, Scrub, Explore, Model, iNterpret). There were some procedural tweaks I made due to the use of deep learning rather than more traditional machine learning techniques.  

I used Python 3 and the following libraries to process and model the data: Tensorflow, Keras, sci-kit learn, NumPy, matplotlib, pandas, Pillow, and seaborn.  

### Repository Structure:
* Predicting_Pneumonia.ipynb - Detailed and documented analysis and modeling of the data in Jupyter Notebook form.
* Predicting_Pneumonia_Presentation.pdf - pdf export of the presentation, with notes. 
* README.md - Project summary and guide to the repository.

