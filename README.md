# Driver Inattention and Drowsiness Detection 🚗👀

## Project Description

This project focuses on the development of a system for detecting driver drowsiness and attention levels using computer vision and machine learning. Key features such as eye closure, yawning, and gaze direction are analyzed to identify poor driving practices. The aim is to create a reliable system that can be integrated into vehicles to monitor drivers and enhance road safety.

## Datasets Used

### 1. **Driver Inattention Detection Dataset** 🚗🧑‍💻
This extensive grayscale dataset is designed for researchers and developers in the field of computer vision, machine learning, and deep learning. It specifically targets driver behavior analysis and driver assistance systems. The dataset includes over **14,000 labeled images**, divided into six different classes, providing a diverse and comprehensive collection for training, validation, and testing, particularly tailored for processing grayscale images.

- **Source**: [Kaggle - Driver Inattention Detection Dataset](https://www.kaggle.com/datasets/zeyad1mashhour/driver-inattention-detection-dataset)
- **Classes**: Dangerous Driving, Distracted Driving, Drinking, Safe Driving, Sleepy Driving, Yawn.

### 2. **MRL Eye Dataset** 👁️😴
This dataset is an adapted version of the original MRL Eye Dataset, containing infrared eye images classified into "Awake" and "Drowsy" states. It is divided into training, validation, and test subsets, with more than **85,000 images** captured under various lighting conditions using multiple sensors. The dataset is customized for tasks such as eye detection, gaze estimation, blink detection, and drowsiness analysis in computer vision.

- **Source**: [Kaggle - MRL Eye Dataset](https://www.kaggle.com/datasets/akashshingha850/mrl-eye-dataset)

## Project Goals 🎯
- **Detection of Driver Inattention**: Develop a model that can classify the state of the driver based on their facial features, including whether they are engaged in unsafe driving practices like distracted driving or drowsiness.
- **Real-time Monitoring**: Implement a system that can operate in real-time, providing feedback to the driver to improve safety.
- **Model Optimization**: Use machine learning techniques to improve the accuracy and performance of the detection models, utilizing the provided datasets for training and testing.

## Tech Stack 🛠️

- **Python**: Programming language used for the development of the project.
  
- **OpenCV (cv2)**: Computer vision library used for image processing tasks, such as reading, manipulating, and transforming images.

- **Matplotlib**: Plotting library used for creating static, animated, and interactive visualizations, primarily used here for displaying images and training results.

- **Pandas**: Data manipulation and analysis library used for handling datasets in tabular form (dataframes).

- **NumPy**: Core library for numerical computing in Python, used for handling arrays and mathematical operations.

- **Scikit-learn**: Machine learning library used for preprocessing data and model selection.

- **TensorFlow**: Open-source deep learning framework used for building and training machine learning models, particularly convolutional neural networks (CNNs) in this case. Used in driver inattention notebooks.
  - **Keras**: A high-level neural networks API within TensorFlow used for building and training deep learning models.

- **PyTorch**: Deep learning framework for building and training neural networks, used alongside TensorFlow in this project for flexibility or comparison. Used in eye detection notebook.

- **PIL (Python Imaging Library)**: Used for opening, manipulating, and saving images in different formats.

## Quick Recap of Results 🚗👀

In this section, I summarize the results of the driver attention and drowsiness detection system - specifically the driver inattention part. The system was evaluated on its ability to detect drowsiness, attention levels, and unsafe driving behaviors.

In this section, I summarize the results of the driver attention and drowsiness detection system - specifically the driver inattention part. The system was evaluated on its ability to detect drowsiness, attention levels, and unsafe driving behaviors.

### Results Overview:
#### Classification report:
This table gives an overview of important metrics.

<img src="https://github.com/user-attachments/assets/708d25b0-8337-48f3-b319-dd4d4de5d731" alt="Classification report" width="600"/>

#### Average Confidence per Class:
This graph shows the average confidence levels for each class in the driver inattention detection task.

<img src="https://github.com/user-attachments/assets/ca256e33-d27d-4584-8cfa-210425fb05bd" alt="Average Confidence Per Class" width="600"/>

#### Per-class accuracy:
This graph shows the accuracy for each class.

<img src="https://github.com/user-attachments/assets/b6287b12-26ab-4704-9454-6b1569b1798d" alt="per-class accuracy" width="600"/>

#### Attention Detection Example:
This image demonstrates how the system detects driver attention based on a few images from the dataset.

<img src="https://github.com/user-attachments/assets/19ae5fed-ea3a-4317-a821-51e173de51e0" alt="Attention Detection Image" width="600"/>

## License 📜

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

