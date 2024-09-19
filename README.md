# U2Net Model training over thyroid nodule segmentation
The ```u2net-thyroid-nodule.ipynb``` will contain all the code for training and testing.
The output we will be getting are one model file, 2 csv files (train and test data), one prediction folder
In the ipynb file, in the first cell, please update the test, train, val - image and mask folder respectively according to the system

# About Data
The data is Thyroid Nodule Segementation Dataset, obtained from Stanford medical image dataset, we have done all the preprocessing before hand and saved in image format, for the sake of transferability.
The dataset is available in Kaggle : https://www.kaggle.com/datasets/sivalalsir/stanford-thyroid-cine-clips-train-test-val-splits
Please download this dataset (~2GB)

# Pytorch GPU access
pytorch should be installed according to the cuda version. You can refer to it in https://pytorch.org/
to check for the GPU in pytorch, please run the following command

```import torch```

```print(torch.cuda.is_available())```
