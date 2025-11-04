# NANO-706
A short project on machine learning classifier and Yolov5 image detection 
Project Title: Machine Learning Classifier Code
This code compares the performance of three different machine learning classifiers: Random Forest, Logistic Regression, and a Multi-layer Perceptron (MLP) Neural Network on a supervised learning task.
Methodology

<img width="236" height="97" alt="Picture1" src="https://github.com/user-attachments/assets/1457f88d-154e-4c70-acce-7a7716e9303e" />


The data was split into training (X_train, y_train) and testing (X_test, y_test) sets. Each model was trained on the complete feature set of the training data and evaluated using the accuracy metric on the unseen test data. I varied the iterations on the logistic regression and MLP neural network with similar accuracy results obtained. 

Classifier	Configuration	Purpose
Random Forest	n_estimators=100, random_state=42	Ensemble of decision trees for robust classification.
Logistic Regression	max_iter=1200	Linear classification model used as a baseline.
MLP Classifier	max_iter=1200	A simple neural network to explore non-linear capabilities.
Results and Conclusion
The MLP Classifier achieved the highest accuracy, closely followed by the Random Forest model.
Classifier	Accuracy
MLP (Neural Network)	97.58%
Random Forest	96.75%
Logistic Regression	92.02%
Conclusion: Both the Random Forest and the MLP models demonstrated superior performance compared to the linear Logistic Regression baseline. The MLP Classifier provided the best generalization capability on the test dataset.
 


📸YOLOv5 Face Detection Readme
This script utilizes the YOLOv5s model for object detection, specifically to detect faces within an image.
Goal: To visually confirm that the YOLOv5s model successfully identifies and localizes objects (faces) in the input image.

🛠️ Execution Steps
The code performs the following actions:
1.	Model Loading: The pre-trained YOLOv5 model is loaded. 
2.	Image Input: The input image, named tofunmi.jpg, is specified. This image is accessible within the YOLOv5 file pathway.
3.	Inference: The model runs inference (results = model(img)), processing the image to identify and localize objects (faces).
4.	Visualization: The results are displayed (results.show()), showing the original image with bounding boxes drawn around the detected objects.
Conclusion: The image detection is successfully executed and detected the loaded picture as a person with 85% accuracy. It also detects partially some other objects in the background which are a desktop screen (identified as laptop – 40%), a shape (identified as a bird – 26%) on the patterned shirt in the image.
 

 
