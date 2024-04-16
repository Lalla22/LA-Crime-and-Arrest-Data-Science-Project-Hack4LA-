# Hack 4 LA: Los Angeles Crime & Arrest Datasets, Data Exploration, and Visualizations


1. [About this Project](#about-this-project)
2. [Data Exploration](#data-exploration)
   
   i. [Exploring the Data Sets](#exploring-the-data-sets)
   
   ii. [Data Dictionary](#data-dictionary)
   
   iii. [Visualizations](#visualizations)
   
4. [Data](#data)

      i.[Crime Data](#crime-data)

      ii.[Arrest Data](#arrest-data)

6. [Project Poster](project-Poster)
7. [Use, Licensing, Attribution](#use-licensing-attribution)




## About this Project
This project centers on leveraging data exploration techniques to analyze arrest data provided by the Los Angeles Police Department spanning the years 2010 to 2019. With datasets comprising over 1 million records each, the analysis delves into crime incidents and arrests to extract insights into crime patterns, demographic trends, and geographic hotspots. The aim is to inform the development of targeted public safety awareness initiatives and proactive strategies for crime prevention. Through the utilization of machine learning algorithms, tailored public awareness campaigns, and collaborative partnerships, the project seeks to empower residents and law enforcement agencies to work together towards creating safer communities in Los Angeles.



## Data Exploration
Descriptive Statistics: Descriptive statistics such as mean, median, mode, standard deviation, minimum, and maximum were computed for numerical columns to understand the central tendency and variability of the data.

Data Visualization: Various data visualization techniques were employed to visually explore the data. These include:

Box plots to visualize the distribution, central tendency, and variability of numerical data.
Scatter plots to identify relationships and patterns between numerical variables.
Histograms with KDE (Kernel Density Estimation) to visualize the distribution of numerical data.
Count plots to visualize the frequency of categorical variables.
Pair plots to visualize pairwise relationships between numerical variables.
Correlation Analysis: A correlation matrix was computed and visualized using a heatmap to identify correlations between numerical variables. 

Skewness and Kurtosis Analysis: Skewness and kurtosis were calculated to assess the symmetry and peakedness of the distribution of numerical data. 
Overall, these data exploration techniques were employed to gain insights into the structure, patterns, and relationships within the arrest and crime data for the city of Los Angeles.

### Exploring the Data sets

### Data Dictionary
![datadictionary](https://github.com/Lalla22/LA-Crime-and-Arrest-Data-Science-Project-Hack4LA-/assets/47159210/92dcd1bd-ec55-4abb-b8fb-8d7c1d1a88a4)
![datadictionary2](https://github.com/Lalla22/LA-Crime-and-Arrest-Data-Science-Project-Hack4LA-/assets/47159210/5d5ec129-20cd-41ed-b9d5-5e9268262829)

### Visualizations
![visulization1](https://github.com/Lalla22/LA-Crime-and-Arrest-Data-Science-Project-Hack4LA-/assets/47159210/c31ee3a5-f75e-4669-b011-a89fead62705)
![visuilization2](https://github.com/Lalla22/LA-Crime-and-Arrest-Data-Science-Project-Hack4LA-/assets/47159210/99aec3d0-1685-434e-84fe-dfc1c25f00fa)

## Data 
- Both data sets are hosted by the city of Los Angeles. The orgainzation has an open data platform [found here](https://data.lacity.org/), and they update thier information according to the amount of data that is brought in. Data was uploaded on to kaggle and can be [found here](https://www.kaggle.com/datasets/cityofLA/los-angeles-crime-arrest-data/data) to download and review.
- Update Frequency: This dataset is updated weekly.
- Data provided by Los Angeles Police Department.
- Dataset Owners (LAPD OpenData)
### Crime Data
 - This dataset reflects incidents of crime in the City of Los Angeles from 2010 - 2019. This data is transcribed from original crime reports that are typed on paper and therefore there may be some inaccuracies within the data. Some location fields with missing data are noted as (0°, 0°). Address fields are only provided to the nearest hundred block in order to maintain privacy.
   - Records
   
         Rows: 2.12M

         Columns: 28

         Each row is a crime incident
 - Link to [dataset](https://data.lacity.org/Public-Safety/Crime-Data-from-2010-to-2019/63jg-8b9z/about_data).
### Arrest Data
 - This dataset reflects arrest incidents in the City of Los Angeles from 2010 to 2019. This data is transcribed from original arrest reports that are typed on paper and therefore there may be some inaccuracies within the data. Some location fields with missing data are noted as (0.0000°, 0.0000°). Address fields are only provided to the nearest hundred block in order to maintain privacy.
 - Records
   
         Rows: 1.32M

         Columns: 25

         Each row reppresents an arrest
 - Link to [dataset](https://data.lacity.org/Public-Safety/Arrest-Data-from-2010-to-2019/yru6-6re4/about_data).

## Project Poster
![Hack4LA Public Saftey Awarness Project picture](https://github.com/Lalla22/LA-Crime-and-Arrest-Data-Science-Project-Hack4LA-/assets/47159210/0e2295ee-1287-4e8d-8f78-28b3962b7f30)

## Use, Licensing, Attribution
The dataset used is maintained using Socrata's API and Kaggle's API. Socrata has assisted countless organizations with hosting their open data and has been an integral part of the process of bringing more data to the public.
This dataset used is distributed under the following licenses: Creative Commons 1.0 Universal (Public Domain Dedication)
