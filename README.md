# AI_Human_Image_Classification
A Transformer model which can classify Images as either Real images or AI generated.

Project Idea<br><br>
● The advancements in AI-generated imagery have significantly improved their quality, raising issues regarding their authenticity and reliability.<br>
● Our approach emphasizes the enhancement of VIT model robustness through the exploration of diverse data augmentation techniques.<br>
● Additionally, we have refined the model's performance by adjusting key hyperparameters, including learning rates and the architecture of a newly integrated fully connected layer.<br>
<br>
Dataset<br><br>
● The dataset contains two classes - REAL and FAKE. For REAL, the images are collected from Krizhevsky & Hinton's CIFAR-10 dataset. For the FAKE images, equivalent of CIFAR-10 is generated with Stable Diffusion version 1.4.<br>
● There are 100,000 images for training (50k per class) and 20,000 for testing (10k per class).<br><br>

Results:<br>
<img width="1467" alt="Screenshot 2024-07-10 at 11 44 13 AM" src="https://github.com/ashwin63/AI_Human_Image_Classification/assets/26385060/0ec746ae-bdc9-4ece-bbaf-703b57b2fd07">

Classification of images as Real / AI generated on sample images can be seen on the Jupyter Notebook file.<br>
References:
Krizhevsky, A., & Hinton, G. (2009). Learning multiple layers of features from tiny images.

Bird, J.J. and Lotfi, A., 2024. CIFAKE: Image Classification and Explainable Identification of AI-Generated Synthetic Images. IEEE Access.

Real images are from Krizhevsky & Hinton (2009), fake images are from Bird & Lotfi (2024). The Bird & Lotfi study is available here.
