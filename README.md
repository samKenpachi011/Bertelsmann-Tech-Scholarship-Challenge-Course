# Bertelsmann-Scholarship-Data-Track

## A walk through the #60DAYSOFUDACITY Challenge

## Day 1: Lesson 1:The Analytical Problem

## Covered
**Strategy for solving problems.

## The Problem Solving Framework
**CRISP-DM :** | Cross Industry Standard Process for Data Mining

### CRISP-DM FRAMEWORK

<image src="crisp-dm-framework.png" />

## A brief summary of the stages in the framework
**Business Issue Understanding :** Develop a mental model while answering questions such as :
  * What decisions needs to be made
  * What information is needed to info that decision
  * What analysis will provide the information to inform that decision
  
**Data Understanding :** Start with data collection/identify data problems/subsets. Try and answer :
  * What data is needed
  * What data is available
  * What are some of the important characteristics of the data
  
**Data Preparation :** Here you will go through the Gathering| Cleasing| Formatting| Blending| Sampling.
  * Gathering: Collecting data from multiple sources.
  * Cleasing: Resolving issues prior to analysis/doing away with missing or incorrect data.
  * Formatting: Changing how the data appears/renaming fields.
  * Blending: Combining the data/Joining.
  * Sampling: Working with more manageable number of records.
   
**Analysis and Modeling :** Determine the methodology to use to use to solve the problem + Determine the important factors + variables to help solve the problem.
  * Run the model and move to the validation phase.
  
**Validation :** Here we are getting to a certain level of confidence in our model.
  * Observe the key results on the model and which variable help predict better results.
  * Ensure the results make sense within the context of the business problem.
  * Repeat the process.

**Presentation :** Effectively communicate results to decision makers.
  * Create visualizations and reference data resources and measure success of your analysis.
  * Tell a story without overwhelming use of the results.
  * For complex analyses walk the audience through the analytical problem solving phase.

## Day 2: Lesson 2: Selecting an Analytical Framework

**Selecting an appropriate analytical methodology based on the context of the problem :**
  
## Data Analysis Methodology

<image src="meth_map.png"/>

**The methodology map will help in taking the right path for solving our problem :**
## Solving a problem using non-predictive data analysis include analysis in either of the following:
**Geospatial :** Grouping data base on location data for example identifying customers based on geographic region or distance to stores.

**Segmentation :** Grouping data together for example customers who have purchased different items.

**Aggregation :** Calculating a value across a group or dimension for example aggregate sales data for a sales person by month.

**Descriptive :** This uses statistics or statistical summaries of data for example average,median,mean and interquartile range

## Solving a problem that requires a predictive outcome:
Predictive analytics uses data to predict a future outcome for example a company may use predictive analytics to forecast demand or whether a customer will repsond to an advertising campaign.
Having data leads to the rich data path and not having data leads to poor data path

**Questions to consider for predictive business problems :** 
  * Do we have enough data on what is being predicted.
  * The outcome of the what is being predicted.
  
**Data Poor Business Problem :** If we don't have enough data to solve the problem we can use a A/B testing so that we gather the data to experiement with .
**Data Rich Business Problem :** Having data will allow one to choose the type of outcome either numeric or classification.

**NUMERIC MODELS :** First determine whether the target variable/outcome being predicted is numeric or non-numeric. If the variable is numeric the following are types of numeric variables:
  * Continuous- a variable that can take on all values in range for example height can be down to many decimal places.
  * Time Based- a value based on what will happen over time.
  * Count- variables that are discrete,positive integers used to analyze variables that you can count.

**NON NUMERIC MODELS :** Often called categorical as the values of the variables take on a discrete number of possible values or categories for example whether a store is classified as large,medium or small.
  * Keep in mind that when modelling categorical variables the number of possible outcomes is an important factor.
  * If there are only two(2) possible outcomes for example YES/NO the variable is described as Binary.
  * When there are more than two(2) possible outcomes then its non-binary.
  
    
  
  
