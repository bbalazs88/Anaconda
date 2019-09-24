## Other python project
These are the notebooks which aren't connected to Machine Learning. My other favourite field is web scraping, a few notebooks are about this topic. I also like to experiment with Python and Databases, it's because my previous work experiences - I always worked with databases before.

## The Beatles' last concert word frequency
It's a tiny project, I made because of the "Word Frequency of Moby Dick" DataCamp project. Get the text from the webpage, tokenize it with NLTK, and exclude the stopwords from it. Stopwords are the most common words, like "the, a, an, and", which used to be deleted from the original text, to make it clearer. A basic visualisation of the frequency distribution at the end.

## Burberry scraper
One of my favourite projects. The story behind this, that from a Facebook ad, I saw that Burberry introduced their make-up line in Hungary. And because it's my favourite fashion brand, I wanted to check, how much is a lipstick, to buy one for my girlfriend. I went to the page, and realized, that there's a misspelling in the price. The 11.000 Huf (33 eur) price is shorter with a zero, it's just 1.100 Huf (3.3 eur). Needless to say, we ordered twenty-something from it, and I thougt that I could check the whole Burberry page for errors like this.
BeautifulSoup is always handy, but it wasn't enough for me just to scrape through the pages. I made a free Azure SQL Service to practice, and inserted all the rows to it, so it's easily searchable.

## Eploring 67 years of LEGO
It's a DataCamp project aims for Pandas using. Select / group by / sort etc.

## John Snow's ghost map
Another DataCamp project about John Snow, who was the first "Data Scientist". The project aims for pandas practicing, create new columns, rename them, and make list from columns. Folium and Bokeh is the two visualisation librarier which were new to me.

## Python basics
It was made as a very-very-very quick tutorial for the budapest.py workshops (github.com/budapestpy-workshops) to those who hasn't used Python before.

## SQLite and Python
It was the topic of one of the former Data Revolution (now budapest.py) workshops. This was the first time, I tried to connect a database with Python. I choose SQLite, because I wasn't needed a robust database - and I've never worked with it before. The idea came from a pydata meetup, where someone presented a Python project with the BKK vehicles routes. I simplified it, and got all the stops from BKK's page (it's called GTFS). For practicing reasons, I made a table in the SQLite database from Python, where I inserted the previously readed csv-s values. Then the table was brought back to pandas, and visualise with Folium. The problem was that there are ~5000 stops, which kills the computer when it tries to draw every piece of it one by one. After a long session of solution finding, I found the markercluster, and the project was ready.
