I'm working my way through Tableau for Dummies, which uses this datset. I wanted to do some Python EDA at the same time--see where Python and Tableau can intersect.

Created this repo from a template with this structure--for now I'm just working out of eda.ipynb

src/app.py → Main Python script where your project will run.
src/explore.ipynb → Notebook for exploration and testing. Once exploration is complete, migrate the clean code to app.py.
src/utils.py → Auxiliary functions, such as database connection.
requirements.txt → List of required Python packages.
models/ → Will contain your SQLAlchemy model classes.
data/ → Stores datasets at different stages:
data/raw/ → Raw data.
data/interim/ → Temporarily transformed data.
data/processed/ → Data ready for analysis.