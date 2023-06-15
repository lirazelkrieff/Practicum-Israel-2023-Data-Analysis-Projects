# SQL Project

The global outbreak of the coronavirus has had a profound effect on people's daily routines. With restrictions on outdoor activities and more time spent at home, individuals have turned to books as a source of entertainment and solace. This shift in behavior has sparked the interest of startups aiming to meet the growing demand for digital book services. In this context, a database containing information on books, publishers, authors, and customer ratings and reviews becomes a valuable resource for understanding this emerging market.

The primary objective of this study is to leverage the provided database to gain insights into the impact of the coronavirus on the book industry. By analyzing customer ratings, reviews, and other relevant data, the study aims to:

- Identify trends and patterns: Explore changes in reading preferences, popular genres, and emerging authors during the pandemic period.

- Understand customer behavior: Analyze how readers' habits and preferences have evolved due to the pandemic, including shifts in reading frequency, book formats, and preferred genres.

- Assess the competition: Evaluate the performance of competing book services and identify their strengths and weaknesses.

- Generate a value proposition: Utilize the database insights to develop a compelling value proposition for a new product or service that caters to the evolving needs of book enthusiasts during the pandemic.


Description of the data

The books table contains data on books:

- book_id (PK)
- author_id
- title
- num_pages — number of pages
- publication_date
- publisher_id

The authors table contains data on authors:

- author_id (PK)
- author

The publishers table contains data on publishers:

- publisher_id (PK)
- publisher

The ratings table contains data on user ratings:

- rating_id (PK)
- book_id
- username — the name of the user who rated the book
- rating

The reviews table contains data on customer reviews:

- review_id (PK)
- book_id
- username — the name of the user who reviewed the book
- text — the text of the review
