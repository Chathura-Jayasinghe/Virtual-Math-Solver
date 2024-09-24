# Virtual-Math-Solver
This repo include the virtual math solver using OpenCV.

🚀 **Project Overview**

The Hand Gesture Math Solver with AI is an innovative application that allows users to solve math problems using hand gestures. Leveraging OpenCV and the Gemini API, this project aims to create an interactive way to engage with mathematics through gesture recognition.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Future Developments](#future-developments)
- [License](#license)

## Installation

To set up the project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Chathura-Jayasinghe/Virtual-Math-Solver.git
   cd hand-gesture-math-solver
2. **Create a Virtual Environment**:
   ```bash
   python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
3. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
   
4. **Run the Application**:
   ```bash
    streamlit run app.py

  
## Usage
Webcam Access: Ensure your webcam is connected and accessible.
Running the App: Use the checkbox to start the application.
Gesture Recognition: Solve math problems by writing them in the air using your hand gestures.
Output Display: The application provides an answer in the output area on the right.

## Features
Hand Gesture Recognition: Utilizes OpenCV's HandTrackingModule to recognize hand gestures for solving math problems.
AI Integration: Leverages the Gemini API to generate solutions based on user gestures.
User-Friendly Interface: A clean and interactive UI built with Streamlit for easy navigation.
Canvas Drawing: Draw math problems on a virtual canvas for the AI to process.

## Technologies Used
OpenCV: For computer vision tasks and hand gesture detection.
Gemini API: For AI-based content generation and problem-solving.
Streamlit: To create a user-friendly web application interface.
Python: The primary programming language used for development.

## Future Developments
Additional math functionalities and features.
Support for different types of math problems.
Enhanced gesture recognition accuracy.
Contributing
Contributions are welcome! If you'd like to contribute to the project, please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
