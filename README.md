# CS867-Assignment-03
CS867-Computer Vision-Assignment 03


# Dataset
Kaggle Intel-Classification-Images. The dataset is divided into 3 categories i.e. Training set, validation set and test set.

# Trained Model Weights
https://drive.google.com/file/d/19t1lj2dtC2Y5pZPvCPr4HsQcn3pMKWvy/view?usp=sharing

# Training Settings
Simple CNN Model 
history = model.fit(train_images, train_labels, batch_size=128, epochs=20, validation_split = 0.2)

VGG16 Model Single Layer
history2 = model2.fit(train_features, train_labels, batch_size=128, epochs=15, validation_split = 0.2)

Ensemble Neural Networks Train Settings
histories.append(models[i].fit(train_features[train_idx], train_labels[train_idx], batch_size=128, epochs=10, validation_split = 0.1))
