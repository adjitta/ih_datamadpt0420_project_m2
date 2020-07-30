# Blood Diamonds 

The objective of this project is to do an exploratory analysis on the different characteristics of diamonds in Jupyter Notebook and then create a dashboard in tableau.

![Image](https://images.unsplash.com/photo-1545489379-83f2d972fd20?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60)

### Data sources 
 - Database with the diamonds information.
    - Provided by [Ironhack](http://www.potacho.com/files/ironhack/diamonds_train.csv) formatted as a `.csv` file.
 
 ## **Installation**
Use the package manager conda to install the following libraries:

```bash
conda install nodejs
conda install nodejs
conda instal Seaborn
conda install Matplotlib
```
 ### Requirements
 - Data analysis:
    - Pandas
    - Numpy
- Data visualisation
    - Seaborn
    - Matplotlib
    - Plotly
    -Warnings
    -Cufflinks
###  **Folder structure**
```
└── project
    ├── __trash__
    ├── .gitignore
    ├── .env
    ├── requeriments.txt
    ├── README.md
    ├── main_script.py
    ├── notebooks
    │   ├── notebook1.ipynb
    │   └── notebook2.ipynb
    ├── package1
    │   ├── module1.py
    │   └── module2.py
    └── data
        ├── raw
        ├── processed
        └── results
```
## Conclusions 
1. x,y, and z have a very strong relation with price but surprisingly depth (which comes from x,y, and z) doesn't has a significant relation with price.
2. Carat has a strong relation with price
3. Table doesn't have a significant relation with price or any other variable as well.
4. Average diamond prices are low.The upper quartile is bigger. It shows that whichever category it may be there's a variety of diamonds that are still very expensive.

## Tableau Public Dashboard
- A Tableau Public dashboard has also been created, which can be accessed through this [link](https://public.tableau.com/profile/adja1203#!/vizhome/Project_Module_2/Average?publish=yes)
