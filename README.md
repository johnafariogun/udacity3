# (Dataset Exploration Title)
## by (your name here)


## Dataset

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area for the month of february.

#### After creating a copy of the original dataset. I wrangled the data by:
- Converting columns **start_time** and **end_time** to DateTime format
- Extracting the starting hour of the trip from the **start_time** into a **start_hour** column
- Extracting the starting day of the trip from the **start_time** into a **day** column
- Extracting the age of the user bu substracting the **member_birth_year** from year of the trips  into a **age** column, but first converting the **member_birth_year** to a *float* datattype
- Calculating the distance of the trip in kilometer using python GeoPy package and collating them in a **distance_(km)** column.
- Filling all categorical variable's missing value with unknown and numerical with 0, so as to try to maintain the integrity of the dataset

## Summary of Findings

> After carrying out univariate, bivariate and multivariate analysis. I found out that:
- User type isn't related to neither the Age nor the Gender of the user.
- the bias of the male gender probably distorted a lot of the visulizations.
- The longer a trip was the more the probability of the gender being **male** or **Other**
- Subscribers generally go on longer trips compared to customers excluding outliers
- Males take lesser time on trips for the same distance
- The amount of users both customers and subscribers of the forgobike are steadily increasing.
- Also that longer trips were taken during the week than on weekends.


## Key Insights for Presentation

> The amount of users both customers and subscribers of the forgobike are steadily increasing. 
> A large amount of the users of fordgobike are in their late twenties to their late thirties
> Distance traveled and Duration of trip is actually not influenced concretely by any variable