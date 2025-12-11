# Face Emotion Detection

This is a small project for realtime face emotion recognition using a CNN.

Files:
- `realtime.py` - Run realtime emotion recognition (webcam or `--video` file)
- `train.py` - Train the CNN and save `emotion_model.h5`
- `emotion_model.h5` - Trained Keras model (optional — large file)
- `data/` - Training and test data folders

Quick start

1. Create a virtual environment and install dependencies:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

2. Run realtime (uses webcam by default):

```powershell
python realtime.py
# or with a video file:
python realtime.py --video C:\path\to\test_video.mp4
```

Notes
- If `emotion_model.h5` is large, consider not committing it to Git and instead host it externally or use Git LFS.
- `haarcascade_frontalface_default.xml` is loaded from OpenCV's data path in `realtime.py`.
