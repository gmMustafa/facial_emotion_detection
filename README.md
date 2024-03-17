# Real-time Facial Emotion Recognition Web Application

This repository hosts a cutting-edge web application designed for real-time facial emotion recognition, blending Flask, Python, HTML, CSS, and advanced machine learning models. It's distinguished by its use of three pivotal models: Convolutional Neural Network (CNN), Chehra model, and Deep Neural Network (DNN), each meticulously trained for high accuracy in detecting diverse emotional states. A hallmark of this project is its interactive visualization, which dynamically showcases emotion detection results and graphically represents them for insightful analysis.

## Project Overview

Understanding and analyzing human emotions in real time can significantly impact various domains such as mental health assessment, user experience enhancement, and educational tools. Our web application offers a robust and user-friendly platform for real-time analysis and categorization of human emotions through facial expressions, leveraging cutting-edge AI and human-computer interaction advancements.

## Key Features

- **Real-time Emotion Detection:** Detect and analyze facial emotions in live video streams using your web camera.
- **Interactive Visualization:** Dynamic display of detected emotions on the web page, along with a bar chart graph for an in-depth analysis over time.
- **Model Flexibility:** Switch seamlessly between CNN, Chehra, and DNN models, catering to various needs for accuracy and computational efficiency.
- **User-Friendly Interface:** An intuitive and navigable front-end ensures a smooth user experience.
- **Comprehensive Reporting:** Generate detailed reports of detected emotions for further analysis.

## Motivation

The project aims to bridge the gap between human emotions and technology, providing insights into emotional dynamics and enhancing interactions in digital spaces. It stands as a testament to the potential applications of machine learning in real-time emotion detection and interactive visualization.

## Installation and Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/facial_emotion_detection.git
   ```
2. **Download the architecture and model zip file** from the following URL, and extract it into the root folder of the cloned repository:
   ```plaintext
   https://tinyurl.com/439nt2th
   ```
3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
4. **Launch the application:**
   ```bash
   python app.py
   ```
5. **Access the application** by navigating to `http://127.0.0.1:5000/` in your web browser.

   
## Usage Guide

- Grant the application permission to use your web camera.
- Select the desired emotion detection model from the dropdown menu.
- Experience real-time emotion detection and visualization.
- Utilize the "Generate Report" feature for a session summary of detected emotions.

## Technologies Used

- **Flask:** Serves as the backbone for server-side operations.
- **HTML/CSS/JavaScript:** Crafts a responsive and interactive UI.
- **TensorFlow/Keras:** For model training and inference.
- **OpenCV:** For video stream processing and face detection.
- **Dlib:** Facial landmark detection in the Chehra model.

## Screenshots

### UI Overview
![UI Overview](https://github.com/gmMustafa/facial_emotion_detection/assets/26876754/cfaa212d-6665-4ca7-a932-bebb2139eecf)

![Emotion Detection Results](https://github.com/gmMustafa/facial_emotion_detection/assets/26876754/08304192-b494-49ec-9700-188c2e52880e)

## Contributing

We welcome contributions to improve functionality, model performance, or user experience. Please fork the repository and submit pull requests for review.

## License

This project is licensed under the MIT License - see [LICENSE](LICENSE.md) for details.

## Acknowledgments

Our heartfelt thanks go to the facial emotion recognition community for their research and datasets that have significantly contributed to this project's success.

## Future Directions

Future enhancements will focus on integrating more advanced neural networks, refining user interfaces, and expanding the application's reach into various sectors, guided by ethical considerations and a commitment to innovation.

## Disclaimer
This project is associated with the "Interactive Visualization Project" under the "AI Systems and Applications" pillar, part of the Master of Science in Artificial Intelligence degree at Friedrich-Alexander-Universität Erlangen-Nürnberg.

For a detailed exploration of the project's methodology, evaluation, and insights, refer to the presentation slides at https://tinyurl.com/4ppxptxp.

---
