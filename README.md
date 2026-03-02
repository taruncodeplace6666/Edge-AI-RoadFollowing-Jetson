# Real-Time Road Following using Jetson Nano
# Project Overview

This project implements a real-time road following system using NVIDIA Jetson Nano.

The system captures live images from a camera module, processes them using a trained Convolutional Neural Network (CNN), and predicts steering directions for autonomous road following.

The trained model is optimized using TensorRT for high-performance GPU-accelerated edge inference.

# Objectives

Collect real-world road driving dataset

Train a CNN model for steering prediction

Deploy the trained model on Jetson Nano

Optimize inference using TensorRT

Achieve real-time edge AI performance

# System Architecture

Camera Module
↓
Image Preprocessing
↓
CNN Model (Trained)
↓
TensorRT Optimization
↓
Real-Time Steering Output
