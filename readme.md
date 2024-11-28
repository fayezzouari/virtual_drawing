
# Virtual Drawing

Virtual Drawing is a Python-based project that uses hand detection to create drawings on a virtual canvas. It leverages **OpenCV** for image processing and **MediaPipe** for hand tracking to provide an interactive experience.

## Features

- **Hand Detection**: Detects and tracks hand movements in real time.
- **Virtual Drawing**: Use gestures to draw lines and shapes on a virtual canvas.
- **Customizable Tools**: Modify the drawing colors, thickness, and modes (optional implementation).

---

## Demo

[Add a GIF or screenshot of your application in action.]

---

## Installation

Follow these steps to set up and run the Virtual Drawing project:

1. Clone the repository:
   ```bash
   git clone https://github.com/fayezzouari/virtual_drawing.git
   ```
2. Navigate to the project directory:
   ```bash
   cd virtual_drawing
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage

1. Run the main script to start the virtual drawing tool:
   ```bash
   python paint.py
   ```
2. Ensure your webcam is active. The program will display a real-time video feed.
3. Use your hand gestures to:
   - Draw on the canvas.
   - Control actions (e.g., change colors or erase if those features are implemented).

---

## Files in the Repository

- **`handDetection.py`**: Handles hand tracking and gesture recognition using MediaPipe.
- **`paint.py`**: The main application script where virtual drawing functionality is implemented.
- **`requirements.txt`**: Lists the required libraries and their versions.
- **`.gitignore`**: Specifies files and folders to exclude from version control.
- **`__pycache__/`**: Contains cached Python files.

---

## Requirements

The project has been tested with the following dependencies:

- **Python 3.x** (Recommended: 3.7 or newer)
- **OpenCV** (For video processing)
- **MediaPipe** (For hand tracking)

You can install these dependencies using the `requirements.txt` file provided.

---

## Future Improvements

The following features could be added to enhance the project:

- Adding more gestures for advanced control.
- Customizable pen colors and thickness.
- Undo/redo functionality for the canvas.
- Save the canvas as an image.

---

## Contributing

Contributions are welcome! If you'd like to enhance this project, feel free to:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add YourFeature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Contact

For questions or suggestions, feel free to reach out:

- **Name**: Fayez Zouari
- **Email**: fayez.zouari@insat.ucar.tn
- **GitHub**: [Your GitHub Profile](https://github.com/fayezzouari)

---

## Acknowledgments

- MediaPipe and OpenCV teams for providing powerful libraries.
- Open-source contributors and the Python community for continuous support.
