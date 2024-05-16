# 3D Semantic Reconstruction from 2D images: A COLMAP - UNet Fusion with Voting

CSCI 5561: Computer Vision (Final Project)

Advisor: Prof. Volkan Isler (University of Minnesota, CSE)

Team: Amitabha Deb, Srijan Pal, Roozbeh Eshani, Tejasvi Bansal

### Introduction
We developed a method to reconstruct 3D scenes from 2D images while preserving semantic information. Using COLMAP, we generated sparse and dense 3D point clouds from the images. We designed and trained a custom U-Net-based CNN architecture to segment the images. By combining segmentation data with the 3D point cloud using a voting algorithm, we achieved accurate 3D semantic scene reconstruction. Our approach offers a novel way to understand and interpret 3D environments from 2D imagery. 

<img src="https://github.com/srijanpal07/3D-Semantic-Segmentation-From-2D-Images/blob/main/semantic_reconstruction_methodology.png" width="400" height="400">

### Results -

<img src="https://github.com/srijanpal07/3D-Semantic-Segmentation-From-2D-Images/blob/main/results.png" width="400" height="400">


Files: https://drive.google.com/drive/folders/17CZ5d8uK5eoNXu-UYhfO5NaT3g1WDCZR?usp=sharing
