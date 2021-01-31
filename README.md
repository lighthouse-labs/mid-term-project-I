# Mid-Term Project
This repository cointains all the information you need to work on the Mid-Term project.

## **Hello and Welcome!!!**

The goal is to predict the arrival delays of commercial flights. 

This repository contains following files:

- **exploratory_analysis.ipynb**: this file contains 10 questions we need to answer during the data exploration phase. They will help us to understand the data and become familiar with different variables.
- **modeling.ipynb**: this file contains instructions for modeling part of the project. We recommend to split modeling tasks into more notebooks.
- **data_description.md**: if you are looking for any information regarding specific attributes in the data this is the file to look in.
- **sample_submission.csv**: this file is an example how the submission for the modeling task should look like.

### Data

We will be working with data from air travel industry. We will have four separate tables:

1. **flights**: The departure and arrival information about flights in US in years 2018 and 2019.
2. **fuel_comsumption**: The fuel comsumption of different airlines from years 2015-2019 aggregated per month.
3. **passengers**: The passenger totals on different routes from years 2015-2019 aggregated per month.
5. **flights_test**: The departure and arrival information about flights in US in January 2020. This table will be used for evaluation. We are required to predict delays on flights from first 7 days of 2020 (1st of January - 7th of January). We can find sample submission in file _sample_submission.csv_

The data are stored in the Postgres database. You can see the information about the hostname and credentials [in Compass](https://data.compass.lighthouselabs.ca/23284197-327b-4c82-84fa-f220a40a7d1a).


### Presentation Guidelines

Your presentation should have following information.

- 1 slide for each task from **exploratory_analysis.ipynb**. Put an simple informative visualization on each slide.
- sampling strategy(ies)
- modeling techniques
- evaluation metrics 
    - compare different metrics for various prediction techniques
    - which model is the best and why?
- feature importance
- biggest challenges for your team


### Submission Guidelines

- share the link to your project repository


### How to Start

Don't start with the EDA tasks right away. Spend some time with the datasets on your own (there is plenty of time to get to tasks from us later on), try to look for interesting relationships and information inside the tables. Once you are familiar with the tables and information in them you can move on to the tasks from us that will be part of the final presentation. Then, you will see that they are a piece of cake :).
