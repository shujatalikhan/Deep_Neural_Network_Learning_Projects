# Transfer Learning?
### Transfer learning is a machine learning technique where a model trained on one task is re-purposed on a second related task.
## Why we Use Transfer Learning?
### In practice, very few people train an entire Convolutional Network from scratch (with random initialization), because it is relatively rare to have a dataset of sufficient size. Instead, it is common to pretrain a ConvNet on a very large dataset (e.g. ImageNet, which contains 1.2 million images with 1000 categories), and then use the ConvNet either as an initialization or a fixed feature extractor for the task of interest.
## Types of Transfer Learning?
* Pre trained network.
* Fixed Feature Extraction Method
* Fine-Tunning Method
![13244_2018_639_Fig10_HTML](https://user-images.githubusercontent.com/49519213/57741054-344e0100-76bb-11e9-8259-5a45c09b3d56.png)
## Tip When to use Pretrained ,Fixed Feature Extraction Method,Fine-Tunning Method
![scenario](https://user-images.githubusercontent.com/49519213/57742512-ab869380-76c1-11e9-8ee1-3b81391d78f9.jpg)
# Project on  Image clssification:
*Dataset:datasets download -d salader/dogs-vs-cats
*Convolutional_Neural_Network.ipynb
*vgg16_transfer_Learning _fine_tuning.ipynb
*Vgg16_xfer_tuned_Weights .ipynnb
Projects were made on google-colab
## Conclusion : Validation  accuracy for model made from scrath is far more less than the VGG-16 fine-tune Model and Feature Extraction 
