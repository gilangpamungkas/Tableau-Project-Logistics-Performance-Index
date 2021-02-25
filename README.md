# Tableau-Projects
This repository contains the analysis and visualizations I have created in Tableau.

### Logistics Performance index
#### About
The Logistics Performance Index (LPI) is an interactive benchmarking tool created by the World Bank to help countries identify the challenges and opportunities they face in their performance on trade logistics and what they can do to improve their performance.It is the weighted average of the country scores on six key dimensions: customs performance, infrastructure quality, ease of arranging shipments, logistics services quality, consignments tracking and tracing and timeliness of shipments. 

The Logistics Performance Index is reported by the World Bank in every two years. The LPI is based on a worldwide survey of stakeholders on the ground providing feedback on the logistics "friendliness" of the countries in which they operate and those with which they trade. They combine in-depth knowledge of the countries in which they operate with informed qualitative assessments of other countries where they trade and have experience of global logistics environment. In this data analysis project, I have explored the LPI dataset and used Tableau to create my own visualizations version.

#### Dataset
The LPI data set contains 160 countries, 5 periods, with 6 idicators and scores on each coutrries, including customs, infrastructure, international shipment, logistics quality, timeliness,tracking and tracing, and overall.

https://lpi.worldbank.org/sites/default/files/International_LPI_from_2007_to_2018.xlsx

#### Summary
On the official website of the logistics performance index, World Bank visualization is still static with a combination of tables that are not engaging and dynamic. We can not see comparisons from year to year clearly, or compare between countries, compare countries in one region, or compare individual indicators.

Then I then tried to design this data by combining it by combining the data for each period, applying the openstreetmap mapbox using the latitude, longitude of each country, designing color levels, and making filters that make it easier for users. 

- You can view final version of my [Prosper Loan Data Story](https://public.tableau.com/profile/jubin.soni#!/vizhome/ProsperLoanData_7/ProsperLoanStory-Version2) by clicking on image below:

[![visualization image](https://github.com/jubins/Tableau-Projects/blob/master/ProsperLoanData/data/pld_screenshot.png)](https://public.tableau.com/profile/jubin.soni#!/vizhome/ProsperLoanData_7/ProsperLoanStory-Version2)

- Version 1 of my Tableau story can be viewed by clicking on below image:

[![visualization image](https://github.com/jubins/Tableau-Projects/blob/master/ProsperLoanData/data/pld_screenshot_v1.png)](https://public.tableau.com/profile/jubin.soni#!/vizhome/ProsperLoanData_Version1/ProsperLoanStory-Version1)


## References
- [Prosper About.](https://www.prosper.com/plp/about/contact-us/)
- [Prosper Loan Data Project on Kaggle.](https://www.kaggle.com/jschnessl/prosperloans)
- [Repo on the same project.](https://github.com/grace-pehl/ProsperLoan) 
- [MIT page showing stats usage on same project.](http://courses.media.mit.edu/2008fall/mas622j/Projects/CharlieCocoErnestoMatt/data/)
- [Udacity Tableau Course.](https://www.udacity.com/course/data-visualization-in-tableau--ud1006)
- [Tableau Tutorials.](https://www.tableau.com/learn/training)
- A lot of googling to figure out how to do stuff.
