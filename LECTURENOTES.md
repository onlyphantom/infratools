# Starting Out
- Python and R
- Why, Python?
    - Pandas
    - Numpy
    - Scipy
    - Scikit Learn
    - Matplotlib
- Challenges of Notebook
    - Hidden state
    - Environments
    - Making it _extremely_ hard to be reproduced
- Work you do:
    - Descriptive / Prescriptive?
    - Service-based or Product-based

# Productionizing
- Start from a Notebook
    - Prototyping
    - JupyterLab

- Reading in the data
    - Python: `pd.read_sql_query("SELECT * FROM sales", conn)`
    - Python: `pd.read_csv("sales_2017.csv")`
    - R: `read.csv(sales_2017.csv)`

- Explore the data
    - R: `dim()`, `head()`, `tail()`, `nrow()`
    - Python: `shape()`, `.head()`

- Transforming your data
    - `.melt()` or `.reshape()`
    - One-hot encoding
    - Objective: reshape so you can use them for ML or for DV

- Visualize 
    - `import altair as alt`
    - `alt.Chart(sales)`, add `point`, `bar`, `line`, add `encode()`
    - add interactivity if used on a web medium

- Productionize
    - Copy your import statements
    - Copy your preprocessing code (modular)
    - Visualize and expose an endpoint
        - Conventionally, json
    - Test
    - Other ways to package up your code and make it available for the general public
        - R package
        - R Shiny
        - R Plumber 

Resources
- Installing Jupyter
    - Make sure you learn about setting up your environments first!
- https://github.com/onlyphantom/revconnexion
- https://github.com/onlyphantom/pedagogy
- https://github.com/onlyphantom/verisr2
- https://github.com/onlyphantom/textcomplete
    - Demo: https://samuelc.shinyapps.io/textcomplete/
    - Demo: https://samuelc.shinyapps.io/quadrant
- https://github.com/onlyphantom/darkershiny
- http://pedagogyapp.com
- https://github.com/facebookresearch/fastText
- Free book (Elements of Statistical Learning):
    https://web.stanford.edu/~hastie/Papers/ESLII.pdf
- Conda environments
    https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html
