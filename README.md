# SageMaker/DeepLens demo Safety-helmet detection (AWS)

This repo sync's with the SageMaker folder in steve@smtahunter's SageMaker folder in US-East-1,
https://safethelmetdetection.notebook.us-east-1.sagemaker.aws/tree

Use Case:
As a Site Inspector, I want to identify any construcion crew that are not wearing safety helmets, so I can meet my health and safety responsibilties

Steps:
1. Grab images from ImageNet
2. Compose them into .rec format for MXNEt
3. Retrain model (hotdog) with new images (of safety helmet)
4. Deploy retrained model to DeepLens
5. Build infrastructure to alert Site Inspector of construction crew not wearing a safety helmet 
