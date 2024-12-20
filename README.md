# Applied Statistics
**by: Phumi Tshidi (phumitshidi@gmail.com)**

<img src="https://ccap.co.ke/wp-content/uploads/2021/01/Applied-Statistics.jpg" width="450" height="300">

## Key Section

- **Overview:** Summary of the notebook.
- **Contents:** Describes the tasks and their purposes.
- **Requirements:** Lists dependencies required to run the notebook.
- **Usage Instructions:** Explains what the notebook does and how to interact with it.
- **Running the Jupyter Notebook:** Provides instructions for running the notebook using both Anaconda, Visual  Studio Code or Google Colab.
- **Conclusion**: Provides the reader with the outcome.

## Overview

This repository contains various statistical tasks and analyses implemented in tasks Jupyter notebook, aimed at providing practical examples of commonly used statistical methods.

The project Jupyter notebook performs an analysis on the PlantGrowth dataset from R.

## Contents

**1. Tasks Jupyter Notebook**

This notebook contains a series of statistical tasks and exercises that demonstrate core concepts in applied statistics:

- **Permutations and Combinations:** Explore combinatorial methods used in statistics.

- **NumPy's Normal Distribution:** Learn about normal distribution and how to simulate it using NumPy.

- **t-Test Calculation:** Perform a t-test for hypothesis testing on sample data.

- **ANOVA (Analysis of Variance):** Conduct an ANOVA test to compare the means of different groups.

**2. Project Jupyter Notebook**

This notebook demonstrates how to load and analyze the PlantGrowth dataset from R. The analysis involves exploring the relationship between plant growth in different treatment groups. It covers:

- t-test anlysis to determine the difference between the two treatment groups trt1 and trt2.
- Performing ANOVA to determine difference between the three treatment groups ctrl, trt1, and trt2.

## Requirements

Before running the notebook, ensure you have the following installed:

- [Python](https://www.python.org/downloads/) (version 3.12 or higher) also available through anaconda.
- Jupyter Notebook
- [Anaconda] (https://www.anaconda.com/download) - recommended for managing environments
- [Visual Studio Code](https://code.visualstudio.com/) - for editing and running Jupyter notebooks

You can install all required dependencies by running:

## How to run the Notebooks

There are two main ways to run the notebook: using **Anaconda** or **Visual Studio Code**.

### 1. Running with Anaconda

If you're using Anaconda, follow these steps:

1. **Clone this repository** to your local machine:

    ```bash
    git clone https://github.com/PCM11/applied-statistics
    ```

2. **Navigate to the project directory**:

    ```bash
    cd applied-statistics
    ```

3. **Create a new Conda environment** (optional but recommended) with the necessary dependencies:

    ```bash
    conda create -n tasks python=3.12
    conda create -n project python=3.12
    ```

4. **Activate the environment**:

    ```bash
    conda activate tasks
    conda activate project
    ```

5. **Install dependencies** from `requirements.txt`:

    ```bash
    pip install -r requirements.txt
    ```

6. **Launch Jupyter Notebook**:

    ```bash
    jupyter notebook
    ```

    This will open Jupyter in your web browser. Navigate to `tasks.ipynb`or `project.ipynb` and start working with the notebook.

### 2. Running with Visual Studio Code

If you prefer using Visual Studio Code:

1. **Clone the repository** to your local machine:

    ```bash
    git clone https://github.com/PCM11/applied-statistics
    ```

2. **Navigate to the project directory**:

    ```bash
    cd applied-statistics
    ```

3. **Open the folder** in Visual Studio Code:

    ```bash
    code .
    ```

4. **Install the Python extension** (if not already installed) in Visual Studio Code.

5. **Install the dependencies** by opening a terminal in Visual Studio Code and running:

    ```bash
    pip install -r requirements.txt
    ```

6. **Install the Jupyter extension** in Visual Studio Code.

7. **Open the Jupyter notebook** (`tasks.ipynb` or `project.ipynb`) in Visual Studio Code, and the notebook interface will be available to run cells interactively.

### 3. Running with Google Colab

The `tasks.ipynb` can also be found in [Google Colab](https://colab.research.google.com/github/PCM11/applied-statistics/blob/main/tasks.ipynb).

I used [openincolab.com](https://openincolab.com/)
to generate a clickable link.

## Conclusion

This repository demonstrates key statistical concepts and techniques, providing practical, hands-on applications to reinforce theoretical understanding. The exercises on permutations and combinations illustrate foundational principles of combinations while the simulation of normal distributions using NumPy highlights its importance in statistical modeling.

The hypothesis testing sections, provide valuable insights into comparing sample groups and analyzing variance across multiple datasets. The exploration of the PlantGrowth dataset from R exemplifies real-world applications, showcasing how these statistical tools can uncover meaningful relationships between treatment groups.
