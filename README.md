# Exploration in Artificial Intelligence Lab

Python lab programs for **AD/AM/IT/CB/CZ/CS6102 – Exploration in Artificial Intelligence** (Sep–Dec 2026), organized experiment-wise from the lab manual.

## Experiments
1. [Student Marks, Percentage, Grade and Academic Performance](experiments/experiment_01.py)
2. [Electricity Billing System Using Conditional Statements and Loops](experiments/experiment_02.py)
3. [Menu-Driven Student Information Management](experiments/experiment_03.py)
4. [Student Record Management Using Lists, Tuples, Dictionaries, Files and CSV](experiments/experiment_04.py)
5. [IoT Sensor Data Analysis Using NumPy](experiments/experiment_05.py)
6. [Analysis of Student Dataset Using Pandas Series and Data Frames](experiments/experiment_06.py)
7. [Data Cleaning and Exploratory Data Analysis Using Pandas](experiments/experiment_07.py)
8. [Data Cleaning, Exploratory Data Analysis and Visualization Using Pandas and Matplotlib](experiments/experiment_08.py)
9. [Data Visualization Using Matplotlib](experiments/experiment_09.py)
10. [Prompt Design and Evaluation Using Generative AI](experiments/experiment_10.py)
11. [Role-Based, Zero-Shot, One-Shot and Few-Shot Prompting](experiments/experiment_11.py)
12. [AI-Assisted Generation of Technical Content and Python Programs](experiments/experiment_12.py)
13. [AI-Powered Study Assistant Using Python and Generative AI](experiments/experiment_13.py)

## Requirements
Python 3; NumPy (Experiment 5); Pandas (Experiments 6–13); Matplotlib (Experiments 8–9).

Install dependencies:
```bash
python -m pip install numpy pandas matplotlib
```

Run from the repository root:
```bash
python experiments/experiment_01.py
```

Experiments 8–13 use CSV input files and retain the Google Colab upload statements from the manual. For local execution, place the required CSV in the working directory and adapt/remove the `google.colab` upload lines. See [data/README.md](data/README.md) for dataset filenames.

## Notes
- Experiments 10 and 11 use rule-based demonstration/evaluation logic, not a live language model.
- Experiment 13 uses CSV keyword-overlap retrieval, not a live Generative AI model.
- All 13 Python files were checked for syntax validity after extraction.