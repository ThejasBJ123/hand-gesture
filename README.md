# Mathematical Hand Gesture Recognition

A real-time hand gesture recognition system that uses computer vision to solve mathematical problems through hand gestures.

## Features

- Real-time hand gesture detection using webcam
- Draw mathematical expressions using hand gestures
- AI-powered mathematical problem solving
- User-friendly Streamlit interface
- Split-screen display showing both camera feed and AI responses
video link: https://youtu.be/1sSwAm0XCYw?si=GCgXWOh10lLDPb7-

## Requirements

- Python 3.11.0
- Streamlit
- OpenCV
- NumPy
- Pillow
- TensorFlow
- Keras
- Webcam
- Required Python packages (see requirements.txt)

## Installation

1. Clone the repository:
```bash
git clone [repository-url]
cd Mathematical
```

2. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

## Running the Application

1. Make sure your webcam is connected and accessible
2. Run the Streamlit app:
```bash
streamlit run code/math.py
```

3. Open your web browser and navigate to the URL shown in the terminal (typically http://localhost:8501)

## Usage

1. The app interface has two main sections:
   - Left side: Webcam feed with hand gesture detection
   - Right side: AI-generated answers

2. Hand Gestures:
   - Index finger up: Draw mode
   - Thumb up: Clear canvas
   - Three fingers up: Submit drawing for AI analysis

3. The AI will analyze your drawing and provide mathematical solutions in real-time

## Project Structure

```
Mathematical/
├── code/
│   └── math.py
├── requirements.txt
└── README.md
```

## Note

Make sure to replace the API key in `math.py` with your own valid Google Generative AI API key.

## Acknowledgments

- OpenCV for computer vision
- Streamlit for web interface
- Google Generative AI for mathematical problem solving

