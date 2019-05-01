# DATS6103 - Data Mining: Individual Project 3
# Data Mining Little Free Library Locations

Evan Carraway

Nima Zahadat, Ph.D.

The George Washington University

May 1, 2019

Objective: The purpose of this project is to continue learning and improving skills in data mining and extracting information from raw data using Python by analyzing locations of free libraries along with other demographic data.

Due Date: May 4, 2019 by 4:30 PM

## Tasks
1. Scrape library locations from online map
2. Aggregate and map libraries by city
3. Correlate library density to other city demographics 

## Subtasks
1. Create an effective presentation describing your data set of choice
2. Present the topic and the rationale on why you are picking that topic
3. Topic and its data MUST be complex and not at all obvious
4. The topic will be checked for plagiarism
5. State where the data came from
6. State your data cleaning and preprocessing
7. Your code needs to be working and be well commented
8. Your analysis needs to be clear, organized, and in depth
9. Indicate any classifications, clusters, associations/correlations, etc.
10. Discuss your predictions you might have and your reasoning behind them
11. Describe your learning processes
12. Present an overall conclusion

## Abstract

May 2019 will mark the 10 year anniversary of Little Free Library, a non-profit, community-driven program to spread literacy and learning through free book exchanges. As of this year, there are over 80,000 such libraries in over 90 countries (LFL, 2019). Previous research has shown links to book access from sources like LFLs can lead to higher literacy rates (Rebori, 2017). Knowing more about the locations of these libraries and the communities that build them can give us an understanding of the effectiveness of this movement, as well as other insights. Using littlefreelibrary.org's database of over 30,000 registered LFLs which contains zip, state, country and coordinates, and combining this with other demographic data, we will seek to learn and expose new insights about LFLs and their popularity.

## Assumptions and Questions

We would expect to see more libraries in higher population areas, but it is unclear if more little free libraries in an area would have a correlation with academic success. We would predict cities such as Ann Arbor, MI, Washington, DC and Madison, WI might have a higher density of libraries since they are frequently ranked as the most educated cities in the U.S. (Sonnenberg, 2017). Washington, Seattle and Minneapolis would also be contenders for having more libraries given they are frequently rated as the most literate cities (McClurg, 2017). Studies of certain cities have shown that LFL are in built more in high affluence, low poverty areas, but at the same time there are differences city to city in who builds the libraries, whether they be individuals, governmental organization or NGOs (Sarmiento, 2017). 

## Tools Used

For this exercise, we used Python 3 in Jupyter for interactive computing, with the Pandas data manipulation and analysis libraries, as well as the Plotly statistical data visualization library to generate interactive charts and figures. For data retrieval and parsing we will use requests and json. For storage and retrieval of data sets we will use SQLite. Lastly, we will use Folium to create an interactive map of cities and LFLs.

## Little Free Library Website

The primary dataset we will be using for this project is the Little Free Library website. Locations of little free libraries can be found at https://littlefreelibrary.org/
