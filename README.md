# covid_hackathon_visualization Team JiaLiDun

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [Contributors](#contributors)
* [Contents](#contents)
* [Data](#data)
* [Folder](#folder)



## Contributors
Jeffrey Lai <br />
Xiaolu Qian <br />
Jiyu Wang <br />
<!-- Contents -->
## Contents
We aim to use visualization to show the effectiveness of governments' policy responses towards the COVID-19 pandemic in different countries. We looked at three different major categories of policies: containment and closure policies,  economic policies, and health system policies. Within each category, there are different levels of stringency which were also taken into consideration.

We first displayed the number of new cases daily and the cumulative cases for the user selected country on the interactive dashboard (link to Tableau Public dashboard). We then showed the information for all the policies and the categories of those policies that a country implemented. The duration of each policy and their overlaps were shown through the gannet chart.

For the evaluation of the effectiveness of those policies, we considered comparing the moving average of the cases per 100k before and after the date the policy gets implemented for each country. In addition, we compared across each policy for the average cases per 100k with other countries' cases per 100k. <br />

<!-- Data -->
## Data
We used two different datasets for our storytelling and visualization. [Oxford Covid-19 Government Response Tracker (OxCGRT) ](https://github.com/OxCGRT/covid-policy-tracker) is what we used for all the policy information including start date, end date, country, policy type, etc. The other dataset we use for the country-level number of cases daily are from [European Centre for Disease Prevention and Control](https://www.ecdc.europa.eu/en/publications-data/download-todays-data-geographic-distribution-covid-19-cases-worldwide). Both datasets are publicly available. <br />

## Folder
The Raw_data folder includes the raw dataset from both data sources described above. The Cleaned_data folder is what we use for generating the visualization in Tableau.
