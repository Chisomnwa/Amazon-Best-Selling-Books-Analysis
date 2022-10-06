# Amazon Best Selling Books - A Decade of Analysis

I web-scrapped Amazing Best Selling Books in this project from 2009 to 2019.

In this project, I will be presenting insights derived from the decade of analysis performed on the Amazon best-selling books data.

Each year contains a list of 100 best-selling books. The whole data contains 1090 rows and 8 columns in total.

# Categorization of the Books

For the successful analysis of the best-selling books on Amazon, I needed to analyze the books based on types or categories. 

And it happened that Amazon does not have a definite categorization of books on their website as one book can be found in different departments which is a way they used to group their books. In other to overcome this, I used the information from [Goodreads](https://www.goodreads.com/), the world's largest site for readers, and book recommendations to group the books into two distinct categories which are **Fiction** and **Non-Fiction.**

The new column that contains this categorization is called genre and at the end, the dataset had 9 columns in total.

# Metadata Description

The scrapped data contains the following columns:

 - price: the price of each book

 - rank: the ranking of each book in the top 100 best-selling for each year

 - title: the title of the book

 - no_of_review: this is the total reviews a book has

 - rating: this is the user rating that a book has

 - author: this is the name of the author of a book

 - cover_type: this is the cover type of each book

 - year: this is the year each book appeared as a best-selling book

 - genre: this is the category or type of book (Fiction or Non-Fiction)


# Summary of Findings

 - Between 2009 and 2019, Amazon had more Non-Fiction books on the best sellers list than Fiction books. There was a total of  (345) 54.16% Non-Fiction books and (292) 45.58% Fiction books.

 - 2019 had the highest number of best-selling books which were Non-Fiction while 2009 had more Fiction books that were best sellers.

 - The majority of the best-selling books (459) had a hardcover type, followed by the books which had paperbacks (445).

 - There is no relationship between price and reviews.

 - Between 2009 and 2019, Fiction books had more reviews than Non-Fiction books

 - The average price of books started decreasing in 2014, increased in 2018, and then reduced again in 2019. 

 - The top 20 authors with higher user ratings had more than 4.5 stars in User Ratings.

 - Delia Owens had the maximum number of reviews which was about 340,000 reviews and was very much higher than other authors' reviews. This made him the top best-selling author on Amazon as regards reviews.

 - The top 5 authors with the highest priced books are American Psychiatric Association, Hall H Pearson Education, George R.R Martin, and Jay-Z.
American Psychiatric Association is an outlier having a maximum average price of 144 dollars.

 - Based on Genre and number of book appearances:

    - the top five best-selling authors in Fiction were Rick Riordan, Suzanne Collins, Jeff Kinney, Dr.Seuss, and Stephen Meyer.
  
    - the top five best-selling authors in Non-Fiction were Gallup, Malcolm Gladwell, American Psychological Association, The College Board, and Gary Chapman.

 - Fiction writers like Rick Riordan, Suzanne Collins, Jeff Kinney, and John Grisham were the best-selling or sought-after authors.

 - The top 10 books based on user ratings had more than 4.5 stars in their user ratings.
 
 - The top best-selling books based on user ratings had When the Crawdads Sing, The Silent Patient, Becoming, and The Nightingale: A Novel as the top 4 books.

    Meanwhile When The Crawdads Sing is the top outlier with the highest average number of reviews of about 344811 reviews.

 - The overall top best-selling books based on appearance were self-development books.
