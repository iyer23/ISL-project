# Indian Sign Language (ISL) Recognition

## Project Overview
This project uses MediaPipe to extract hand landmarks and a Random Forest classifier to recognize Indian Sign Language (ISL) gestures.

## Project Files
- `ISL_MediaPipe_Training.ipynb` — training notebook
- `ISL_MediaPipe_Training_v2.ipynb` — updated training notebook
- `ISL dataset.zip` — dataset archive
- `isl_mediapipe_output/isl_landmarks.csv` — extracted hand landmark data
- `isl_mediapipe_output/isl_mediapipe_random_forest.joblib` — trained Random Forest model

## Setup
1. Install Python 3.11.
2. Install the dependencies listed in `requirements.txt`.
3. Extract `ISL dataset.zip` if you need the original dataset.
4. Open a training notebook in Jupyter Notebook and run its cells in order.

## Technologies
- Python
- MediaPipe
- OpenCV
- NumPy
- Pandas
- Scikit-learn
- Joblib

## Notes
The model and dataset are included for project use. Results depend on the training data and the prediction pipeline.
