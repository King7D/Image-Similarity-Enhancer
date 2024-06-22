## Image Similarity Finder and Downloader
This project aims to help developers quickly find their pre-processed images and accelerate the training process of checkpoints and models. The script downloads images, resizes them, and uses a pre-trained ResNet50 model to find and rename the closest matching images in a directory. The script evaluates the similarity of images and copies the matching images to a specified folder.

---

## Prerequisites
Ensure you have the following libraries installed:
- TensorFlow
- NumPy
- scikit-learn
- Pillow
- datetime
- shutil

---

## Usage
1. Download Images
Use the download_images.py script to download images based on specified keywords.
2. Resize Images
Use the resize_images.py script to resize images in the training directory.
3. Find and Rename Closest Matching Images
Use the image_similarity_finder.py script to find and rename the closest matching images in the new images directory.

---

## Purpose
This project is designed to help developers quickly find their pre-processed images and accelerate the training process of checkpoints and models. By automating the process of downloading, resizing, and finding similar images, developers can save time and focus on training and fine-tuning their models.