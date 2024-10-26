# Deepfake Detector

A deep learning-based system for detecting facial and voice deepfakes.

## Project Structure

```
deepfake-detector/
├── src/                    # Source code
│   ├── face_detection/     # Face detection and analysis
│   ├── voice_detection/    # Voice analysis
│   ├── preprocessing/      # Data preprocessing
│   ├── models/            # ML models
│   └── utils/             # Utility functions
├── data/                  # Dataset storage
│   ├── training/         
│   ├── validation/       
│   └── test/            
├── notebooks/             # Jupyter notebooks
├── tests/                 # Unit tests
├── docs/                  # Documentation
├── requirements.txt       # Python dependencies
└── README.md
```

## Setup
1. Clone the repository
2. Create virtual environment
3. Install dependencies: `pip install -r requirements.txt`

## Branch Strategy
- main: Production-ready code
- develop: Integration branch
- feature/*: Individual features

## Team Workflow
1. Create feature branch from develop
2. Work on your feature
3. Create pull request to develop
4. Code review
5. Merge to develop
