# Small Python Data-Processing App

A beginner-friendly Python project that loads, cleans, and analyzes a dataset using Pandas and NumPy. The project uses a virtual environment and Jupyter Notebook to demonstrate a simple data-processing workflow.

## Project Overview

This project uses the Palmer Penguins dataset to demonstrate how raw data can be transformed into clean, usable data through Python.

## Features

- Load a CSV dataset using Pandas.
- Inspect dataset structure, data types, missing values, and duplicate rows.
- Clean column names using reusable functions.
- Remove duplicate rows.
- Handle missing numerical and categorical values.
- Perform numerical analysis using NumPy.
- Calculate mean, median, minimum, maximum, range, and standard deviation.
- Save the cleaned dataset as a new CSV file.
- Verify the cleaned data.

## Technologies Used

- **Python** — core programming language
- **Pandas** — data loading and cleaning
- **NumPy** — numerical processing
- **Jupyter Notebook** — interactive development
- **Virtual Environment (`venv`)** — dependency isolation

## Project Structure

```text
AI_ML_Learning/
├── data/
│   ├── penguins_size.csv
│   └── penguins_cleaned.csv
├── Notebook/
│   └── dataprocessing.ipynb
├── requirements.txt
└── README.md
```

The `venv/` directory is excluded from the repository because dependencies can be installed using `requirements.txt`.

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/Redie-tes/Small_data_processingAPP.git
cd small-data-processingApp
```
### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the environment

**Windows:**

```bash
venv\Scripts\activate
```

### 4. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 5. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook inside the `Notebook/` folder and run the cells in order.

## Dataset

The project uses `penguins_size.csv`, containing penguin measurements and categorical information such as species, island, and sex.

The cleaned output is saved as `penguins_cleaned.csv`, leaving the original dataset unchanged.

## Expected Outcome

After processing, the cleaned dataset should have no missing values or duplicate rows. Numerical summaries provide insights into penguin measurements, including culmen dimensions, flipper length, and body mass.

## Learning Objectives

This project demonstrates practical skills in:

- Working with CSV files.
- Writing reusable Python functions.
- Handling missing and duplicate data.
- Using NumPy arrays and statistical functions.
- Managing Python dependencies.
- Working with Jupyter Notebook.

## Author

Created as a Python data-processing learning project.
