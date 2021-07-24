# g20-machine-learning
G20 Machine learning, Concordia University

## Dataset
[WSI images uploaded on Kaggle] (www.kaggle.com/dataset/83e2c6521bb92381b0b0f8f0f6f0a44dd89f5680ef8500254ba9102b5c292314)

## RN_50_SPIPAKMED_PROGRESSIVE_LEARNING_0.98_KAPPA_SCORE
In this notebook, I used the presizing technique. I used the images of size 448, 1024, 2048 which were resized to 224, 512, 1024.
I have used the progressive learning technique. I trained model on the 224 images and saved the last epoch model weight. After that, I took the last saved model. I unfreezed it and again trained on the 512 images size. The same procedure is followed during 1024 images size. The classification interpreation of the models are as shown.

## For 224 x 224 image size 
Kappa Score: 0.975190
Error_rate: 0.041451

![image](https://user-images.githubusercontent.com/32462145/114242967-c28b9a00-9959-11eb-9858-01e2072bc8c4.png)

## For 512 x 512 image size
Kappa Score: 	0.964852
Error_rate: 0.036269

![image](https://user-images.githubusercontent.com/32462145/114243057-f070de80-9959-11eb-973b-f2335541fb6d.png)

## For 1024 x 1024 image size
Kappa Score: 0.98
Error_rate: 0.021

![image](https://user-images.githubusercontent.com/32462145/114243085-fcf53700-9959-11eb-885f-c57bc260c15d.png)

