# Trade-offs-in-Grasp-Detection
Trade-offs in Grasp Detection: Analyzing the Balance Between Accuracy and Computational Time Using Reduced Layer Convolutional Neural Networks

## Description

This project examines the trade-off between grasp detection accuracy and computational speed in robotic systems. By analyzing the performance of state-of-the-art Convolutional Neural Networks (CNNs), we determine if reduced-layer CNNs can sustain necessary accuracy and precision for effective robotic handling without compromising real-time functionality. We conducted comparative experiments across various CNN architectures with different numbers of convolutional layers to quantify their grasp detection capabilities in terms of accuracy, precision, and processing time.

## Key Findings

- Select CNNs can deliver efficient grasp detection with minimal performance loss.
- The feasibility of employing reduced-layer CNNs in robotic systems has been demonstrated, paving the way for enhanced object manipulation in real-time operational settings.

## Installation

Before running the code, ensure you have the following dependencies installed:

- Python 3.x
- TensorFlow (or an equivalent ML library)
- NumPy
- Matplotlib (for visualization)

To install these dependencies, use the following command:

```bash
pip install tensorflow numpy matplotlib
```

## Dataset

The dataset used was the cornell dataset. You will need to download the dataset separately and change the path in the code when using it

## Credits

This project was conducted by Mikhail Chirkoot at the University of Witswatersrand under the supervision of Dr. Benjamin Rosman.

## Future Directions

- Diversify datasets for model training to improve robustness and generalizability.
- Explore more extensive hyperparameter optimization techniques.
- Incorporate confidence intervals in performance metrics for better reliability assessment.
- Evaluate adaptability and robustness under various conditions such as noise and occlusion.
