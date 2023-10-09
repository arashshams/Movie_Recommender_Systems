# Movie_Recommender_Systems
This repo hosts a script to build a few Recommender Systems for movies using the [Kaggle's MovieLens dataset](https://www.kaggle.com/datasets/prajitdatta/movielens-100k-dataset). The original source of the data is [here](https://grouplens.org/datasets/movielens/), and the structure of the data is described in the [README](http://files.grouplens.org/datasets/movielens/ml-latest-small-README.html) that comes with it.

**Note:** The data set is not included in this repo due to size limitations. Make sure to download the folder (`ml-100k`) from [Kaggle](https://www.kaggle.com/datasets/prajitdatta/movielens-100k-dataset) and put it in `data\ml-100k\` folder in the project root.

### Dependencies

If you want to reproduce the [report](https://github.com/arashshams/Movie_Recommender_Systems/blob/master/Analysis.ipynb) (`Analysis.ipynb`) on your local, simply run below commands in terminal to create the environment for running the notebook.

```
conda env create -f environment.yml
conda activate env
```
