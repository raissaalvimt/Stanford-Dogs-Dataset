🐶 Stanford Dogs Dataset


📚 Overview

The Stanford Dogs Dataset is a comprehensive collection of images and annotations of 120 different dog breeds. It’s designed for machine learning and computer vision tasks, such as image classification and object detection.


For more information, visit the official dataset website:  

👉 [Stanford Dogs Dataset Website](http://vision.stanford.edu/aditya86/ImageNetDogs/)


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

📁 **images/**  
   ├── 🐕 **breed_1/**              # Images for breed 1  
   ├── 🐕 **breed_2/**              # Images for breed 2  
   ├── ...                          # Images for other breeds  

📁 **annotations/**  
   └── 📝 **Bounding Box Annotations**   # Bounding box annotations for images  

📄 **file_list.mat**  
   └── 🗂️ List of all files in the dataset  

📄 **train_list.mat**  
   └── 🏋️ List and labels of all training images  

📄 **test_list.mat**  
   └── 🧪 List and labels of all test images  

📄 **train_data.mat**  
   └── 📊 Feature matrix (after applying histogram intersection kernel)  

📄 **test_data.mat**  
   └── 📊 Feature matrix (after applying histogram intersection kernel)  

📄 **train_info.mat**  
   └── 🏷️ Labels and IDs corresponding to training data  

💖 Acknowledgments and Thanks
A huge thanks to all contributors who made this dataset possible.
Special gratitude goes to Aditya Khosla and the Stanford University Vision Lab for curating and maintaining this valuable resource.

We also appreciate the open-source community for their tools and libraries, which help us explore datasets like this one.

If you use this dataset or found it helpful, feel free to ⭐ star this repository and share your work with us!
Together, we can build amazing machine learning projects. 🚀🐾


