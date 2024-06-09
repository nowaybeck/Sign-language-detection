# Sign Language Detection
Sign language is an essential form of communication for individuals with hearing impairments. This project focuses on developing a sign language detection model that can recognize and interpret various sign language gestures.
This project aims to detect hand signs for sign language using two different models - one based on LSTM and another using Teachable Machine. The LSTM model is implemented in `app.py`, allowing real-time hand sign detection through your computer's camera. The second model, based on Teachable Machine, is implemented in `testlstm.py`. This model utilizes a pre-trained model generated using your custom dataset of hand sign images. Both models are capable of real-time sign language detection.
## Features
1. Real-time Detection: Both models provide real-time sign language detection using the computer's camera, enabling instant communication through gestures.
2. Customizable Models: The LSTM model allows users to train and customize the system for specific sign language gestures by using their own datasets.
3. Fine-tuning Capability: The Teachable Machine model, based on a pre-trained model, can be fine-tuned on custom datasets, providing adaptability to different sign language variations.
4. Adaptability: The Teachable Machine model is adaptable to different sign language variations, enabling users to create models for specific contexts.
5. Extensibility: The codebase is open for exploration and modification, allowing users to extend the functionality, integrate additional features, or experiment with different architectures.
## Requirements
-Python 3.6 or later
-TensorFlow 2.x
-OpenCV
-Other dependencies can be installed using `requirements.txt`
## Installation
To run the Sign language detector locally, follow these steps:
1.Clone or download this repository to your local machine.
2. Install the required dependencies: pip install -r requirements.txt
3. Download the pre-trained models or train your own.
## Usage
## LSTM Model (app.py)
1. Run the following command to start the application: python app.py
2. The camera will open, and you can perform hand signs in front of it. The application will detect and display the corresponding sign.
## Teachable Machine Model (testlstm.py)
1. Run the following command to test the LSTM model using Teachable Machine: python testlstm.py
2. The camera will open, and you can perform hand signs in front of it. The application will detect and display the corresponding sign.
## Custom Dataset
The models were trained using a custom dataset of hand sign images, located in the Image directory. The dataset includes diverse examples to improve the model's accuracy and generalization.
## Note
Make sure your camera is properly configured and accessible for real-time sign language detection.
Feel free to explore and modify the code according to your requirements. If you encounter any issues or have suggestions for improvement, please create an issue in the repository.
## Contributions
Contributions are welcome! If you'd like to contribute to this project, please follow these steps:
-Fork the repository.
-Create a new branch.
-Make your changes and commit them.
-Push your changes to your forked repository.
-Submit a pull request describing the changes you've made.
