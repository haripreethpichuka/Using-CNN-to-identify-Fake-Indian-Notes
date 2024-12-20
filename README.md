# Using Convolutional Neural Networks Identifying Fake Indian Notes
## Project Overview

This project leverages deep learning techniques to detect fake Indian currency notes. Using a Convolutional Neural Network (CNN), the system analyzes images of Indian currency and classifies them as authentic or counterfeit. The model is trained to learn patterns and features that differentiate real currency notes from fake ones, providing a reliable tool for identification.

## Features

- **Automated Detection**: Utilizes CNN for precise and automated fake currency classification.
- **Web Interface**: Flask framework for an intuitive and user-friendly interface.
- **Robust Analysis**: Combines image preprocessing with deep learning for improved accuracy.

## Technologies Used

### Frameworks and Libraries

- ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
- ![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
- ![Pillow](https://img.shields.io/badge/Pillow-333333?style=for-the-badge&logo=pillow&logoColor=white)
- ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
- ![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
- **Xception Architecture**: A deep learning architecture used for feature extraction and classification.

### System Architecture

1. **Image Preprocessing**: Input images are preprocessed to enhance quality and prepare them for analysis.
2. **Feature Extraction**: CNN, utilizing the Xception architecture, automatically extracts relevant features from the images.
3. **Classification**: The model classifies the notes as real or fake based on learned patterns.
4. **Web Interface**: Flask allows users to upload images and view results interactively.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone <repository-link>
   ```
2. Navigate to the project directory:
   ```bash
   cd fake-currency-detection
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Flask application:
   ```bash
   python app.py
   ```
5. Open the web interface in your browser at `http://localhost:5000`.

## Results

- **Accuracy**: The model achieved high accuracy during training and testing, ensuring reliable performance.
- **Interactive Interface**: Users can upload images of currency notes and get real-time classification results.




## Future Scope

- Extend the dataset to include more diverse samples for robust training.
- Integrate additional security features for better reliability.
- Deploy on cloud platforms for scalability.

## Credits

- **Frameworks**: NumPy, Keras, TensorFlow, Pillow, Flask
- **Architecture**: Xception
- **Tools**: Python
- **Dataset**: Custom dataset of Indian currency notes

---

