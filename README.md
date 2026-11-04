# AI Course Code

Welcome to the AI course Python tutorial and exercises repository! This repository serves as a comprehensive resource for our course, offering a series of tutorials and exercises to help you master key concepts and tools for applying artificial intelligence techniques in the field of civil engineering. 

## Course Description

This course provides an introduction to the concepts and applications of artificial intelligence (AI) in civil engineering. The course covers the fundamentals of data science, machine learning, and deep learning methods, with a focus on their application to civil engineering problems. The course also provides an introduction to Python programming language, which is a popular tool for data analysis, modeling, and simulation. In
this course, students will learn about the different AI techniques, algorithms, and models that can be used in various aspects of civil engineering, such as transportation, smart and sustainable city, asset management and geoinformatics.

## Course Plans

This course will majorly cover the following contents:

- Introduction
  * Fundamentals of artificial intelligence
  * Various open data resources
- Python Programming Skills
  * Basic Python syntax
  * Flow control statements
  * Function and class
- Regression Theory and Applications
  * Simple and multiple linear regression
  * Regularization
  * Applications in engineering problems
- Classification Theory and Applications
  * Linear discriminative analysis
  * Logistic regression
  * Support vector machine
  * Decision trees
  * Ensemble learning approaches
  * Applications in engineering problems
- Deep Learning
  * Artificial neural networks
  * Convolutional neural networks
  * Graph neural networks
  * Recurrent neural networks
  * Attention mechanisms
  * Large language models
  * Applications in engineering problems
- Unsupervised Learning
  * K-means clustering
  * Expectation maximization
  * Principal components analysis
  * Applications in engineering problems
- Transportation and Civil Engineering Applications
  * Transportation applications I
  * Transportation applications II
  * Applications beyond transportation

## Current lesson folders

The active tutorials, exercises, and their required data are organised as follows:

1. Practices of Python language
2. Regression models
3. Classification models
4. Artificial neural networks
5. Transportation applications I
6. Unsupervised learning
7. Recurrent neural networks
8. Convolutional neural networks
9. Graph neural networks
10. Attention mechanisms
11. Large language models
12. Transportation applications II
13. Others

Folder `13 Others` archives previous versions and supplementary materials. The active lesson folders contain only the current `tutorialXX` and `exerciseXX` notebooks together with the local files they require.

## Set up the Python environment

Install [Anaconda](https://www.anaconda.com/) first. The file `environment.yml` in this repository creates one environment, named `ai-course`, with Python 3.12 and the packages used by the notebooks: NumPy, pandas, Matplotlib, scikit-learn, XGBoost, PyTorch, torchinfo, and Transformers.

On Windows, open Anaconda Prompt. On Mac, open Terminal. Move to the folder that contains `environment.yml`, then run:

```bash
conda env create -f environment.yml
conda activate ai-course
python -m ipykernel install --user --name ai-course --display-name "AI Course"
```

In Jupyter, VS Code, or Cursor, choose the kernel named **AI Course** before running a notebook. To update an environment you already created, run `conda env update -f environment.yml --prune` from the same folder.

## Usage of this repository

In this GitHub repository, we have prepared Python code for both tutorials and exercises for each topic, along with relevant datasets. The tutorials will be briefly introduced by teaching assistants and are intended for self-study by students to enhance their understanding of Python and artificial intelligence-related techniques. After becoming familiar with the tutorials, each section is accompanied by exercises designed for students to practice. Students are required to write code and generate results based on the exercise requirements.
