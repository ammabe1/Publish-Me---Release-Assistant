# Publish-Me---Release-Assistant
The purpose of this project is to take published books sales data, sorted it by sub-genre to allow self-publish authors to determine the highest probability for successful sales of their novel based on genre and sub-genre sales data. The long term goal would be to design an application or web based dashboard that will allow the author search or filter for the chosen sub-genre/tropes for sales numbers for historical sales data. Furthermore, to cross check with planned release dates of similar books that will be published by traditional publishing houses to prevent lower sales by releasing self-published books at or around the same time of more well known or popular authors.

The two original datasets utilized, Books_Data_Clean.csv & book_details.csv, were inner joined/merged using book title as the primary key, which resulted in 675 rows of data. Each row contained a list of ten genres/sub-genres/tropes attributed to each book. This column was seperated to allow for prioritizing and sorting of the stings in this column. Once the data was cleaned, it was broken out into fiction or nonfiction in a new column. I used a list of fiction and nonfiction genres to sort for sales numbers. I further drilled down the data into tropes or sub-genres based on value counts of all tropes/sub-genres in the dataset with a dictionary to explain the cleaned data in the analysis markdown. These were sorted based on highest to least in a value count list. The cleaned data was put into a new csv file which can be explained in a data dictionary in the analysis markdown. The results of sales (fiction vs nonfiction), sales totals by publisher, and sales of fiction and nonfiction broken out by genre were grapheds via matplotlib. I have also created a Tableau Dashboard to further display my data to allow for additional callouts within the visualizations.   

## Features
| Feature | Description |
|-------|-----------|
| Read Three data files | Read in two csv files from Kaggle and created one of cleaned data|
| Created several matplotlib plots and Tableau dashboard | Various graphs to map my findings and a Tableau dashboard for interactive data findings |
| Utillized a virtual environment | Created a venv for faster usage/running of the notebook |
| Cleaning and merging | I completed column breaking down of strings for easier analyzing and plotting, thorough cleaning of the data |
| Functions | Created several functions to prioritize the string genre data once broken out and cleaned |
| Data Dictionary | Built a custom data dictionary for the created csv from the cleaned data |
| Analysis | Analysis for book sales broken out by fiction and nonfiction then drilled down by genre and top selling tropes within those genres | 

# Installation
1. Clone the repository: fork and clone the repository from this link: https://github.com/ammabe1/Publish-Me---Release-Assistant
2. Navigate to the project on your computer file explorer: /Publish-Me---Release-Assistant
3. Open the file in your prefered code editor (I use VisualStudio Code)
4. Open the Publish-Me---Release-Assistant.ipynb file
5. Open your command line interface. Ensure you are in the file named /Publish-Me---Release-Assistant, if not navigate using command directory (cd) to the correct folder. 
6. Follow the usage directions below to create and activate a virtual environment.
 

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
2. The above install should install all needed packages from the requirements.txt file.
3. Download the datasets from: 
    
    Books_Data_Clean.csv (https://www.kaggle.com/datasets/thedevastator/books-sales-and-ratings)
    
    book_details.csv (https://www.kaggle.com/datasets/evilspirit05/comprehensive-goodreads-book-dataset?resource=download)
4. You should be able to run the code in the notebook at this juncture.
5. When finished in the notebook, use the deactivate command in your command line to deactivate the virtual environment. 
6. You can access the Tableau Dashboard for this project by clicking the following link: https://public.tableau.com/views/PublishMe-ReleaseAssistant2023BookSalesbyGenreTrope/BookSales2023?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link 

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
3. Fiction and Nonfiction genre list from https://nextnewbooks.com/book-genres-explained-complete-list/
 

# Contact
For questions or support, contact Amy Mabe.


