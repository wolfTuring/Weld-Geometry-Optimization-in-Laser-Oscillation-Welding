# Weld Geometry Optimization in Laser Oscillation Welding

## Overview
This research project focuses on optimizing weld geometry in laser oscillation welding processes through machine learning and image processing techniques. The study aims to enhance weld quality and efficiency through systematic analysis of welding parameters and automated geometry prediction.

## Research Methodology
The project follows a systematic approach combining image processing, machine learning, and experimental welding:

### 1. Data Collection and Processing Pipeline
1. Sample Collection (Weld Area Images)
2. Image Preprocessing
   - Grayscale image conversion
   - Piecewise linear enhancement
   - Filtering and denoising
   - ROI extraction
3. Neural Network Training
4. Model Prediction
5. Error Analysis

### 2. Image Processing Workflow
The weld area calculation involves several steps:
1. Original image capture
2. Grayscale conversion
3. Piecewise linear enhancement
4. Filtering and denoising
5. ROI extraction
6. Contour recognition
7. Weld area calculation

### 3. Neural Network Architecture
- Implementation of Back-Propagation Neural Network (BPNN)
- Input Layer: Parameters including LP, WS, OF, OA
- Hidden Layer: Multiple nodes with logistic regression units
- Output Layer: Weld Area prediction
- Loss Function: Mean squared error or R-square loss function
- Each node functions as an independent logistic regression unit

## Experimental Setup

### Material Specifications
- Base Material: 6061 aluminum alloy
- Composition (wt%):
  - Si: 0.56
  - Fe: 0.70
  - Cu: 0.30
  - Mn: 0.89
  - Mg: 0.93
  - Zn: 0.25
  - Ti: 0.15
  - Cr: 0.04
  - Al: Balance

### Equipment
1. Continuous Fiber Laser system
2. Oscillation welding head
3. Moving platform
4. Argon shielding gas system

### Welding Configuration
- Material combination: 6061Al - Ti-6Al-4V
- Laser beam oscillation pattern: Controlled directional scanning
- Specialized setup for asymmetric laser welding

## Key Features
- Automated image processing pipeline
- Neural network-based prediction model
- Real-time weld geometry optimization
- Comprehensive error analysis system

## Technologies Used
- Image Processing Libraries
- Machine Learning Framework (BPNN implementation)
- Continuous Fiber Laser System
- Data Acquisition and Analysis Tools

## Results
[To be added: Experimental results and performance metrics]

## Team Members
Group 7
[List of team members]

## Documentation
For detailed information about the experimental setup and methodology, please refer to the presentation file in this repository.
