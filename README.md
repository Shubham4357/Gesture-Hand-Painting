# Gesture Hand Painter

## Description
Gesture Hand Painter is an AI-powered virtual drawing tool that allows users to paint on a screen using hand gestures detected through a webcam. It utilizes OpenCV and MediaPipe to track hand movements, enabling color selection, brush strokes, and an eraser mode when the palm is fully open. This project is ideal for interactive applications, AI-based gesture control, and digital art experiments.

## Features

https://github.com/user-attachments/assets/79863ab9-730d-46f7-9e0a-64131283f1e8


- **Hand Gesture Detection**: Uses MediaPipe to track hand landmarks.
- **Drawing with Index Finger**: Move your index finger to draw.
- **Color Selection**: Change colors by touching the index finger and thumb.
- **Eraser Mode**: Activated when all five fingers are open.
- **Smooth Drawing Experience**: Reduces flickering and improves accuracy.
- **User-Friendly Interface**: Overlay UI elements to display active colors and eraser status.

## Technologies Used
- Python
- OpenCV
- MediaPipe
- NumPy

## Installation
Follow these steps to set up and run the project:

### Prerequisites
Ensure you have Python installed (Python 3.7 or later recommended). Install the required libraries using:

```sh
pip install opencv-python mediapipe numpy
```

### Running the Project
After installing dependencies, execute the script using:

```sh
python gesture_painter.py
```

## Usage Instructions
1. **Start the application**: Run the script, and the webcam will activate.
2. **Drawing**: Move your index finger to draw on the canvas.
3. **Change Color**: Touch your index finger and thumb to switch colors.
4. **Eraser Mode**: Show your entire palm (all five fingers visible) to activate the eraser.
5. **Exit the application**: Press `q` to close the window.

## Project Structure
```
/gesture-hand-painting
│── gesture_painter.py   # Main script for hand gesture-based painting
│── README.md            # Project documentation
│── requirements.txt     # List of dependencies
```

## Future Enhancements
- Add different brush sizes and shapes.
- Implement a save feature to store drawings.
- Introduce gesture-based menu controls.

## Contributing
Contributions are welcome! Feel free to fork this repository and submit a pull request with your improvements.

## License
This project is open-source and available under the MIT License.

## Contact
For any queries or suggestions, feel free to reach out to me via GitHub issues or discussions.

---

