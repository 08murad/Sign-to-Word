# Sign-to-Word using Tensorflow CNN for Deaf and Mute Individuals Communication

This project provides a Python-based implementation for recognizing and visualizing sign gestures of deaf and mute individuals. Leveraging MediaPipe’s holistic model and OpenCV, the system detects and interprets face, hand, and pose landmarks in real-time, offering transformative applications in assistive communication and education.

# Features

- Real-Time Gesture Recognition: Detects and visualizes hand, face, and body landmarks in real-time.
- Custom Visualization: Styled landmarks for clear and intuitive representation of gestures.
- Modular Design: Easy integration with gesture classification or language translation modules.
- Scalable Framework: Suitable for various domains such as healthcare, education, and social integration.

# Prerequisites

To run the code, ensure the following are installed on your system:

- Python 3.12.1
- Required Python libraries:
  - OpenCV
  - MediaPipe
  - NumPy
  - Matplotlib

Install the dependencies using pip:
```bash
pip install opencv-python mediapipe numpy matplotlib
```

# File Structure

- Code Files: The main code resides in the Jupyter Notebook (`actd_cnn.ipynb`), which includes:
  - Functions for MediaPipe integration.
  - Landmark visualization utilities.
  - Real-time processing pipeline.
- Output Visualizations: The code generates real-time overlays on video feeds, showing detected landmarks.

# Usage Instructions

1. Clone or download the project files.
2. Open the `actd_cnn.ipynb` file in Jupyter Notebook or your preferred IDE.
3. Ensure your webcam is connected for real-time gesture detection.
4. Run the notebook step by step to:
   - Initialize MediaPipe’s holistic model.
   - Process video frames from the webcam.
   - Visualize detected landmarks in real-time.

# How It Works

1. Data Acquisition: Captures input frames from a webcam feed.
2. Preprocessing: Converts frames to RGB and processes them using MediaPipe’s holistic model.
3. Landmark Detection: Extracts and overlays landmarks for face, hands, and body.
4. Visualization: Displays styled landmarks for better clarity and interpretation.

# Applications

- Assistive Communication: Enables deaf and mute individuals to convey gestures effectively.
- Education: Promotes inclusive learning with gesture-based teaching tools.
- Healthcare: Supports therapy and rehabilitation.
- Social Integration: Facilitates seamless communication in social and professional environments.

 # Future Enhancements

- Gesture Classification: Integrate classification models for interpreting specific sign languages.
- Language Translation: Expand functionality to translate gestures into text or speech.
- Enhanced Performance: Optimize processing speed for lower-end devices.

 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests with enhancements or fixes.

 License

This project is licensed under the MIT License. Feel free to use and modify the code for personal or commercial purposes.

# Acknowledgments

- MediaPipe: For providing the holistic model and drawing utilities.
- OpenCV: For image and video processing capabilities.


For any queries or support, please contact:
Md. Murad Hasan
Email: 08muradhasan@gmail.com


