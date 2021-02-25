# Tableau-Projects
This repository contains the analysis and visualizations I have created in Tableau.

### Logistics Performance index
#### About
The Logistics Performance Index (LPI) is an interactive benchmarking tool created by the World Bank to help countries identify the challenges and opportunities they face in their performance on trade logistics and what they can do to improve their performance.It is the weighted average of the country scores on six key dimensions: customs performance, infrastructure quality, ease of arranging shipments, logistics services quality, consignments tracking and tracing and timeliness of shipments. 

The Logistics Performance Index is reported by the World Bank in every two years. The LPI is based on a worldwide survey of stakeholders on the ground providing feedback on the logistics "friendliness" of the countries in which they operate and those with which they trade. They combine in-depth knowledge of the countries in which they operate with informed qualitative assessments of other countries where they trade and have experience of global logistics environment. In this data analysis project, I have explored the LPI dataset and used Tableau to create my own visualizations version.

#### Dataset
The Prosper loan data set contains 160 countries with 6 idicators and scores on each coutrries, including customs, infrastructure, international shipment, logistics quality, timeliness,tracking and tracing, and overall.

https://lpi.worldbank.org/sites/default/files/International_LPI_from_2007_to_2018.xlsx

#### Summary
In peer-to-peer lending, there are three main stakeholders: borrowers, lenders and the company itself. In my Tableau story I have done exploration on the relationship between these people, what affects borrowers Prosper Score and who defaults the most. First, I have done a time series analysis ranging from year 2007 – 2014 about the number of loans taken by borrowers, the amount of their loans and how their ProsperScore got affected in this duration. I noticed that since 2009, the loan business increased and climbed up quickly since 2013 and then dropped down at beginning of 2014 while the borrower credit scores constantly dropping over this time and some states having default rates more than 30%.
Then I have explored the defaulters, reason for defaults, and reason for borrowers to take loan, I found out that the people with $0 income have highest default rates and most defaulters invest in the loan type ‘D’. Breaking down to occupation-wise, an interesting pattern was found that the college student group which are enrolled in higher grade studies have more loans, higher borrower and default rates. While this made sense with $0 income, the sophomore students were the top defaulters and having lower number of loans. Lastly, I have looked at the incomes and losses on different loan ratings – the ‘HR’ loan rating had the highest loss even though this type of loan is given to most credit-worthy borrowers. However, looking at the net principal returns over the time I noticed loans C&D had highest losses than other loans and are most risky.

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
