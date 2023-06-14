# Final-Project-Tableau

## Project/Goals
>In this project, we will combine and practice implementing what we have learned throughout this course, including:
>
>1. Turning data into easily consumable visual insights, using Tableau
>2. Creating impactful dashboards that help stakeholders make decisions, based on a business questions
>3. Communicating insights with the correct visualizations

## Process
### Step 1: Connecting Data
Download data from [airbnb.xlsx](https://docs.google.com/spreadsheets/d/1BJWyZpZrrRUla_EQ6Pnusy0KH31UMGf2/edit?usp=sharing&ouid=108445376648788204707&rtpof=true&sd=true). Connect the dataset to the Tableau datasource. The dataset contains string, number, and date data type.

### Step 2: Explore the Table

Map 

<img width="986" alt="image" src="https://github.com/maybester/Data-Visualization-and-Dashboards-with-Tableau/assets/73912419/7074fb21-ce49-451d-add8-35462b7bb5c8">

Airbnb of NYC is located mainly in four districts which are Bronx, Brooklyn, Manhattan and Queens. By running a quick table calculation, it can be interpreted that Manhattan has half of the hosts (52.61%), Brooklyn has 38.31% of the hosts, Queens has 7.47% of the hosts and Bronx and staten Island have fewer hosts which are only 1.13% and 0.48% of the total number.

Date and time

<img width="979" alt="image" src="https://github.com/maybester/Data-Visualization-and-Dashboards-with-Tableau/assets/73912419/8c21636d-1792-4bdd-b1f8-8ef623de3a23">
The line graph indicated the numbers of new hosts during 2008 to 2015. From the data we can see that Airbnb continously get new hosts and the number of new hosts is increasing from 2008 up until 2014, and then have a drop in 2015 after reaching a peak.

Show me tables

<img width="966" alt="image" src="https://github.com/maybester/Data-Visualization-and-Dashboards-with-Tableau/assets/73912419/b6f74e7c-824d-4b27-bce4-bea61cf51960">

The stack graph showed majority of the room type host is entire home / apartment or private room. However, in Manhattan, private room is less hosted than entire unit of the property while situation is the opposite in Queens and Brooklyn.

<img width="981" alt="image" src="https://github.com/maybester/Data-Visualization-and-Dashboards-with-Tableau/assets/73912419/17ebd232-fa29-4de5-ab5e-5559c0b4f9a1">

The treemap showed average price per night in each district of NYC. Manhattan has the highest average price per night which is 198 $ while Bronx has the lowest average price per night which is 94.7 $.

## Results

Clustering results
<img width="405" alt="image" src="https://github.com/maybester/Data-Visualization-and-Dashboards-with-Tableau/assets/73912419/ddb7a052-ba57-4ff9-80f5-d60169b887c7">




Forcasting results
<img width="992" alt="image" src="https://github.com/maybester/Data-Visualization-and-Dashboards-with-Tableau/assets/73912419/9720138c-c548-40a1-9ea6-6e12770a5a14">



Linear regression results
<img width="963" alt="image" src="https://github.com/maybester/Data-Visualization-and-Dashboards-with-Tableau/assets/73912419/9380d5ec-c1b6-49df-8f75-e1bac3981834">

<img width="968" alt="image" src="https://github.com/maybester/Data-Visualization-and-Dashboards-with-Tableau/assets/73912419/efc6df8b-c16c-4127-acbf-656ee555f04b">


## Challenges 

1. hard to find variables for better clustering since the numeric pamaeters are not many.

2. R2 of linear regression model is small which means data is not well explained by model.



## Future Goals

1. To improve the linear regression model, outlier values need to be predicted and missing values need to be identified.

2. Transform the feature data brfore put into a regression model.

3. multiple linear regression model can be conducted for better fit of the data.




