# Hand Gesture Recognition using MediaPipe and OpenCV

This repository contains code for real-time hand gesture recognition using MediaPipe and OpenCV. The system detects hand gestures through a webcam feed and categorizes them into predefined actions.

## Overview

The system utilizes the following components:

- **OpenCV**: Used for capturing video frames from the webcam and displaying the processed frames.
- **MediaPipe**: Employs the MediaPipe Holistic model for detecting hand gestures and facial landmarks.
- **NumPy**: Facilitates numerical computations and data manipulation.
- **Matplotlib**: Utilized for visualizing the processed video frames.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/vigneshmagalingam/sign-language-to-Text-conversion.git
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the main script:

    ```bash
    python Main(2).py
    ```

2. When the script is executed, it will open the webcam feed showing real-time hand gesture recognition.

3. Perform various hand gestures in front of the webcam, and the system will detect and classify them.

4. Press 'q' to exit the program.

## Customization

- **Actions**: Define custom actions by modifying the `actions` array in the script.
- **Parameters**: Adjust parameters such as `min_detection_confidence` and `min_tracking_confidence` in the script for desired detection sensitivity.

## Data Collection

The repository also includes functionalities for data collection:

- Thirty videos worth of data are recorded for each action.
- Videos consist of 30 frames each, capturing different instances of the action.
- Data recorded by our teammates by own

