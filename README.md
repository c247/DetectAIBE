# Medical AI Pneumonia Detector

### Stack
- AWS (SageMaker, API Gateway, Lambda, S3, Cloudwatch) - ML API endpoint
- MongoDB - User login data
- Next.js, Node.js - Server/Client - Interacts with AWS API
### AWS SageMaker Model Creation, Data Analysis and HyperParameter Tuning
- See MedicalAI.ipynb for Model configuration
- I utilized SageMakers image classification model and used transfer learning for my model.
- Used matplotlib, numpy, seaborn and scikit-learn to visualize data, generate confussion matrix etc.

### Digital Ocean Demo
- http://165.22.236.78/
- Note: image classification endpoint stopped

![alt text](./githubdemo.JPG)
