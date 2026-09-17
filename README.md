# Machine Learning

A personal workspace for machine learning projects, experiments, and topic notes — covering fundamentals through applied projects.

## Structure

```
.
├── projects/          # End-to-end ML projects (data → model → evaluation)
│   └── firstProject.ipynb
├── topicNotes/        # Concept notebooks (linear algebra, etc.)
│   ├── dotproduct.ipynb
│   └── matrix.ipynb
├── datasets/          # Raw data files
└── requirements.txt   # Python dependencies
```

## Setup

**Python 3.x required.**

```bash
# Create and activate a virtual environment
python -m venv .venv
source .venv/bin/activate        # macOS/Linux
# .venv\Scripts\activate         # Windows

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook
```

## Dependencies

| Package | Purpose |
|---|---|
| numpy, scipy | Numerical computing |
| pandas | Data manipulation |
| matplotlib, seaborn | Visualization |
| scikit-learn | ML algorithms |
| jupyter, ipykernel | Notebook environment |
