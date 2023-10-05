# Project-Webscraping

Create a data product by extracting data from the web.

Webscrapring with Selenium the website scholenopdekaart.nl to find all relevant information 
on primary and secondary schools in the Netherlands.

As first step, we created an initial dataframe with all schools and their basic contact informatio (name, address, postal code, region).

After that we tried to scrape the website looking at the 'search page', but we faced the first difficulties using the standard BeautifulSoup method, as the soup did not match what we saw inspecting!

Then we made progress by involving Selenium scraping tools and we were able to retrieve more information on all schools (webpage in the main website, schools educational approach, number of students)

What we were really interested in was some sort of numerical value to estimate the performance of the students for each schools.

For that purpose, we created 2 functions to scrape target level and fundamental level reached by pupils in primary schools, that worked well. 
We also tried to define other functions that could obtain the satisfaction level of students and parents for the primary schools and extract the percentage of students who passed the final exams and their average grade in the last year recorded (2022) for the middle schools, but these functions stays in our WIP list for now.

We worked on a big amount of data (more than 7000 schools) and we did not always find all information, as not for every schools public results were showing...so a lot of erro handling involved and a huge amount of time for the functions to run!
