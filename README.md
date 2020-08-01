# Web-Scrapping
A site for e books- GoodBooks is being scrapped for the first 50 pages using Beautiful Soap and python.
Beautiful Soap is the python library used for scrapping the ebook site. The scrapped details are author's name, book title, avg ratings, no. of ratings yer of 
publishing. The details are converted into a csv file. Here, data science section is being scrapped. The URL shows that the page no. only changes when we fivit to different pages, so using that and parser library:html-parser, we create a HTML parse tree, from where the data can be scrapped easily. Regular expressions are 
used as they are powerful tools for selection of particular patterns in repeated texts. The https://regex101.com website is pretty cool for trying out the expressions and check their understanding. For acquiring the class names of the portions we want to scrap, we need to inspect the page using- shift+ctrl+i command, it shows the entire html structure of the page. 
To run this code on command line- python web_scrapp.py
