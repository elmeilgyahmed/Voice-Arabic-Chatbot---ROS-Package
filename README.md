# NOOR Social Robot: Voice-Activated Arabic Chatbot (ROS Package)

This ROS package enables the NOOR social robot to engage in conversations with users through voice commands and responses in Arabic. It utilizes speech recognition and text-to-speech technologies to provide a natural and interactive experience.

# Installation

**Prerequisites:**

    ROS (version X or later): ROS Installation Guide
    Python library for Arabic speech recognition (e.g., py-speech-recognition [invalid URL removed] with Arabic language model)
    Python library for Arabic text-to-speech (e.g., pyttsx3)

# Installation:

    Clone the repository:

    git clone https://github.com/elmeilgyahmed/Voice-Arabic-Chatbot---ROS-Package.git


Navigate to the package directory:

    cd NOOR_arabic_chatbot_ros

Install dependencies:

        pip install -r requirements.txt  

# Build the ROS package:

    catkin_make


source <workspace_name>/devel/setup.bash


# Usage

    Launch the chatbot node:
    Bash

    roslaunch NOOR_arabic_chatbot_ros chatbot.launch


The NOOR robot will now be ready to receive voice commands in Arabic and respond accordingly.
The specific behavior may depend on the implementation of the chatbot logic within the ROS node.

Technical Details (Optional)

This package typically includes the following ROS components:

    Chatbot Node: This node is responsible for receiving audio input from the robot's microphone, performing speech recognition to convert audio to Arabic text, processing the text to understand user intent, and generating Arabic text responses using text-to-speech. It would likely publish messages on topics related to recognized text and subscribe to topics for robot actions or responses.

Contributing (Optional)

We welcome contributions to improve this ROS package!

