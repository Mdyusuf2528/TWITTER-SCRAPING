# WEB-SCRAPING

This code is for scraping data from Twitter using Python's snscrape and Streamlit libraries. The code takes inputs from the user such as the keyword, start date, end date, and the number of tweets to scrape. The scraped tweets are then stored in a MongoDB database, and the user can also download the scraped data in CSV and JSON formats.

The code first sets up the Streamlit page by adding a background image, a Lottie bird animation, and the page title. Then, it takes inputs from the user and displays them using Streamlit widgets. After that, it defines the scraping function, which takes the user's inputs and scrapes tweets based on those inputs using snscrape. The scraped tweets are then converted into a pandas DataFrame.

Next, the code defines a function to store the scraped data in a MongoDB database. The function uses the pymongo library to connect to the database and inserts the data into the Tweets collection. Finally, the code creates three buttons to upload the data to MongoDB, download the data in CSV format, and download the data in JSON format. When the user clicks on one of these buttons, the corresponding function is called, and the data is either uploaded to MongoDB or downloaded in the selected format.
