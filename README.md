# FaceAIGenerator
Based on 20,000 real human images, draws a new form of human face

GNN (Generative Adversarial Network)

Generator: Used for new image production
![image](https://github.com/jasonshin1127/FaceAIGenerator/assets/101506840/45a3185d-3670-4b7e-b2ac-ccad4fb2301e)



Discriminator: Verifying the image
![image](https://github.com/jasonshin1127/FaceAIGenerator/assets/101506840/ed0521b3-1764-4f14-b9d6-005f7aa3bbaf)


![image](https://github.com/jasonshin1127/FaceAIGenerator/assets/101506840/b97d1b1c-99f0-46c7-89a3-6a010f612f70)

Dataset: 178 * 218 sized 20,000 images of celebrities (created by the University of Hong Kong)

Code:

import os
os.environ['KAGGLE_CONFIG_DIR'] = "drive/MyDrive/Colab Notebooks/" 
!kaggle datasets download -d jessicali9530/celeba-dataset

![image](https://github.com/jasonshin1127/FaceAIGenerator/assets/101506840/150fe068-7be9-4606-af93-348225cbbe4d)


