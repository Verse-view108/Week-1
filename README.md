# Week-1
- Mounted Google Drive to access your dataset located at /content/drive/MyDrive/Dataset.
- Loaded and preprocessed the dataset using tf.keras.utils.image_dataset_from_directory, splitting it into training and validation sets (80%/20%) with a batch size of 32, resized images to 128x128, and shuffled the data.
- Optimized the datasets with cache() and prefetch() for better performance.
- Calculated class distribution percentages for training, validation, and overall datasets, visualizing them with bar plots.
- Computed class weights to handle imbalanced data and created a dictionary for use in model training.
- Defined a data augmentation pipeline with RandomFlip, RandomRotation, RandomZoom, and RandomContrast, applying it to the training dataset.
- Visualized sample images from the augmented training dataset with their corresponding class labels.
