# Dataset for Suicide-Susceptible Students

This is a comprehensive collection of data aimed at understanding and mitigating the factors contributing to student suicides. 
The dataset comprises 14 input features, including age, gender, mental health support, academic pressure, experiences of caste/religious discrimination, mental harassment, relationship issues, depression, academic misconduct (caught in UFM), family problems, feelings of life frustration, sexual assault/harassment and blackmail, mental stress, and online gaming addiction. Each feature is binary, denoted as either 1 for "yes" and 0 for "no". The target variable indicates the likelihood of suicide susceptibility, categorized into three levels: high chances (value = 1), medium chances (value = 2), and low chances (value = 0).

## Installation and Usage Guide

### Prerequisites

Before you begin, ensure you have the following installed on your system:

- Python (version 3.x)
- Pip (Python package installer)
- Git (for cloning the repository)

### Cloning the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/AdeebKhan25/dataset_suicide_susceptible.git
cd dataset_suicide_susceptible
```

### Using the Dataset

The dataset is located in Dataset.csv. You can load and use it in your project with the following Python code:

```bash
import pandas as pd

# Load the dataset
data = pd.read_csv('dataset.csv')

# Display the first few rows
print(data.head())
```
### Additional Notes

1. This dataset is very small and in no way describes the situation at large.
2. Use the dataset cautiously for any inference.
