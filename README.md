# Pasta Detection Robot 🍝🤖

A ROS2-based object detection project for identifying and detecting pasta using computer vision and deep learning techniques.

## Overview

This project implements an automated system to detect and classify pasta using ROS2 (Robot Operating System 2) framework. It combines computer vision, object detection algorithms, and robotic middleware to create a practical application for automated pasta recognition.

## Features

- **Real-time Object Detection**: Detect pasta objects in images and video streams
- **ROS2 Integration**: Built on ROS2 middleware for robot communication and coordination
- **Scalable Architecture**: Modular design for easy integration with robotic systems
- **Cross-platform Support**: Works on Linux (primary), with shell and PowerShell scripts for automation

## Project Structure

```
Pasta-Detection-Robot-/
├── README.md                      # Project documentation
├── comp8430_week10/               # Weekly assignments/deliverables
├── images/                        # Sample images and dataset
└── [Additional Python modules and scripts]
```

## Technology Stack

### Languages
- **Python** (55.1%) - Core detection algorithms and ROS2 node implementations
- **Shell** (34.8%) - Build scripts, setup, and automation
- **PowerShell** (10.1%) - Windows environment support and deployment

### Key Technologies
- **ROS2** - Robot Operating System for middleware and communication
- **Computer Vision** - Object detection and image processing
- **Deep Learning** - Neural networks for pasta classification

## Getting Started

### Prerequisites

- ROS2 (Humble or later recommended)
- Python 3.8+
- opencv-python
- TensorFlow or PyTorch (depending on the detection model)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/shauravkhadka/Pasta-Detection-Robot-.git
   cd Pasta-Detection-Robot-
   ```

2. **Set up ROS2 environment**
   ```bash
   source /opt/ros/<ros2-distro>/setup.bash
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt  # if available
   ```

### Usage

Run the main detection node:
```bash
ros2 run pasta_detection detection_node
```

Or launch the full system:
```bash
ros2 launch pasta_detection detection.launch.py
```

## Project Organization

- **comp8430_week10/**: Contains coursework and weekly deliverables
- **images/**: Training dataset and test images for pasta detection
- **scripts/**: Automation and setup scripts (Bash and PowerShell)

## Development

This project appears to be part of coursework (COMP8430), implementing practical robotics applications using ROS2 and object detection.

### Contributing

For improvements or bug fixes:
1. Create a new branch (`git checkout -b feature/improvement`)
2. Make your changes
3. Submit a pull request

## License

This project is open source. Check the repository for specific license details.

## Author

**Shaurav Khadka** - [GitHub Profile](https://github.com/shauravkhadka)

## Links

- [GitHub Repository](https://github.com/shauravkhadka/Pasta-Detection-Robot-)
- [ROS2 Documentation](https://docs.ros.org/en/humble/)
- [OpenCV Documentation](https://docs.opencv.org/)

## Support

For questions or issues, please open an [issue](https://github.com/shauravkhadka/Pasta-Detection-Robot-/issues) on GitHub.

---

*Last Updated: June 2026*