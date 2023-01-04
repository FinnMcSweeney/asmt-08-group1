# asmt-08-group1
Pandas Group Assessment: Extract, Transform, Load and Visualizations for Census Annual Business Survey

Contributors: 
Carol Lopez, James McSweeney, Zeeshan Pervaiz, Rachel Walter

Summary:
Our task for this project was to review 2019 US Census data, access it through the ABS API, and draw conclusions based on our analysis. We used the ABS API to gain a better understanding of the technology adoption and use patterns among small businesses in the US and to identify any trends or disparities in business practices across different industries.

Analysis Questions: Our analysis of the data revolved around exploring the following questions:
- What is the average salary of employees by state?
- What percentage of workers are male and what percentage are female? How does that compare to the number of male versus female owners?
- What technologies are mostly used by employer firms?
- What is the salary range for jobs that require varying levels of use of software-based technology?
- In which industries are individuals who work with Artificial Intelligence likely to earn the highest salaries?
- What is the educational background of business owners? Does more education make it more likely for you to own a business?

Data: The data utilized for this analysis was taken from the 2019 Annual Business Survey API 
(https://www.census.gov/data/developers/data-sets/abs.2019.html)
The Datasets utilized were: 
- Company Summary: “Provides data for employer businesses by sector, sex, ethnicity, race, veteran status, years in business, receipts size of firms, and employment size of firms for the U.S., states, and metro areas" (US Census Bureau).
- Characteristics of Businesses: “Provides data for respondent employer firms by sector, sex, ethnicity, race, veteran status, years in business, receipts size of firm, and employment size of firm for the U.S., states, and metro areas, including detailed business characteristics" (US Census Bureau).
- Characteristics of Business Owners: “Provides data for owners of respondent employer firms by sector, sex, ethnicity, race, and veteran status for the U.S., states, and metro areas, including detailed owner characteristics" (US Census Bureau).
- Technology Characteristics of Businesses: provides data on technology use and production for Artificial Intelligence, Cloud-Based Computing, Specialized Software, Robotics, and Specialized Equipment technologies data at the U.S. and State level for the reference year 2018.

File Structure: 
- asmt-08.ipynb: Jupyter notebook containing the methodology for accessing the data through API calls, cleaning and transforming the data as well as the visualizations addressing the analysis questions. 
- projectreport.doc: Summary report based on our analysis and findings.  

<!-- Think of your README.md as your landing page for your project. Before a viewer dives into your files, what do you want them to know about your project? Here are some recommendations for your project README.mds:
Give a brief overview of what is in each folder in your repo, so a viewer knows how to navigate around.
Give a summary of what your project is all about:
Problem Statement: What question(s) did you aim to answer through your analysis?
Data: What data did you use? How did you acquire it?
Consider adding a data dictionary that explains what is in each column of your dataset
Data Processing: What steps did you take to clean and transform your data before more formal analysis
Results/Findings: What did you find throughout your analysis? This is a great place to add some of your visualizations
Conclusions/Recommendations: Are there any conclusions or recommendations that can be made based on your analysis?
Next Steps: If you feel like there is more that could be done with your data to investigate your initial questions, what would you do? Are there other datasets you could add? Other cleaning or tranformation steps? -->
