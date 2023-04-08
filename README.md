# MMAI894 Deep Learning Course Project - Tomato Leaf Disease Classification
This repo contains code for MMAI894 Deep Learning course project from Team Broadview.
- 1) Exploratory Data Analysis
- 2) Develop Custom CNN - Pre Hyperparameter Tuning
- 3) Transfer Learning Using Pertained Models
- 4) Hyperparameter Tuning Using Hyperband and Random Search algorithms


Tomato plants are susceptible to diseases, including bacterial speck/blight, viruses, leaf spots, and other pathogens, making them prone to significant losses. Early detection of tomato leaf disease is one of the ways to manage this issue, but it is challenging for farmers to detect them early on. 

The Tomato Disease dataset on Kaggle, published in 2022, is the largest dataset focused on tomato leaf disease, with 11 classes and 10 diseases. It has over 20,000 images of tomato leaves with 10 diseases and 1 healthy class, collected both in the lab and in the wild. 

To solve this problem, the team tried nine different deep learning models to determine which one gave the best results in detecting tomato leaf disease. The Xception model gave the best accuracy, at 98.32%, followed by Densenet 201, provided the best precision across some of the disease classes. Additionally, the team implemented the six-step hyperparameter tuning process to improve model performance. After hyper parameter tuning, the team was able to achieve significant performance improvement for custom CNN and MobileNet. 
