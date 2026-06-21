# VeilNet-V2X-Perception-Showcase
> ⚠️ This repository is a public overview of ongoing research work.
> Source code, trained models, and datasets are not publicly available at this time due to research and publication considerations.
V2X-fused multi-modal perception framework for robust understanding of occluded long-range driving scenarios.

# VeilNet: V2X-Fused Perception for Robust Understanding of Occluded Long-Range Driving Scenarios

## Overview

VeilNet is a multi-modal perception framework designed to improve autonomous driving safety in occluded and long-range scenarios using Vehicle-to-Everything (V2X) communication.

The system fuses information from onboard and infrastructure sensors to enhance environmental understanding.

## Problem Statement

Autonomous vehicles often struggle to detect objects hidden behind obstacles or outside the field of view.

VeilNet addresses this challenge by integrating infrastructure-based sensing and V2X communication.

## My Contributions

- Dataset preparation and preprocessing
- Multi-modal sensor fusion
- Semantic segmentation using ResUNet++
- Model training and evaluation
- Performance analysis and visualization

## Technologies Used

- Python
- PyTorch
- CARLA
- SUMO
- V2X-Sim
- OpenCV
- NumPy
- Matplotlib

## Dataset

This work uses the V2X-Sim dataset for cooperative perception research.

## Methodology

Describe your pipeline briefly:

1. Data collection
2. Sensor synchronization
3. Data preprocessing
4. Multi-modal fusion
5. Semantic segmentation
6. Evaluation

## Results

- Training Mean IoU: 95.66%
- Test Mean IoU: 92.96%
- Mean Dice/F1 Score: 97.65%
- Pixel Accuracy: 99.09%


  ## System Architecture

![Architecture](images/architecture.jpg)

#IoU vs Dice Comparison Bar graph
![Comparison].(images/iou_vs_dice_comparison.png)

## Sample Results

![Results](images/result_19.png)


## Future Work

- Real-time deployment
- Enhanced sensor fusion
- Integration with autonomous navigation systems

## Publication Status

Manuscript currently in preparation.

Code available upon request after publication approval.
