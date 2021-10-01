<!-- Add banner here -->
![undraw_Weather_re_qsmd](https://user-images.githubusercontent.com/83410546/135469595-7be2c567-4cd0-4f46-b787-bd8f0d18f650.png)

# Weather-Dataset-Analysis

<!-- Add buttons here -->
![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/ridhed/Weather-Dataset-Analysis?include_prereleases)
![GitHub last commit](https://img.shields.io/github/last-commit/ridhed/Weather-Dataset-Analysis)
![GitHub issues](https://img.shields.io/github/issues-raw/ridhed/Weather-Dataset-Analysis)
![GitHub pull requests](https://img.shields.io/github/issues-pr/ridhed/Weather-Dataset-Analysis)
![GitHub](https://img.shields.io/github/license/ridhed/Weather-Dataset-Analysis)

<!-- Described the project in brief -->
The Notebook described in the section will query the daily-summaries dataset to retrieve the desired data based on few constraints.


# Table of contents

- [Project Title](#project-title)
- [Data Analysis Project](#the-basic-phases-in-data-analysis-project)
- [How I Did The Weather Dataset Analysis](#how-i-did-the-weather-dataset-analysis)

# The basic phases in Data Analysis Project 
1. Business Understanding
 * Data mining goals are defined.
 * The fundamental requirement is to understand client and business objectives.
 * Current data mining scenario factors in resources, constraints and
assumptions should also be taken into the consideration.
2. Data Understanding
 * In this stage, a sanity check is conducted to understand whether it is appropriate for data mining goals.
 * The data is collected from various sources within the organization.
 * It is a highly complex process since data and process from various sources are unlikely to match easily.
3. Data Preparation
 * The data is production ready in this stage.
 * The data from diverse sources should be nominated, cleaned, transformed,formatted, anonymized, and created.
 * Data cleaning is a process to "clean" the data by smoothing noisy data and
satisfying in missing values.
4. Modelling
 * In this stage, mathematical models are used to determine the data patterns.
 * Suitable modelling techniques need to be chosen for the prepared data set.
 * After that, create a scenario to validate the model. Then run the model on the prepared data set.
5. Evaluation
 * In this stage, patterns recognized are examined against business objectives.
 * A go or no-go decision should be taken to move the model in the deployment phase.
6. Deployment
 * In this stage, ship your data mining.
 * Discoveries (model/reports) to every business operation.
 * A thorough deployment plan, for shipping, maintenance, and monitoring of data mining discoveries is created.

[(Back to top)](#table-of-contents)

# How I Did The Weather Dataset Analysis

Functions Used For Analysis

* head() - It shows the first N rows in the data (by default, N=5).
* shape - It shows the total no. of rows and no. of columns of the dataframe
* index - This attribute provides the index of the dataframe
* columns - It shows the name of each column
* dtypes - It shows the data-type of each column
* unique() - In a column, it shows all the unique values. It can be applied on a single column only, not on the whole dataframe.
* nunique() - It shows the total no. of unique values in each column. It can be applied on a single column as well as on the whole dataframe.
* count - It shows the total no. of non-null values in each column. It can be applied on a single column as well as on the whole dataframe.
* value_counts - In a column, it shows all the unique values with their count. It can be applied on a single column only.
* info() - Provides basic information about the dataframe.
* isna() - function is used to detect missing values. It return a boolean same-sized object indicating if the values are NA

Questions Answered/Analysed From The Dataset

* Q.1)  Find all the unique 'Wind Speed' values in the data.
* Q.2) Find the number of times when the 'Weather is exactly Clear'.
* Q.3) Find the number of times when the 'Wind Speed was exactly 4 km/h'.
* Q.4) Find out all the Null Values in the data.
* Q.5) Rename the column name 'Weather' of the dataframe to 'Weather Condition'.
* Q.6) What is the mean 'Visibility' ?
* Q.7) What is the Standard Deviation of 'Pressure'  in this data?
* Q.8) What is the Variance of 'Relative Humidity' in this data ?
* Q.9) Find all instances when 'Snow' was recorded.
* Q.10) Find all instances when 'Wind Speed is above 24' and 'Visibility is 25'.
* Q.11) What is the Mean value of each column against each 'Weather Condition ?
* Q.12) What is the Minimum & Maximum value of each column against each 'Weather Condition ?
* Q.13) Show all the Records where Weather Condition is Fog.
* Q.14) Find all instances when 'Weather is Clear' or 'Visibility is above 40'.
* Q.15) Find all instances when :
       A. 'Weather is Clear' and 'Relative Humidity is greater than 50'or
       B. 'Visibility is above 40'
       
[(Back to top)](#table-of-contents)


[GNU General Public License version 3](https://opensource.org/licenses/GPL-3.0)
