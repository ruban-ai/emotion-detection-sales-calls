# Emotion Detection in Sales Calls

Computer vision system for detecting customer emotions during sales conversations using deep learning.

The project explores how facial expression recognition can be used to understand customer sentiment and engagement during sales interactions.

---

## Problem

In sales conversations, understanding customer emotions can provide valuable insights into:

- engagement level
- confusion
- frustration
- interest

Sales teams often rely on subjective judgment to interpret customer reactions.

Goal:
Build an AI system capable of **detecting emotions from facial expressions during sales conversations**.

---

## Approach

The system uses computer vision models to analyze facial expressions from video frames.

Pipeline:

Sales Call Video  
↓  
Frame Extraction  
↓  
Face Detection  
↓  
Emotion Classification Model  
↓  
Emotion Prediction

---

## Emotion Categories

The model predicts common emotional states such as:

- happy
- neutral
- surprised
- frustrated
- confused
- disengaged

These signals can help analyze customer sentiment during conversations.

---

## Model Architecture

The system uses deep learning models trained on facial expression datasets.

Components include:

- face detection
- image preprocessing
- CNN-based emotion classification

---

## Dataset

Training uses publicly available facial expression datasets and curated samples from recorded video interactions.

Examples:

- facial expression datasets
- labeled emotion images

---

## Experiments

Experiments evaluate:

- emotion classification accuracy
- model performance on video frames
- inference speed

---

## Tech Stack

Python  
Deep Learning  
Computer Vision  
OpenCV  
PyTorch

---

## Potential Applications

- sales coaching tools
- conversation intelligence platforms
- customer sentiment analysis
- training simulations for sales teams
