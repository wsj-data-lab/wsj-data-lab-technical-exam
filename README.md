# Data Analyst Technical Exam

This repository contains the dataset and questions for the WSJ Data Lab's technical exam. The dataset contains ["311" water quality complaints](http://www1.nyc.gov/nyc-resources/service/2713/water-complaint) reported in New York City. A table of relevant variables is given below:

Variable | Description | Notes
-------- | ----------- | -----
Created Date | Date and time 311 complaint was made. | MM/DD/YYY HH:MM:SS AM/PM
Closed Date | Date and time 311 complaint was resolved. | MM/DD/YYY HH:MM:SS AM/PM
Descriptor | Description of the water quality complaint. |
Status | If the complaint is open, pending, closed, or started. |
Resolution Action Updated Date | Date and time 311 complaint began to be addressed. | MM/DD/YYY HH:MM:SS AM/PM

## Questions

Please answer the following. You should send a zipped version of the repository with your solutions via email to [john.wiley@dowjones.com](mailto:john.wiley@dowjones.com). Answers can be presented in either a Jupyter notebook (preferred), a markdown file, or a pdf.

1. What are the five most frequent descriptors of complaints? What are they by borough?

2. Has the number of complaints changed over time? How? Plot the change in complaints over time by borough.

3. For each complaint, add a metric for wait time between when the complaint was made and its resolution. What do you expect the distribution of wait times to be? Explain. 

4. Now plot the distribution of wait times and calculate its mean and median. Did the data match your expectations?

5. Choose the best measure of central tendency to represent wait time (mean, median, trimmed mean, etc.) Explain your choice. 

6. Have wait times changed over time? What about by borough?

7. How would you predict the wait time for a new complaint?

8. The City of New York is interested in reducing the average time it takes to resolve a water complaint. Based on this dataset, what would be your recommendations to the city?
