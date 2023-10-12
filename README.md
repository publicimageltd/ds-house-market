# ds-house-market

This project documents data extraction, cleaning and exploration using
Python. It is based on a list of King County real estate sales from
for 2014/2015, which is also often used to practice price prediction.
The specific task in this project is to give advice to socially
responsible investor who wants to invest in poorer communites and is
not interested in much profit.

This project has been part of a Data Science course in the Spiced
Academy, Berlin.

There is actually an interesting mistake in the conclusions. So if you are seriously trying to reconstruct the
reasoning, have a look at the meaning of the scores for the conditions of the houses. There are more possibilies
of investment in the dataset for the type of investor envisiones in the task than I had thought of. 

## Setup

The project loads the data from a PostgreSQL server which is not
publicly accessible. To follow the project step by step, one has to
download the [King County
Dataset](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction)
and import them manually. I might write an import script when I find time.

Extract the folder and set up a python virtual environment. Then,
install the modules via `pip`.

Installation instructions for Linux:

```bash
python -m .venv venv
source .venv/bin/activate
pip install -r requirements.txt
```
