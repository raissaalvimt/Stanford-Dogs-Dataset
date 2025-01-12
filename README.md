🐶 Stanford Dogs Dataset


📚 Overview

The Stanford Dogs Dataset is a comprehensive collection of images and annotations of 120 different dog breeds. It’s designed for machine learning and computer vision tasks, such as image classification and object detection.


For more information, visit the official dataset website:

👉 Stanford Dogs Dataset Website

If you use this dataset in a publication, please cite it as described on the website.

📁 File Information

Here’s what’s included in the dataset:

images/

📂 Images of different breeds are stored in separate folders.

annotations/

📝 Bounding box annotations for each image.

file_list.mat

🗂️ List of all files in the dataset.

train_list.mat

🏋️ List and labels for all training images.

test_list.mat

🧪 List and labels for all test images.

📊 Training Splits

For testing with fewer than 100 images per class:

The first n indices for each class in train_list.mat were used, where n represents the number of training images per class.

🔍 Feature Information

Files:

train_data.mat & test_data.mat

Contains the feature matrix after applying the histogram intersection kernel.


train_fg_data.mat & test_fg_data.mat

Contains the feature matrix before applying the histogram intersection kernel.

train_info.mat & test_info.mat

Contains labels and IDs corresponding to images in the feature matrix.

💾 Directory Structure

stanford-dogs-dataset/

├── images/               # Dog breed images

│   ├── breed_1/          # Images for breed 1

│   ├── breed_2/          # Images for breed 2

│   ├── ...

├── annotations/          # Bounding box annotations

├── file_list.mat         # List of all files

├── train_list.mat        # Training images and labels

├── test_list.mat         # Test images and labels

├── train_data.mat        # Feature matrix (after kernel)

├── test_data.mat         # Feature matrix (after kernel)

└── train_info.mat        # Labels and IDs

📧 Contact

For questions or additional information, reach out to:

Aditya Khosla

✉️ Email: aditya86@cs.stanford.edu


📝 Citation

If you use this dataset, please cite it as described on the official website.


🌟 Thank You for Using the Stanford Dogs Dataset!

Bring your models to life with this incredible collection of furry friends! 🐕✨

