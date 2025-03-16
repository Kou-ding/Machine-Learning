# Machine-Learning
Notes regarding the university course "Machine learning".

### Setup
Download necessary dependencies to run the notebooks.
```bash
# Recreate conda environment
conda env create -f environment.yml
# Install dependencies from requirements txt
pip install -r requirements.txt
```

### Create snapshot
```bash
conda env export > environment.yml
pip freeze > requirements.txt
```