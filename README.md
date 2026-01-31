# Space Debris & Satellite Identification System

## Space Situational Awareness (SSA) using Deep Learning
This project implements a real-time computer vision pipeline to detect and classify orbital objects. 
By leveraging the YOLOv8 architecture, the system distinguishes between active mission assets and orbital debris, providing a foundation for autonomous collision avoidance protocols.

## Overview
As space becomes increasingly congested, Space Situational Awareness (SSA) is critical for mission safety. 
This project addresses the challenge of identifying 11 distinct classes of space objects, including specific satellites like SOHO, SMART-1, and XMM-Newton.

## Tech StackLanguage: 
PythonFramework: Ultralytics YOLOv8
Environment: Google Colab with GPU Acceleration
Libraries: OpenCV, PyTorch, YAML, Matplotlib

## Dataset & Training
Dataset Source: Space Debris Detection Dataset (YOLOv8 Format).
Classes: cheops, debris, double_start, earth_observation_sat_1, lisa_pathfinder, proba_2, proba_3_csc, proba_3_ocs, smart_1, soho, xmm_newton.
Hyperparameters: Trained for 30 epochs with an image size of 640x640, utilizing Early Stopping to prevent overfitting.

# Example Output:

<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/72245135-3ed6-44ba-ae86-02c0286338d7" />
<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/9646991e-5435-4a91-b019-ba56ed6d6bc8" />
<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/0f8b7638-be10-480b-a48b-151ea3617dea" />
