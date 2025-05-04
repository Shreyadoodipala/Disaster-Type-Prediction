# Disaster-Type-Prediction
## Data Preparation
* Mapping labels to integers
* Resampling dataset
  + train set: 940-1500 images per class
  + dev set: 120-170 images per class
  + test set: 270-350 images per class
* Image resizing to 224 x 224
## CNN Model
* base CNN - VGG16 (pre-trained on Imagenet)
* Softmax layer - 7 nodes
* 27 epochs
* Accuracy anf F1 score is ~0.15 only
