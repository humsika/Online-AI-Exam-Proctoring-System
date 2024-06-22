# AI Online Exam Proctoring System

## Overview

The AI Online Exam Proctoring System is designed to ensure the integrity and security of remote examinations. Utilizing advanced machine learning and computer vision techniques, this system is capable of user authentication, face verification, mobile phone detection, multiple persons’ detection, speech recognition, and mouse location tracking. The system's robust algorithms help in identifying fraudulent activities with an impressive 97% accuracy rate.

## Features

- **User Authentication**: Verifies the identity of the exam taker.
- **Face Verification**: Ensures that the correct person is taking the exam.
- **Mobile Phone Detection**: Detects the presence of mobile phones during the exam.
- **Multiple Persons Detection**: Identifies if more than one person is present in the frame.
- **Speech Recognition**: Monitors for unauthorized speech during the exam.
- **Mouse Location Tracking**: Tracks mouse movements to detect suspicious activities.

## Technologies Used

- **Python**
- **TensorFlow**
- **OpenCV**
- **Face Recognition Libraries**
- **YOLOv8**
- **Numpy**
- **Pandas**
- **Scikit-learn**

## Project Structure

The project is organized into several key components, each responsible for different aspects of the proctoring system:

- **alerts.py**: Handles alert generation for detected fraudulent activities.
- **check_individual.py**: Manages the identification and verification of individual users.
- **face_verification.py**: Implements face verification techniques to confirm user identity.
- **person_phone_detection.py**: Detects the presence of multiple persons and mobile phones.
- **proctoring.py**: The main script that integrates all components and runs the proctoring system.

## Setup and Installation

 **Clone the repository**:
   ```sh
   git clone https://github.com/yourusername/ai-online-exam-proctoring.git
   cd ai-online-exam-proctoring
