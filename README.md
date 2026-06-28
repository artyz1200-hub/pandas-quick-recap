# pandas-quick-recap

A fast, hands-on **pandas refresher** built around the Titanic dataset , the kind of thing helps you to get the core verbs back in your fingers.

It's two notebooks: one to **read** and one to **solve**.

## Contents

| File | What it is |
|------|------------|
| [`Pandas_quick_recup.ipynb`](Pandas_quick_recup.ipynb) | The crash-review. Run each cell top to bottom, read the comment, understand the output. |
| [`Pandas_exercises.ipynb`](Pandas_exercises.ipynb) | 5 practice tasks (with hidden solutions) to test yourself after the review. |
| `data/train_and_test2.csv` | Titanic dataset used everywhere below. |

## Topics covered

1. Reading data & dtypes (`read_csv`, `astype`, `category`)
2. Inspecting a dataset (`head`, `info`, `describe`, `value_counts`)
3. Selection - `loc` / `iloc` / boolean masks / `query` / `isin`
4. Cleaning - `isnull`, `fillna` strategies, `dropna`, duplicates, IQR outliers
5. `groupby` & aggregation (`agg`, `transform`)
6. `merge` / `join` / `concat`
7. `pivot_table`
8. Transformations - `map`, `apply`, vectorization, `assign`, method chaining, `.str`

## The exercises

`Pandas_exercises.ipynb` ramps up from a warm-up to a full mini-pipeline:

1. **Load & inspect** - shape, dtypes, missing values, survival rate
2. **Filtering** - boolean masks + a conditional survival share
3. **Cleaning & features** - group-wise `fillna`, `pd.cut`, derived columns
4. **groupby & pivot** - survival pivot table + fare-by-port ranking
5. **Check yourself** - a from-scratch end-to-end pipeline

Each task has a *your code* cell and a *Solution* cell. Try it yourself first, then check.

## Getting started

```bash
pip install pandas numpy jupyter
jupyter lab        # or: jupyter notebook
```

Open either notebook and run the cells. Paths assume you launch from this folder
(`data/train_and_test2.csv` is relative).

## Dataset

Titanic — https://www.kaggle.com/datasets/heptapod/titanic
