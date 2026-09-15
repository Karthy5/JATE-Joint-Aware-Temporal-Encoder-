## PERFORMANCE & EFFICIENCY EVALUATION REPORT
System & Throughput
* Device Used: CUDA (Nvidia RTX 4060 laptop)
* Total Frames Processed: 587
* Total Runtime: 30.90 seconds
* Overall Throughput (FPS): 19.00
* CPU Usage: 4.4%
* Average Memory Usage: 1372.19 MB

JATE Model Specific Metrics
* Model Parameters: 137,667
* Average Inference Latency: 1.30 ms
* Fastest Inference: 0.87 ms
* Slowest Inference: 1.99 ms
* (Based on 21 stable measurements)

## Key Innovation: JATE (A Unique Neural Network Architecture that replaces a traditional 3D CNN for processing spatio-temporal data involving human actions and poses.)
A core component of this project is **JATE (Joint-Aware-Temporal-Encoder), a custom Action Recognition model (`jate_model.pth`)**, developed entirely by the author. This involved:
*   Single-handedly creating a **custom dataset** comprising 150 videos relevant to retail scenarios.
*   Designing and training a **unique neural network architecture** (using PyTorch) specifically for recognizing actions like "reaching," "standing," and "walking" within the store environment. This enables it to potentially be way more efficient than a traditional 3D CNN for processing Spatio-temporal data. Making it suitable for real-time use in edge devices. 

This system demonstrates a practical application of computer vision and machine learning to solve real-world retail challenges, aligning with the objectives outlined in the Intel program.
