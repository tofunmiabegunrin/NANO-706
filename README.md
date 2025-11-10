# NANO-706
# A short project on machine learning classifier and Yolov5 image detection 


 
# Machine Learning Classifier Code
This code compares the performance of three different machine learning classifiers: Random Forest, Logistic Regression, and a Multi-layer Perceptron (MLP) Neural Network on a supervised learning task.

Iris, a publicly available dataset was used for this project and downloaded and processed through the ucilmrepo as shown below. 

![iris 1](https://github.com/tofunmiabegunrin/NANO-706/blob/f84f4c36a59ff46b72a85ad1d431f8832c6dc904/iris%201.png)

The predictions made are also displayed validating the model.

![iris 4](https://github.com/tofunmiabegunrin/NANO-706/blob/2ba06d16d99904035933cc4b4d4e9525ed0553c2/iris%204.png)


# Results and Conclusion
The MLP Classifier achieved the highest accuracy, closely followed by the Random Forest model.


Logistic Regression Accuracy: 92.02%

Random Forest Accuracy: 96.75%

MLP Accuracy: 97.34%


 



# Face Detection with YOLOv5 Readme

Goal: To visually confirm that the YOLOv5s model successfully identifies and localizes objects (faces) in the input image.

Execution Steps
The code performs the following actions:
1.	Model Loading: The pre-trained YOLOv5 model is loaded. 
2.	Image Input: The input image, named tofunmi.jpg, is specified. This image is accessible within the YOLOv5 file pathway.
3.	Inference: The model runs inference (results = model(img)), processing the image to identify and localize objects (faces).
4.	Visualization: The results are displayed (results.show()), showing the original image with bounding boxes drawn around the detected objects.

![iris 2](https://github.com/tofunmiabegunrin/NANO-706/blob/21c259e27038c06d1e9bd0974d5ca6357d7790f5/iris%202.png)

Conclusion: The image detection is successfully executed and detected the loaded picture as a person with 85% accuracy. It also detects partially some other objects in the background which are a desktop screen (identified as laptop – 40%), a shape (identified as a bird – 26%) on the patterned shirt in the image.
 

 
