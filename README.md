# Kaggle-Carvana-3rd-place-solution

Implementation of U-Net + Dilated Convolution. Network detail is shown on below figure.
I used this network in "Carvana-Image-Masking-Challenge-Competition".

![network](https://github.com/lyakaap/Kaggle-Carvana-3rd-place-solution/blob/master/network.png)

put all training data, testing data, masks, sample_submission.csv and train_masks.csv in input/

## model.py
A script of model definition.

## losses.py
A script of loss functions definition.

## train.py
start training by ```python train.py```

## make_submission.py
make submission file by ```python make_submission```
