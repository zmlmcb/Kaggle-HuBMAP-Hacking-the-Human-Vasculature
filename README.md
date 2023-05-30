# Kaggle-HuBMAP-Hacking-the-Human-Vasculature
Kaggle compotion - HuBMAP - Hacking the Human Vasculature - Segment instances of microvascular structures from healthy human kidney tissue slides.

https://www.kaggle.com/competitions/hubmap-hacking-the-human-vasculature/overview

Still a work in progress, dice_coef of around 0.65, however it doesnt perform well on the private test dataset for scoring. experimenting with keras base models, could be room for preprocessing improvments.

uses pretrained models (ResNet/EfficentNet) with U-Net architecture to predict binary mask of blood vessels

Final version, is complete runthru for training the model and creating submission.csv. 

But if you have a model already (pretrained), you can just use model import and predict to load model and make predicitons on test data to submission.csv. Helpful for submitting on kaggle. Just be sure to update the loss function to match what the model loss function is for your model
