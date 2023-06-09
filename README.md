# Classification of Breast Cancer Imagery
•	Introduction: 
		To build a breast cancer classifier on an IDC dataset that can accurately classify a histology image as benign or malignant. The IDC dataset contains 2,777,600 patches of size 50×50 taken from 162 whole mount slide images of breast cancer bodies scanned at 40x. Out of these, 1,984,000 test negative and 78,800 test positive with IDC.

•	Problem description: 
		the project aims to tackle the issue of breast cancer. By providing scans of a breast cancer body, the trained Neural Network classifier will categorize it into one of two categories that are relevant to cancerous bodies: Benign, the less harmful type of cancer, and the second type is Malignant, the dangerous and fatal type of cancer. the model’s target is to classify Malignant and Benign scan images as accurately as possible, as that is extremely crucial to be accurate in for patients with cancer.

•	Techniques: 
		Several Neural Network models have been used and designed " Transformers, KNN, CNN, Attention". An important part of the project was implementing a parallel model system where accuracies of different models that combine are evaluated to finally give us a resulting accuracy reading that improves upon the partial models used. This allowed us to improve our results way beyond than if we only had a model that does not implement this parallel multi-model technique. It improves accuracy, cuts on computation time. 

