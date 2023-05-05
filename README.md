Citi-Bike-Challenge-18

 	My challenge assignment focused on the summer months, July - September for years 2019 & 2020, and also data for 2021 & 2022.  I focused on the Citi Bike stations for New York City and New Jersey from the website provided for the assignment.  My findings were general in nature about the increase in the number of bike stations from Pre-Covid to Post Covid.

Methods Used
Python code, Tableau worksheets, dashboards and stories options. 


Technologies
Jupyter Notebook, Tableau Workbook and Tableau Public.


Data Source
https://citibikenyc.com/system-data - csv files downloaded.


Installation
I had to install "glob" at the terminal which was a method I found in Stack Overflow I believe, by Googling how to concatinate many csv files at once. 

pip install glob2 (I believe)
Also added the following to Jupyter Notebook to use glob: 
"from glob import glob"

Analysis:
Here's a map of New Jersey and New York City area where Citi Bike routes are located. It's just for general purposes. It was not used in dashboards.

[nyc-bike-map-2022.pdf](https://github.com/KatKess/Citi-Bike-Challenge-18/files/11403049/nyc-bike-map-2022.pdf)

    In general, Citi Bike stations are all over the area. A lot of them are situated on the New Jersey side, although many are in New York area as well.  I decided to only look at summer months of July - September 2019 & 2020 and 2021 & 2022 respectively. I wanted to see how many stations there are and what the most  popular routes and trip distances. The 2019 and 2020 .csv files downloaded from the website were in the same format.  The 2021 and 2022 July – September  data are in a similar but still different format from the 2019 & 2020 data set.  I could not easily combine all 4 years together, so I made 2 concatinated files   to work with instead. Results from both data sets are noticeably different, however I tried to highlight the interesting facts I could gather and make into presentable  dashboards on Tableau Public. My goal in pulling this data together would be to show the audience (City officials) how the Citi Bike stations have changed over the four year span  and to see if any generalizations can be made taking into account pre and post COVID pandemic.
