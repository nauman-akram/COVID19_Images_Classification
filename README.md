## Image_classification (PyTorch)

Detecting corona-virus (Covid-19) Infections in Chest X-Ray images through Transfer Learning

Using Vgg-16 and ResNet-18 pretrained models from pytorch and finetuning just only fully-connected layer of network at first so that they can learn on the learned filters of ImageNet and detect the difference between infected and normal person\'s X\-ray images. 

#### Vgg-16
> Vgg-16 fine-tuned only FC layers
![Accuracy curves](/Accuracy_Loss/vgg_fc_acc.png)  ![Loss curves](/Accuracy_Loss/vgg_fc_loss.png)

##### Confusion Matrix
![Test](/ConfusionMatrix/Only_FC/vggCM_test.png) | ![Train](/ConfusionMatrix/Only_FC/vggCM_train.png) | ![Validation](/ConfusionMatrix/Only_FC/vggCM_val.png)


> Vgg-16 fine-tuned Entire network
![Accuracy curves](/Accuracy_Loss/vgg_Ent_acc.png)  ![Loss curves](/Accuracy_Loss/vgg_Ent_loss.png)

##### Confusion Matrix
![Test](/ConfusionMatrix/Entire/vggCM_test.png) | ![Train](/ConfusionMatrix/Entire/vggCM_train.png) | ![Validation](/ConfusionMatrix/Entire/vggCM_val.png)


#### ResNet-18
> Resnet-18 fine-tuned only FC layers
![Accuracy curves](/Accuracy_Loss/resnet_fc_acc.png)  ![Loss curves](/Accuracy_Loss/resnet_fc_loss.png)

##### Confusion Matrix
![Test](/ConfusionMatrix/Only_FC/resnetCM_test.png) ![Train](/ConfusionMatrix/Only_FC/resnetCM_train.png) ![Validation](/ConfusionMatrix/Only_FC/resnetCM_val.png)


> Resnet-18 fine-tuned Entire network
![Accuracy curves](/Accuracy_Loss/resnet_Ent_acc.png)  ![Loss curves](/Accuracy_Loss/resnet_Ent_loss.png)

##### Confusion Matrix
![Test](/ConfusionMatrix/Entire/resnetCM_test.png) ![Train](/ConfusionMatrix/Entire/resnetCM_train.png) ![Validation](/ConfusionMatrix/Entire/resnetCM_val.png)





_“This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 course offered at **Information Technology University, Lahore, Pakistan**. This assignment is only for learning purposes and is not intended to be used for clinical purposes.”_
