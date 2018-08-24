# SageMaker/DeepLens demo Safety-helmet detection (AWS)

This repo sync's with the SageMaker folder in steve@smtahunter's SageMaker folder in US-East-1,
https://safethelmetdetection.notebook.us-east-1.sagemaker.aws/tree

Use Case:
As a Site Inspector, I want to identify any construcion crew that are not wearing safety helmets, so I can meet my health and safety responsibilties

## Steps:

[1. Download ImageNet images by Wordnet ID.ipynb](https://github.com/Steve--Hunter/DeepLens-Safety-Helmet/tree/master/1.%20Download%20ImageNet%20images%20by%20Wordnet%20ID.ipynb)

[2. Store images into binary recordIO format for MXNEt](https://github.com/Steve--Hunter/DeepLens-Safety-Helmet/tree/master/2.%20Store%20images%20into%20binary%20recordIO%20format%20for%20MXNEt.ipynb)

3. Retrain model (hotdog) with new images (of safety helmet)

4. Deploy retrained model to DeepLens

5. Build infrastructure to alert Site Inspector of construction crew not wearing a safety helmet 

