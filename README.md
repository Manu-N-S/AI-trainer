
# AI Trainer - Gym Position Corrector

AI Trainer is an application designed to assist users in maintaining accurate gym positions during exercise. By leveraging **MediaPipe** for detecting body landmarks, the application checks the angles of various body parts and provides real-time feedback to help users correct their posture. This ensures that exercises are performed safely and effectively.

## Features

- **Real-time Body Landmark Detection**: Utilizes MediaPipe to accurately detect and analyze body landmarks.
- **Posture Correction**: Checks the angles of the body during exercises and provides instant feedback to correct posture.
- **User-Friendly Interface**: Built with **Tkinter**, the application offers a simple and intuitive interface.
- **Python Backend**: The backend logic is implemented in Python, making it easy to extend and customize.

## Installation

To get started with AI Trainer, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/ai-trainer.git
   cd ai-trainer
   ```

2. **Install the required dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application:**

   ```bash
   python ai_trainer.py
   ```

## How It Works

1. **Body Landmark Detection**: The application uses MediaPipe to detect key body landmarks in real-time through the webcam.

2. **Angle Calculation**: It then calculates the angles between relevant body parts during specific exercises.

3. **Position Feedback**: If the angle deviates from the optimal range, the application provides a prompt to correct the position.

4. **UI Interaction**: The user interface, developed using Tkinter, displays the live video feed along with real-time feedback on the posture.

## Usage

1. Start the application by running `ai_trainer.py`.
2. Select the exercise you want to perform.
3. Follow the on-screen instructions and adjust your position as per the feedback provided by the application.

## Demo

Include a screenshot or a GIF of the application in action here.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to improve the functionality or fix bugs.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- **MediaPipe** for the body landmark detection.
- **Tkinter** for the UI development.
- The open-source community for providing useful resources and tools.
