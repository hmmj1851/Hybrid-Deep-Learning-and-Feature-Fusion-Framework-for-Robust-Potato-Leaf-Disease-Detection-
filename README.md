Plant diseases pose a significant threat to global food security, with potato crops being highly 
susceptible to fungal infections like Early Blight and Late Blight. While numerous studies 
have utilized convolutional neural networks (CNNs) to classify these diseases using image 
data, most models are trained on clean, ideal datasets and fail under real-world conditions. 
This project proposes a robust hybrid model that integrates deep CNN features with 
handcrafted descriptors such as GLCM, HOG, and PCA for improved disease classification. 
A custom 4-class dataset is constructed, including a Non-Potato class to simulate practical 
field deployment scenarios. Experimental evaluations on both 3-class (standard) and 4-class 
(realistic) datasets show that the proposed hybrid architecture, combined with SMOTE and 
fine-tuned MLP classifiers, achieves superior performance in terms of accuracy and macro 
F1-score. The model achieved up to 98.0% accuracy on the 3-class dataset and 85.8% on 
the challenging 4-class dataset. Extensive ablation studies and feature importance analysis 
further validate the robustness and generalizability of the framework. This research 
contributes a scalable, interpretable, and real-world-ready AI solution for precision 
agriculture.
