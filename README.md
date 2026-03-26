#  Pose Perfect

Pose Perfect is an interactive computer vision-based game that uses real-time body pose detection to challenge users to match different poses. The system uses a trained machine learning model along with MediaPipe to detect and classify human poses through a webcam.


## Features

*  Real-time pose detection using webcam
*  Machine Learning model for pose classification
*  Timer-based gameplay with score tracking
*  High score system (saved locally)
*  Interactive UI built with Pygame
*  Visual pose guidance for users


##  Tech Stack

* Python
* TensorFlow / Keras
* MediaPipe
* OpenCV
* NumPy
* Pygame


##  Requirements

* **Python Version:** 3.10.x (Recommended: 3.10.11)

##  Installation & Setup

Follow these steps to run the project locally:

### 1. Create a virtual environment (Python 3.10)

```bash
py -3.10 -m venv venv
```

### 2. Activate the virtual environment

```bash
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
pip install protobuf==3.20.3
```

### 4. Run the project

```bash
python Game.py
```


## Project Structure

```
pose-perfect/
│
├── Game.py
├── requirements.txt
├── model.h5
├── labels.npy
├── high_score.txt
│
├── Images/
├── Background_Images/
├── poseImages/
├── Fonts/
```


## How to Play

1. Launch the game
2. Click **Start**
3. Match your body pose with the pose shown on screen
4. Earn points for correct poses
5. Try to beat your high score


## Important Notes

* Ensure your **full body is visible** in the webcam
* Good lighting improves pose detection accuracy
* Do NOT use Python versions above 3.10 (may cause dependency issues)


## Future Improvements

* Add more poses and difficulty levels
* Multiplayer mode
* Sound effects and animations
* Web-based version


## Acknowledgements

* MediaPipe for pose detection
* TensorFlow/Keras for model training
* OpenCV for image processing


## How to Run (Quick)

```bash
py -3.10 -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
pip install protobuf==3.20.3
python Game.py
```

