# facial-expression-by-prompt
This project is a GAN model that can reconstruct an input image based on an input prompt (sad, happy, poker) and change the facial expresiion on input image based on this prompt.
The code ran in Colab and you have to add some files to your Google Drive in order to run the code. You can see the links and details of these files in the following:
1. data.zip: This file must contain 100 images of different expressions for each prompt(sad, happy, poker). I made it by my own from FFHQ dataset: https://drive.google.com/file/d/1i8OrJzSAZi8wA2RwLMfMGJLELWQX321V/view?usp=sharing
2. Pre-trained weights of Style-GAN for pytorch:  https://github.com/lernapparat/lernapparat/blob/master/style_gan/pytorch_style_gan.ipynb
3. dlib shape predictor: https://www.kaggle.com/datasets/codebreaker619/face-landmark-shape-predictor
4. And as test set you can use any images with size 1024*1024 (e.g ffhq images)
5. In the following link you can find latent spaces for images in data.zip: https://drive.google.com/file/d/18nNrtB-yvLxk9cc0k3vOII7ECKxVgdKZ/view?usp=sharing
   
![example1](https://github.com/kamyarMhd/facial-expression-by-prompt/assets/127598555/2cc74df1-e68b-45bc-8d4f-b6cdd14e28df)

Refrences:
1. Chao Yang, S.-N. L. Unconstrained facial expression trans- fer using style-based generator. Facebook AI, 2019.
2. Karras, T., L.-S. . A. T. A style-based generator architecture for generative adversarial networks. CVPR, 2019.
3. Rameen Abdal, Y. Q. and Wonka, P. Image2stylegan: How to embed images into the stylegan latent space? KAUST, 2019.
4. Shu, Z., S. C. . H. T. M. Deblurgan: Blind motion de- blurring using conditional adversarial networks. CVPR, 2019.
