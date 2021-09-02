# Python-Automation

Using Selenium library in Python to webscrape data

We will webscrape data from Norwegian govt publicly shared data on their webiste *https://dbh.nsd.uib.no/statistikk/*

1) There are four levels: Institionstype, Institution name, Faculty name, Department name

2) Every institution has many types. Similarly, within each type there are many institution names, many faculty, many department. Within eacg department there are many courses.

3) We will loop over every level and collect all the course data. 

