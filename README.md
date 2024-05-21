# NOOR Social Robot: Voice-Activated Arabic Chatbot (ROS Package)

This ROS package enables the NOOR social robot to engage in conversations with users through voice commands and responses in Arabic. It utilizes speech recognition and text-to-speech technologies to provide a natural and interactive experience.

# Installation

**Prerequisites:**

    ROS (version X or later): ROS Installation Guide
    Python library for Arabic speech recognition (e.g., py-speech-recognition [invalid URL removed] with Arabic language model)
    Python library for Arabic text-to-speech (e.g., pyttsx3)

# Installation:

    Clone the repository:
    Bash

    git clone https://github.com/your_username/NOOR_arabic_chatbot_ros.git

    Use code with caution.

Navigate to the package directory:
Bash

cd NOOR_arabic_chatbot_ros

Use code with caution.

Install dependencies:
Bash
        pip install -r requirements.txt  # Replace with your actual installation command if using a requirements file


# Build the ROS package:
Bash

catkin_make

Source the workspace (replace <workspace_name> with your actual workspace name):
Bash

source <workspace_name>/devel/setup.bash

Use code with caution.

# Usage

    Launch the chatbot node:
    Bash

    roslaunch NOOR_arabic_chatbot_ros chatbot.launch

    Use code with caution.

    The NOOR robot will now be ready to receive voice commands in Arabic and respond accordingly. The specific behavior may depend on the implementation of the chatbot logic within the ROS node.

Technical Details (Optional)

This package typically includes the following ROS components:

    Chatbot Node: This node is responsible for receiving audio input from the robot's microphone, performing speech recognition to convert audio to Arabic text, processing the text to understand user intent, and generating Arabic text responses using text-to-speech. It would likely publish messages on topics related to recognized text and subscribe to topics for robot actions or responses.

Contributing (Optional)

We welcome contributions to improve this ROS package!

