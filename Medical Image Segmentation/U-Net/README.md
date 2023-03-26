### pytorch Implementation of U-Net, R2U-Net, Attention U-Net, Attention R2U-Net


**U-Net: Convolutional Networks for Biomedical Image Segmentation**

https://arxiv.org/abs/1505.04597

**Recurrent Residual Convolutional Neural Network based on U-Net (R2U-Net) for Medical Image Segmentation**

https://arxiv.org/abs/1802.06955

**Attention U-Net: Learning Where to Look for the Pancreas**

https://arxiv.org/abs/1804.03999

**Attention R2U-Net : Just integration of two recent advanced works (R2U-Net + Attention U-Net)**


## U-Net
![U-Net](https://user-images.githubusercontent.com/72977734/227777237-61717c0f-00bd-4dc5-9420-00cd98e88c51.png)

## R2U-Net
![R2U-Net](https://user-images.githubusercontent.com/72977734/227777254-e24f713a-d96a-456e-bad8-f1c817783d04.png)



## Attention U-Net
![AttU-Net](https://user-images.githubusercontent.com/72977734/227777273-b5005df6-b23d-4a7d-8a01-4acddfe26dc0.png)




## Attention R2U-Net
![AttR2U-Net](https://user-images.githubusercontent.com/72977734/227777292-fb735a2e-e503-4cf2-9013-de1e180ad5d0.png)



## Evaluation
We just test the models with [ISIC 2018 dataset](https://challenge2018.isic-archive.com/task1/training/).The dataset was split into three subsets, training set, validation set, and test set, which the proportion is 70%, 10% and 20% of the whole dataset, respectively. The entire dataset contains 2594 images where 1815 images were used for training, 259 for validation and 520 for testing models. 

![Evaluation](https://user-images.githubusercontent.com/72977734/227777482-e45eb952-6121-4a0b-909a-9f7e6cdfaaa9.png)
for training, 259 for validation and 520 for testing models.

![evaluation](/img/Evaluation.png)
