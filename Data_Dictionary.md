### Data Dictionary of Full_Book_Details_mod2.csv

| Field | Source | Data Type | Description | Example|
|-------|-----------|-------------|--------|--------|
|Book_Name|Renamed from original sources to match as primary key|object|Title of the Book|The Little House Collection|
|Publishing_Year|Renamed from original Book_Data_Clean|float64|Year the book was published|1953|
|Author|Renamed from original sources|object|The name of the author|Laura Ingalls Wilder, Garth Williams|
|gross_sales|Renamed from original source Book_Data_Clean|float64|This is the total sales for the book for 2023|5195.91|
|publisher_revenue|Renamed from original source Book_Data_Clean|float64|This is the publisher revenue attributed to the book sales|3117.546|
|Publisher|Renamed from original source Book_Data_Clean|object|This is the name of the company that published the book|Random House LLC|
|units_sold|Renamed from original source Book_Data_Clean|int64|This tells the number of books sold for 2023|453|
|Master_Genre|New column built from genres column from original source book_details|object|This indicates whether the book is a fiction or nonfiction book|Fiction|
|Master_Sub_Genre|New column built from genres column from original source book_details|object|This indicates what type of fiction or nonfiction book, i.e. Romance, Biography, etc.|Childrens|
Trope_1|New column built from genres column from original source book_details|object|This is the trope/sub-genre with the highest number of sales that is attributed to the book|Young Adult|
|Trope_2|New column built from genres column from original source book_details|object|This is the trope/sub-genre with the second highest number of sales that is attributed to the book|Classics|
|Trope_3|New column built from genres column from original source book_details|objest|This is the trope/sub-genre with the third highest number of sales that is attributed to the book|Historical Fiction|
|Trope_4|New column built from genres column from original source book_details|object|This is the trope/sub-genre with the fourth highest number of sales that is attributed to the book|Historical|
|Trope_5|New column built from genres column from original source book_details|object|This is the trope/sub-genre with the fifth highest number of sales that is attributed to the book|Middle Grade|
|Trope_6|New column built from genres column from original source book_details|object|This is the trope/sub-genre with the sixth highest number of sales that is attributed to the book|Juvenile|
|Trope_7|New column built from genres column from original source book_details|object|This is the trope/sub-genre with the seventh highest number of sales that is attributed to the book|Literature|
|Trope_8|New column built from genres column from original source book_details|object|This is the eighth highest sales trope/sub-genre, or format (audiobook) that is attributed to the book|Kids|