# VR Calibration-Free EMG Challenge (PiEEG)

Repository for developing machine learning models for the VR Calibration-Free EMG Challenge using PiEEG biosensing data.

## Project Structure

```text
├── train/                  # Raw training dataset (.xlsx files, ignored from git)
├── test/                   # Raw testing dataset (.xlsx files, ignored from git)
├── sample_submission.csv   # Format template for competition submissions
├── .gitignore              # Git ignore rules for Python, datasets, models, and checkpoints
└── README.md
```

## Dataset

- **Training data:** `train/` contains multi-session EMG recording spreadsheets (`train_*.xlsx`).
- **Test data:** `test/` contains test recording spreadsheets (`test_*.xlsx`).
- Due to file sizes (~220 MB total), dataset spreadsheets and model weights are excluded from version control via `.gitignore`.
