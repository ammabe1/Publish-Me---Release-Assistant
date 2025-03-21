# Publish-Me---Release-Assistant
The purpose of this project is to take published books sales data, sorted it by sub-genre to allow self-publish authors to determine the highest probability for successful sales of their novel based on genre and sub-genre sales data. The long term goal would be to design an application or web based dashboard that will allow the author search or filter for the chosen sub-genre/tropes for sales numbers for historical sales data. Furthermore, to cross check with planned release dates of similar books that will be published by traditional publishing houses to prevent lower sales by releasing self-published books at or around the same time of more well known or popular authors.

The two original datasets utilized, Books_Data_Clean.csv & book_details.csv, were inner joined/merged using book title as the primary key, which resulted in 675 rows of data.  Once the data was cleaned, and broken out into fiction or nonfiction, I used a list of fiction and nonfiction genres to sort for sales numbers. I further drilled down the data into tropes or sub-genres based on value counts of all tropes/sub-genres in the dataset with a dictionary to explain the cleaned data. These were sorted based on highest to least in a value count list. The cleaned data was put into a new csv file The results of sales (fiction vs nonfiction) and sales totals by publisher were grapheds via matplotlib. Plotly was used to graph out the tropes of Romance sales on the tier one and tier two tropes. 


# Installation
1. Clone the repository: fork and clone the repository from this link: https://github.com/ammabe1/Publish-Me---Release-Assistant
2. Navigate to the project on your computer file explorer: /Publish-Me---Release-Assistant
3. Open the file in your prefered code editor (I use VisualStudio Code)
4. Open the .ipynb file
5. Open your command line interface. Ensure you are in the file named /Publish-Me---Release-Assistant, if not navigate using command directory (cd) to the correct folder. 
 

# Usage
1. Activate the virtual environment to use the code.

    Use the below commands in your command line (either for Linux/Mac or GitBash/Windows) to create, then activate, then install the requirements. Once you have run the program and are ready to leave the Jupyter notebook, use the deactivate command to end your session. 

    ## Virtual Environment Commands to create a virtual environment
| Command | Linux/Mac | GitBash |
| ------- | --------- | ------- |
| Create | 'python3 -m venv venv' | 'python -m venv venv' |
| Activate | 'Publish-Me---Release-Assistant venv/bin/activate' |'Publish-Me---Release-Assistant venv Scripts activate' |
| Install | 'pip install -r requirements.txt' | 'pip install -r requirements.txt' |
| Deactivate | 'deactivate' | 'deactivate' |
2. The above install should install all needed packages:

    import pandas as pd
    
    import matplotlib.pyplot as plt
    
    from matplotlib import colormaps
    
    import numpy as np
    
    from collections import Counter
    
    import string
    
    import sqlite3
    
    from matplotlib.ticker import 
    FuncFormatter
    
    import seaborn as sn
3. Download the datasets from: 
    
    Books_Data_Clean.csv (https://www.kaggle.com/datasets/thedevastator/books-sales-and-ratings)
    
    book_details.csv (https://www.kaggle.com/datasets/evilspirit05/comprehensive-goodreads-book-dataset?resource=download)
4. You should be able to run the code in the notebook at this juncture.
5. When finished in the notebook, use the deactivate command in your command line to deactivate the virtual environment. 

# Contributing
1. Fork the repository
2. Create a new branch: git checkout -b feature-name
3. Make your changes
4. Commit your changes: git commit -am 'Add new feature'
5. Push to the branch: git push origin feature-name
6. Submit a pull request

# License
1. This project is licensed under the GNU GENERAL PUBLIC LICENSE - see the LICENSE.md file for details.

# Credits
1. Books_Data_Clean.csv (https://www.kaggle.com/datasets/thedevastator/books-sales-and-ratings)
2. book_details.csv (https://www.kaggle.com/datasets/evilspirit05/comprehensive-goodreads-book-dataset?resource=download)
 

# Contact
For questions or support, contact name.


