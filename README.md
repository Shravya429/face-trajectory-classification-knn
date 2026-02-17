Real-time face trajectory classification system using KNN and Earth Mover’s Distance with YOLO-based detection. Designed for surveillance analytics and edge AI deployment (Jetson-ready).

# Accurate Classification of True Face Trajectories Using Distance-Based KNN

This repository contains my Master's research project focused on real-time facial trajectory classification in surveillance systems.

---

## Project Overview

This system integrates deep learning-based object detection with classical machine learning classification to validate true facial motion trajectories in video streams.

Pipeline Architecture:

Video Input → YOLO Detection → Centroid Tracking → Feature Extraction → KNN + Earth Mover's Distance Classification

---

## Key Contributions

- Distance-based KNN trajectory validation
- Earth Mover’s Distance similarity metric
- Multi-object tracking integration
- Real-time processing (25–30 FPS)
- 93% classification accuracy
- Designed for NVIDIA Jetson edge deployment

---

## Performance Metrics

- Accuracy: 93%
- FPS: 25–30
- Optimized Latency: 65ms (post optimization)
- Evaluated using confusion matrix and ablation study

---

## Tech Stack

- Python
- OpenCV
- NumPy
- YOLO
- KNN (custom implementation)
- Matplotlib

---

## Repository Structure

src/ → Core implementation  
research/ → IEEE-style conference paper  
screenshots/ → Performance graphs & outputs  

---

## Research Paper

Full conference-grade paper available in:

research/Conference_Submission_Grade_Paper.pdf

---

## Future Work

- NVIDIA Jetson Nano deployment
- TensorRT acceleration
- FP16 inference optimization
- Power and thermal profiling
- Multi-camera distributed architecture

---
_***Topics Focused*:
computer-vision
machine-learning
knn
object-tracking
yolo
edge-ai
jetson
real-time-ai
opencv
deep-learning***_

## Author

Shravya Parusha  
Master of Science – Computer Science & Information Systems
