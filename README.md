# Cloud based Image Recognition
Problem Statement:Develop a cloud-based image recognition system to classify uploaded images using a Convolutional Neural Network (CNN) and display performance metrics.<br>

Workflow:
 
User uploads an image via a web app.<br>
The image is sent to the AWS API Gateway.<br>
AWS Lambda processes the image using a TensorFlow CNN model.<br>
Classification results are returned to the user and logged in DynamoDB.<br>
PowerBI visualizes logs and system performance.<br>

Technolgies used:
<br>
Backend: AWS Lambda, API Gateway, S3, DynamoDB.<br>
Frontend: Angular.<br>
ML Model: TensorFlow for training the CNN model.<br>
Visualization: PowerBI.
<br>
