# Building Segmentation using U-Net and LinkNet 🏗️🖼️

## Overview
This project implements building segmentation using two popular deep learning models: **U-Net** and **LinkNet**. The primary goal is to accurately segment buildings from satellite images, utilizing a publicly available dataset labeled on **Roboflow**. 🌍

## Models
- **U-Net**: A convolutional neural network architecture primarily designed for biomedical image segmentation, known for its ability to produce precise segmentations with limited data. 🤖
- **LinkNet**: A lightweight architecture that combines features from both U-Net and ResNet, designed for efficient segmentation tasks while maintaining high accuracy. 📈

## Dataset
The dataset used in this project consists of satellite images from **Vietnam**. The images have been annotated and are publicly available on [Roboflow](https://roboflow.com/). The dataset is formatted for easy integration into deep learning workflows, making it suitable for training and evaluating the segmentation models. 📷

![Screenshot 2024-10-27 171538](https://github.com/user-attachments/assets/dd0183da-4a09-4a47-af65-a2f5b26c9e93)

## Environment
This project is implemented using **Google Colab Pro**, providing an efficient and accessible environment for training deep learning models with GPU acceleration. 🚀

## Colab Notebook
The project is hosted on Google Colab. You can access the notebook using the following link:

[Open Google Colab Notebook]([https://colab.research.google.com/drive/1n60-gREYcK7_L2zncz9Q-BF74rxOOe5n?usp=sharing]) 📒

## Installation
To run this project, follow these steps in the Google Colab notebook:
1. **Open the Colab Notebook**: Click the link above to open the notebook in Google Colab. 🌐
2. **Set Up the Environment**: Follow the instructions in the notebook to set up the necessary libraries and dependencies. 📦
3. **Load the Dataset**: Use the dataset provided through Roboflow. 📥
4. **Train the Models**: Execute the cells to train both the U-Net and LinkNet models on the satellite images. 🏋️‍♂️
5. **Evaluate the Models**: Run the evaluation section to assess the performance of both models on the test set. 🔍

## Results
### Test dataset
![Screenshot 2024-10-27 171603](https://github.com/user-attachments/assets/162044ee-ba6a-4341-81b0-14e1cedd4320)
### Real-world dataset
![Screenshot 2024-10-27 171457](https://github.com/user-attachments/assets/3da2e013-d4d4-43e5-8629-4eab9b038124)


## Contributing
Contributions are welcome! If you would like to contribute to this project, please fork the repository and create a pull request. 🤝

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. 📄

## Acknowledgments
- [Roboflow](https://roboflow.com/) for providing the dataset. 🙏
- The developers of U-Net and LinkNet for their foundational work in image segmentation. 💡
