# Logistic Regression

An introduction to logistic regression, the workhorse algorithm for classification. You start from the intuition behind the model, move to fitting it with scikit-learn, extend it to multiple classes, and finish by applying it to a new dataset yourself.

## Learning Objectives

By the end of this repository, you should be able to:

- Explain how logistic regression turns a linear model into class probabilities.
- Fit and evaluate a logistic regression model with scikit-learn.
- Extend binary classification to the multiclass setting.
- Apply logistic regression end to end on the Titanic dataset.

## Learning Path

Work through the notebooks in order:

| File / Folder | Description |
|---|---|
| [**1 - Logistic Regression**](1_logistic_regression.ipynb) | The intuition behind logistic regression, explained graphically. |
| [**2 - Logistic Regression with sklearn**](2_logistic_regression_sklearn.ipynb) | Fitting and evaluating the model with scikit-learn. |
| [**3 - Multiclass Classification**](3_multiclass_classification.ipynb) | Extending logistic regression to more than two classes. |
| [**4 - Logistic Regression Exercise**](4_logistic_regression_exercise.ipynb) | Your turn: implement logistic regression on the Titanic dataset. |

### Additional Folders and Files

| File / Folder | Description |
|---|---|
| [**Data**](data/) | Datasets used across the notebooks. |
| [**Solutions**](solutions/) | Reference solutions. |
| [**pyproject.toml**](pyproject.toml) | Project configuration and dependencies. |
| [**uv.lock**](uv.lock) | Dependency lock file. |

## Setup

> [!NOTE]
> Throughout these steps, text in angle brackets like `<repo-name>` is a
> **placeholder**. Replace it, including the `< >` brackets, with your own
> value. For example, `cd <repo-name>` becomes `cd ds-logistic-regression`.

### 1. Create the Repository from the Template

Click **Use this template** on GitHub.

When creating the repository:

- Set yourself as the **Owner**
- Choose a repository name
- Disable **Include all branches**
- Click **Create repository**

> [!IMPORTANT]
> If you are working in pairs or groups, only **one person** should complete this step.

---

### 2. Add Collaborators (Pairs/Groups Only)

If working with teammates:

1. Open the repository on GitHub
2. Go to **Settings → Collaborators**
3. Add your teammates as collaborators
4. Share the repository link with your team

Teammates should accept the invitation before continuing.

---

### 3. Clone the Repository

Copy the SSH URL from the **Code** button on GitHub, then run:

```bash
git clone <copied-ssh-url>
```

The copied SSH URL will look like `git@github.com:<your-username>/<repo-name>.git`.

---

### 4. Move into the Project Folder and Install Dependencies

This installs all dependencies and creates a virtual environment in `.venv/`.

```bash
cd <repo-name>
uv sync
```

---

### 5. Open the Notebooks

> [!NOTE]
> Make sure you open VS Code from the project root so it automatically detects the environment created by `uv sync`.

Launch VS Code in the project root folder:

```bash
code .
```

Then open a notebook and select the Python environment created by `uv sync` as the kernel.

## References & Further Reading

- [**Scikit-learn: Logistic regression**](https://scikit-learn.org/stable/modules/linear_model.html#logistic-regression): Official documentation for the model and its options.
- [**Google ML Crash Course: Logistic regression**](https://developers.google.com/machine-learning/crash-course/logistic-regression/video-lecture): A concise walkthrough of the model and the sigmoid function.
- [**Kaggle: Titanic - Machine Learning from Disaster**](https://www.kaggle.com/c/titanic): A classic binary classification dataset to practice on.
