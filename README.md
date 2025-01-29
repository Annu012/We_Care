# We_Care


## Overview
This project consists of two main components:
1. **Heart Disease Analysis (`heart.ipynb`)** - A Jupyter Notebook that performs data analysis on a heart disease dataset.
2. **Django Application (`manage.py`)** - A web application built with Django for managing and visualizing health-related data.

## Dataset
The notebook uses a dataset named `heart.csv`. Ensure that this file is available in the working directory before running the notebook.

## Dependencies
To run this project, install the following Python dependencies:

```bash
pip install numpy pandas matplotlib seaborn django
```

## Features
### Heart Disease Analysis
- Loads and explores the heart disease dataset.
- Performs exploratory data analysis (EDA).
- Generates visualizations using Matplotlib and Seaborn.

### Django Application
- Manages health-related data.
- Provides an administrative interface.
- Uses Django's built-in management commands.

## Usage
### Running the Jupyter Notebook
1. Open Jupyter Notebook.
2. Load `heart.ipynb`.
3. Run the cells sequentially.

### Running the Django Application
1. Navigate to the project directory.
2. Run the server using:
   ```bash
   python manage.py runserver
   ```
3. Access the application in your browser at `http://127.0.0.1:8000/`.

## Author
Created by Anisa_Shaikh.

## License
This project is licensed under the MIT License.


