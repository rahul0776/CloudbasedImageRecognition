# CloudbasedImageRecognition
Problem Statement:Develop a cloud-based image recognition system to classify uploaded images using a Convolutional Neural Network (CNN) and display performance metrics.

Workflow:
 
User uploads an image via a web app.
The image is sent to the AWS API Gateway.
AWS Lambda processes the image using a TensorFlow CNN model.
Classification results are returned to the user and logged in DynamoDB.
PowerBI visualizes logs and system performance.

Technolgies used:

Backend: AWS Lambda, API Gateway, S3, DynamoDB.
Frontend: Angular.
ML Model: TensorFlow for training the CNN model.
Visualization: PowerBI.
