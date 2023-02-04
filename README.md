# Data Analytics Project Template
A project template to quick start data analytics and machine learning task.

# About The Project
It is convenient to adopt a good project structure having support of git when starting with a project for data analysis and machine learning. This project is made for Visual Studio Code (**vscode**) but can be used in any IDE.

# Project Highlights
1. Jupyter Notebook
2. Pandas
3. Polars
4. matplotlib
5. numpy
6. seaborn
7. plotly.express
8. **data** directory git ignored
9. module finder for code sharing

## Recommended Steps:

1. Install Conda - [Instructions Here](https://conda.io/projects/conda/en/latest/user-guide/install/index.html)
2. Install vscode (optional) - [Download Here](https://code.visualstudio.com/download)
3. Clone this repo
4. `src/example/data/archive.zip` - unzip for testing
5. Run `src/example/main.ipynb`
6. Get started with your own project 🥳

## VSCODE template generation
1. Open `Command Palette`
2. Select `Tasks: Run Task`
3. Select `Template: Generate Analysis Module`
4. `Enter the name` of a new module directory
5. The template directory is generated in the `src` directory with the given name
6. Start working on the task


https://user-images.githubusercontent.com/11065002/209532606-c62df522-2136-4837-a736-4568801411a9.mov

## Project Directory Structure
```
.
├── .git
├── .gitignore
├── .templates
├── .vscode
└── src
    ├── example
    │   ├── .gitignore
    │   ├── __module_finder__.py
    │   ├── data
    │   │   ├── Churn_Modelling.csv
    │   │   └── archive.zip
    │   └── main.ipynb
    └── utils
        ├── __init__.py
        └── display.py
```
 


