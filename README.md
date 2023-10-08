# Panorama Auto-Stitching

## Overview

In this comprehensive project undertaken at Carnegie Mellon University, I developed an image stitching tool relying heavily on feature matching and homography. The linchpin of the feature matching component was the BRIEF feature descriptor. BRIEF descriptors, known for their efficiency and power, contend closely with complex descriptors like SIFT but allow for real-time computation.

Through this assignment, not only did I learn to seamlessly merge two images into one panoramic image but also to craft my augmented reality photographs.

**Note:** This project is an integral part of the computer vision course I'm undergoing at Carnegie Mellon University. All the code and content are credited to Carnegie Mellon University.

## Learning Objectives

- Grasp and apply 2D planar and linear transformations.
- Conduct automatic image warping to align and merge images.
- Delve into the world of basic augmented reality.

## Assignment Breakdown

### Part I: Planar Homography

1. **BRIEF Descriptor**: 
    - Introduction to the BRIEF Descriptor, setting the stage for further tasks.

2. **Compute Homography** : 
    - Derived the 3x3 transformation matrix, a key element in determining the homography between two images.

3. **RANSAC**: 
    - Implemented RANSAC, a robust method to compute homography, especially useful when outliers are present.

4. **Automated Homography Estimation and Warping**: 
    - Combined the power of BRIEF and RANSAC to automatically estimate the homography and then warp the images to align them.

### Part 2: Panoramas Stitching 

5. **Image Stitching**: 
    - Stitched two warped images to generate a continuous panorama.

6. **Generate Panoramas**: 
    - Perfected the panorama by removing any artifacts and seamlessly merging the images.

## Visualization ## 

Image 1:

<img width="827" alt="l" src="https://github.com/sankalp-rajeev/Panorama-Auto-Stitching/assets/81537336/f3ce21ef-1cc3-4f63-a120-39854d05faf6">

Image 2 :

![r](https://github.com/sankalp-rajeev/Panorama-Auto-Stitching/assets/81537336/4ea8445a-10f7-4be2-bebf-61402c1ae727)

Panoramic Image:

![pano](https://github.com/sankalp-rajeev/Panorama-Auto-Stitching/assets/81537336/5ca21e3a-ce31-4270-9051-551cadb87246)

## Insights & Takeaways

- Developed a profound understanding of image homography and the intricate steps in merging two images.
- Grasped the strength and efficiency of the BRIEF descriptor in feature matching.
- Understood the importance and application of RANSAC in tackling outliers during homography estimation.
- Acquired practical skills in the realm of augmented reality.

## Acknowledgments

A heartfelt thank you to the faculty and fellow students at Carnegie Mellon University for their unwavering support, insightful discussions, and peerless guidance throughout this project.
