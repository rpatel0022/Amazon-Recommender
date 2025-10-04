# Amazon Recommender System

A machine learning project for building a recommendation system using Amazon product data.

## Project Structure

- `data/` - Dataset files
- `models/` - Trained models and model artifacts
- `notebooks/` - Jupyter notebooks for analysis and experimentation
- `reports/` - Analysis reports and visualizations
- `src/` - Source code for the recommendation system
- `requirements.txt` - Python dependencies

## Getting Started

### Option 1: Using Conda (Recommended)

1. Clone the repository
2. Create conda environment: `conda create -n amazon-recommender python=3.9`
3. Activate environment: `conda activate amazon-recommender`
4. Install dependencies: `conda install jupyter pandas numpy matplotlib seaborn scikit-learn -y`
5. Start Jupyter: `jupyter notebook`

### Option 2: Using pip

1. Clone the repository
2. Create virtual environment: `python -m venv amazon-recommender-env`
3. Activate environment: `source amazon-recommender-env/bin/activate` (Linux/Mac) or `amazon-recommender-env\Scripts\activate` (Windows)
4. Install dependencies: `pip install -r requirements.txt`
5. Start Jupyter: `jupyter notebook`

### Working with the Project

- Open `notebooks/sales.ipynb` to start your analysis
- All data files are in the `data/` directory
- Save your models in the `models/` directory
- Generate reports in the `reports/` directory

## Contributing

This project is a collaboration between team members. Please create feature branches for your work.
