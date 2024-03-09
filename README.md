# html_challenge

In this challenge, automated browsing with Splinter was used to visit the Mars news site provided, and a Beautiful Soup object was created for web scraping. The page was then inspected to identify elements for extraction. Using Beautiful Soup, titles and preview text of news articles were successfully extracted and stored as Python data. The resulting list was printed in the notebook.
In the second part of the assignment, the Mars Temperature Data Site was used with Beautiful Soup to scrape data from the HTML table. The scraped data was organized into a Pandas DataFrame. A tutor helped me as I was getting a value error. We ended up using a nested for loop rather than the for loop I orginally had to skip the header line. We used a range for the seven lines of each set in the loop based on the data scraped from the website. I converted data types, determined the number of months on Mars, calculated a Martian days' worth of data, and identified the coldest and warmest months on Mars based on average minimum daily temperatures. This was put in a bar chart and sorted by values to get greatest to least average minimum daily temperatures. The third month was the coldest and the eighth month was the warmest.

![image](https://github.com/kelseajade/html_challenge/assets/152021966/2b1440a2-5f70-44b6-8d67-d6a359e4d27f)

The months with the lowest and highest atmospheric pressure on Mars were identified through average daily atmospheric pressure calculations.The lowest was the sixth month and the highest being the ninth month. 

![image](https://github.com/kelseajade/html_challenge/assets/152021966/f5dedd84-f167-40cd-8e9d-27839a2ef5a9)

An estimation of the number of terrestrial days in a Martian year was made by plotting daily minimum temperatures. The explanation being that there are 675 days in a year on Mars from peak to peak however the Mars year us actually 687.

![image](https://github.com/kelseajade/html_challenge/assets/152021966/0ab2c961-7676-430a-9872-a3c59712c0bf)

The DataFrame was exported as a CSV file.
