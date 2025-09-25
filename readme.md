 # Week 3 - Decision Trees, Random Forests and Regression

In this laboratory you will go a step further towards autonomy. The pipeline is the usual one.
1. Read data from files.
2. Get a look to the data using the Pandas library.
3. Prepare the data for the training using the Scikit-learn library.
4. Train a model using the Scikit-learn library.
5. Evaluate the model using the Scikit-learn library.

This time you MUST use Decision Tree and Random Forest algorithms to model the data and make predictions. However, you are free (encouraged even) to try other approaches.

---
**Golden rule**: You should be able to explain everything you do and why you do it.
---

## Installation of the project
### uv
- Install [uv](https://docs.astral.sh/uv/getting-started/installation/) on your machine. If you want to keep things simple, usually this command is enough:

```bash
pip install uv
```

- Install the dependencies by running the following command in the root directory of the project (where the `pyproject.toml` file is located):

```bash
uv sync
```
### Without uv
Alternatively, you can install "manually" the dependencies using pip. However, also in this case, we **strongly** suggest creating a virtual environment.

## Input
We provide you with a [CMAPSS](https://data.nasa.gov/dataset/cmapss-jet-engine-simulated-data) and a structured jupyter notebook that will guide you throw the different parts.

This time, the provided notebook is not much more of a raw skeleton. Do not hesitate to reuse the code from the previous labs to complete the notebook. However, pay attention, the problem is different. *Quite* different.

## Expected Outcomes
A Jupyter notebook to be submitted via GitHub classroom.
Please make sure to:
- Explain the goal of your code (i.e., what you are doing and *why*).
- Comment on the results.
- Provide direct answers to **all** the questions posed in the notebook.

We *expect* that you take the time to understand the concepts mentioned below, the code you write and the results you obtain.



*NOTE: the concepts noted below between brackets (e.g., [ROC curve]) are considered optional content.*

### Main Tools
NumPy, pandas, scikit-learn

## Mission 1 - Implement a full ML workflow using Decision Trees and Random Forests (Week 3 - HD1-3)
- **Problem**: Predict the Remaining Useful Life (RUL) of engines using sensor data.
- **ML Concepts**: Regression, Feature Engineering, Feature Selection, Decision Trees, Random Forests, Regression metrics (MSE, RMSE, MAE, R2 score).

### Additional task (not in the notebook):

Create 5-10 slides presenting Decision Trees and Random Forests. The content of your slides should enable you to explain the following concepts:
- how to implement a simple Decision Tree using Gini impurity and Information gain
- how to implement a simple Decision Tree using entropy and Information gain
- what are the parameters of a Decision Tree?
- what are the main hyperparameters of a Decision Tree?
- know the main steps to build a Random Forest algorithm from a decision tree
- what are the main hyperparameters of a Random Forest?
- Random Forest Vs. Decision Tree: advantages and drawbacks


*NOTE: cite the sources that you used to prepare your presentation.*


## Mission 2 - Fine tuning using Genetic Algorithms (Week 3 - HD3-4)
- **Problem**: Adapt the code of Mission 1 to use Genetic Algorithms for hyperparameter tuning instead of Grid Search. Compare the results.
- **ML Concepts**: Adapt a Genetic Algorithms for hyperparameter tuning.

## Mission 3 - Peer Review (week 3 - HD 4-5)
- **Problem**: Review the work of your peers.
- **ML Concepts**: Give and get constructive feedback; team work.
- **Input**: The template of the evaluation grid is provided in the repository (in the `peer review` folder).
- **Expected Outcomes**: A filled evaluation grid to be submitted via GitHub classroom. Your code improved after the feedback of your peers.
