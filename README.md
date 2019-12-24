# Scraper-for-Job-Hunting
This is a team project with Yuxin Yao, Yaqi Wu and Yuran Zhu.

In this project, we developed an automatic generator for job hunting information report. It allows users to input a job position they are interested in and return a job report in HTML format. 

The main libraries included are pandas, selenium, matplotlib, plotly and wordCloud. 

projectall.py: main script to input the job position and control the whole process

scrapping.py: using selenium and Xpath to scrape essential data features from Glassdoor and Indeed, including salary, location, job title, company, industry, job summary, rating, etc.

dataclean.py: using pandas to clean the raw data

visualizedata.py: doing the visualization such as bar chart, histogram, pie chart, wordcloud and choropleth map.

htmloutput.py: interfacing with plotly's Chart Studio to generate and pop up a HTML report automatically
