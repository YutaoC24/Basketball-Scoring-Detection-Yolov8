### Project Description ###
This is a python program with trained yolov8 model for basketball scoring detection and scoring position mapping.
The program converts a raw basketball playing video into visual data showing the ball detection, the rim detection, the score calculated and the last scored position in a 3D-to-2D court mapping.
The folder includes a trained yolov8 model with more than 5k images and two ipynb notebooks to show the workflow from training to detection.

### Installation ###
I would recommend running Jupyter Notebook in a virtual env with libraries installed.

python3 -m venv venv
source venv/bin/activate (Windows: venv\Scripts\activate)
pip install -r requirements.txt

### Usage ###
Please follow the comments in ScoreDetect.ipynb to customize the detection and visualization process.

### Demo ###
https://raw.githubusercontent.com/YutaoC24/Basketball-Scoring-Detection-Yolov8/main/testVideo3Make.mp4
