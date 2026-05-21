# ⌨️ Keystroke Dynamics Authenticator

A behavioral biometrics system that authenticates users 
based on *how* they type, not just *what* they type.

## What It Does
- Records the timing rhythm between keypresses during login
- Builds a personal typing profile from multiple samples
- Rejects login attempts that don't match your typing pattern
- Shows a real-time confidence score on the UI

## Stack
- Python, scikit-learn, NumPy, SQLite, Tkinter

## Setup
```bash
git clone https://github.com/YOURUSERNAME/keystroke-dynamics-auth
cd keystroke-dynamics-auth
pip install -r requirements.txt
python src/capture.py    # collect your typing samples first
python src/train.py      # build your profile
python src/authenticate.py  # run the login system
```

## Preview
![Login UI](screenshots/login_ui.png)

## What I Learned
- Behavioral biometrics and how they differ from traditional auth
- Feature extraction from raw timing data
- Training and evaluating a KNN classifier
- Building a practical ML pipeline from scratch

## ⚠️ Disclaimer
Built for educational and research purposes only.
