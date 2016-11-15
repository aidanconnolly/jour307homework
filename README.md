# JOUR 307 Homework
*Spring 2016 — Matt Waite, instructor*

This repository holds different assignments for JOUR 307: Data Journalism. 

From the syllabus:
> Every day, more of our lives is being stored in a database somewhere. With that explosion of data, journalists now more than ever need the skills to analyze and understand data to then produce the stories hidden in the information. In this class, we’ll use brainpower and software to look at raw data -- not summarized and already reported information -- to do investigative reporting. We’re going to get our hands dirty with spreadsheets, databases, maps and some basic stats. And we're going to do journalism. So buckle up and hold on.

Below are some assignments including the instructions and my work.

* [Percent change](#percentchange)
* [Grouping data](#groupby)
* [First chart](#firstchart)
* [Data joining](#join)
* [Data normalization](#normalization)
* [Mapping assignment](#mapping)
* [Second mapping assignment](#secondmapping)
* [Data request](#datarequest)
* [Health inspections investigation](#inspections)
* [Downtown apartments investigation](#apartments)
* [Data cleaning](#cleaning)

<a name="percentchange"></a>
## [Percent change](PercentChange)

The assignment:
>1. Download this dataset of population estimates from the US Census Bureau.
1. Calculate the percent change in population for every county in the US from 2010 to 2014.
1. Round that change off to a single decimal point.
1. Sort it fastest growing to fastest shrinking. Print it to the screen but limit it to 50.

[Jupyter Notebook](PercentChange/PercentChange.ipynb)

<a name="groupby"></a>
## [Grouping data](GroupByAssignment)

The assignment:
>We've calculated the median and mean salary for all UNL employees, but that doesn't tell the whole story. The mean includes football and basketball coaches. The medians don't showthe differences between jobs at the university. So using what you've learned in this walkthrough, group the salaries by job title.   

>Aggregate a count, a median and an average for each job title. Hint: You can do this all in one aggregate table. One gotcha on that multiple aggregates in a single table thing: Watch out for commas. You need one at the end of every line EXCEPT the last aggregate.  >Sort the table by the count, putting the most common job title at the top.  >Print the table out. Limit it to the 50 most common jobs.

[Jupyter Notebook](GroupByAssignment/GroupByHomework.ipynb)

<a name="firstchart"></a>
## [First chart](ChartAssignment)
The assignment:
>Using the Mountain Lion data from earlier this semester, make a bar chart of the top 10 counties for sightings. Create three different versions, with three different set_styles and three different colors. In your Jupyter Notebook, tell me which one you like the most and why. And what is the main weakness of your chart?

[Jupyter Notebook](ChartAssignment/ChartAssignment.ipynb) 

<a name="join"></a>
## [Data joining](DataJoining)
The assignment:
>Often, in data, we have one set of information stored in a table over here, and another set of information stored in a table over here. At the university, your student records are scattered in tables all over. Somewhere, there is a master student record, that has your name, birthdate, ID number, home address and other basic info. Then, over in the registrars office, we have the classes you took and the grades you received. Over here, we have the bursars office, which shows how much you owe in tuition and how much you've paid. If we wanted to get a single table together that showed how much you paid for each grade you got, we'd have to JOIN them together somehow.  
>
>There are three data files in the Data folder in the class repository: frl13, frl14, and frl15. They are the Free and Reduced Lunch participation totals for every school in Nebraska. I want you to join them together into a single table and calculate the percent change from 2013 to 2015 and sort them by the largest. Which school in Nebraska saw the largest increase in participation in free and reduced school lunches, which is a proxy for poverty.

[Jupyter Notebook](DataJoining/JoinAssignment.ipynb)


<a name="normalization"></a>
## [Data normalization](DataNormalization) 

The assignment:
>In this assignment, you must take a file from the Nebraska Department of Environmental Quality and make it useful. I want to know how many leaking underground storage tanks there are in each city in Nebraska.  
>  
>To do this, you will need to:  
>
>1. Get the file from the DEQ. The file you want is called spillfac.csv, but keep this page handy because it has some filter conditions you're going to need.
2. The file that comes from the state is not UTF-8. Follow the walkthrough. Use Excel and csvkit to zap the non-UTF-8 characters.
3. Normalize the data using Open Refine. Specifically, the fields you need to normalize are the owner company -- OWNCO -- and the city the tank is in -- SPCITY.
4. Export your newly cleaned data into a new csv file.
5. Import your newly cleaned up data into Agate.
6. Filter out any leaking underground storage tanks that aren't leaking. (see the documentation from where you downloaded the file)
7. Group it by the OWNCO and count them.
8. Sort it.
8. Print the top 20 to the screen.

[Jupyter Notebook](DataNormalization/DataNormalization.ipynb)

<a name="mapping"></a>
## [Mapping assignment](MappingAssignment)

The assignment:
>Create a map of population change in Nebraska using this data. Thematically shade it in a manner you think is appropriate. Write a paragraph discussing what the map shows, as if this paragraph were going to be published in a story about population change in Nebraska after a Census data release.



<a name="secondmapping"></a>
## [Second mapping assignment](SecondMappingAssignment)

The assignment:
>An editor has just approached you about a story idea they have. They heard this podcast of this Washington Post reporter who wrote a story about The Worst Place In America To Live, which is in Minnesota. In the podcast, and in the story, the ranking was based on the USDA's Natural Amenities Index. The map that the Washington Post published also made Nebraska out to be a pretty rough place to live.
>
>Your editor wants to know:
>
> 1. What are the 50 worst places in America to live based on natural beauty?
> 1. How many of Top 50 Worst places are in Nebraska?
> 1. Where are they?
> 1. And can we have a map like the Washington Post map?

<a name="datarequest"></a>
## [Data request](DataRequest) 

The assignment:
> During the semester, you will identify a database held by a government agency that you need for a story and go get it. You are negotiating for public data as a journalist, you may not promise to not use the records. Downloading data from the Internet does not fulfill the requirements of this exercise.

[Final thoughts](DataRequest/finalthoughts.md)

<a name="inspections"></a>
## [Health inspections investigation](HealthInspectionsArticle)

[The final article](HealthInspectionsArticle/FinalArticle.md)

<a name="apartments"></a>
## [Downtown apartments investigation](DowntownAptsArticle)

As the University of Nebraska-Lincoln continues efforts to grow enrollment to 30,000 students, private housing companies are preparing for the surge by developing housing complexes near campus.

[The final article](http://www.dailynebraskan.com/news/off-campus-downtown-housing-becoming-more-viable-alternative-to-on/article_92239198-0051-11e6-a04c-17f7db0e7407.html)

<a name="cleaning"></a>
## [Data cleaning](OpenDataUNL)

The assignment:
>Take a PDF from the Office of Institutional Research, Analytics and Decision Support and turn it into a usable dataset.

[Github repository of converted documents](https://github.com/OpenDataUNL/enrollment-data)



