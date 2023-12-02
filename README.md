# FoodVision 
Welcome to the FoodVision project! In this GitHub repository, we'll be exploring the exciting journey of building and scaling up our image classification model. Previously, in the notebook we crafted Food Vision mini, a transfer learning model that outperformed the original Food101 paper with just 10% of the data.

### But what if we unleashed the full power of our dataset?

Enter Food Vision Big™ - our ambitious endeavor to utilize the entire Food101 dataset, consisting of a whopping 75,750 training images and 25,250 testing images. Our objective this time? To surpass the performance of DeepFood, a 2016 paper that achieved a top-1 accuracy of 77.4% using a Convolutional Neural Network trained for 2-3 days.

** Note: **  Top-1 accuracy measures the accuracy for the highest softmax activation value output by the model.

## Project Overview

### Data Comparison
|                | Food Vision Big            | Food Vision Mini                |
|----------------|---------------------------|---------------------------------|
| Dataset source | TensorFlow Datasets        | Preprocessed download from Kaggle|
| Train data      | 75,750 images             | 7,575 images                    |
| Test data       | 25,250 images             | 25,250 images                   |
| Mixed precision | Yes                       | No                              |
| Data loading    | Performant tf.data API    | TensorFlow pre-built function   |
| Target results  | 77.4% top-1 accuracy      | 50.76% top-1 accuracy           |

## What We're Going to Cover
1. Using TensorFlow Datasets for data download and exploration.
2. Creating a preprocessing function for our data.
3. Batching & preparing datasets for modeling to ensure efficiency.
4. Creating modeling callbacks for monitoring and optimization.
5. Setting up mixed precision training for faster model training.
6. Building a feature extraction model (refer to Transfer Learning Part 1: Feature Extraction).
7. Fine-tuning the feature extraction model (refer to Transfer Learning Part 2: Fine-Tuning).
8. Viewing training results on TensorBoard.
   
Alongside our quest to beat the DeepFood paper, we'll dive into two key methods to enhance the speed of our model training: prefetching and mixed precision training.

This project was in the course of TensorFlow


