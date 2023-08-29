# Medical AI Pneumonia Detector

### Stack
- AWS (SageMaker, API Gateway, Lambda, S3, Cloudwatch) - ML API endpoint
- MongoDB - User login data
- Next.js, Node.js - Server/Client - Interacts with AWS API
### AWS SageMaker Model Creation, Data Analysis and HyperParameter Tuning
- See MedicalAI.ipynb for Model configuration
- Training Data: Kaggle chest-xray pneumonia dataset https://www.kaggle.com/datasets/lasaljaywardena/pneumonia-chest-x-ray-dataset
- I utilized SageMakers image classification model and used transfer learning for my model.
- Used matplotlib, numpy, seaborn and scikit-learn to visualize data, generate confussion matrix etc.
- 15 epochs and best model got validation accuracy of 87.6%

### Digital Ocean Demo
- http://165.22.236.78/
- Note: image classification endpoint stopped

![alt text](./githubdemo.JPG)
