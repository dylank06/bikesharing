# bikesharing

Link to Dashboard: https://public.tableau.com/shared/STXHJGXQR?:display_count=y&:origin=viz_share_link

## Summary 

- The purpose of this ananlysis was to create a visual story of NYC Citibikes raw data and turn it into useful information using Tableau. To present a business proposal for a bike-sharing company. Created worksheets, dashboards, and stories to visualize key data from a New York Citi Bike dataset.

## Overview of Analysis

### Change Trip Duration to A Datetime Format 

- Used Python and Pandas functions, to convert the "tripduration" column from an integer to a datetime datatype to get the time in hours, minutes, and seconds (00:00:00). After converting the "tripduration" column to a datetime dataytpe, I exported the DataFrame as a CSV file to use for the trip analysis.

### Created Visualizations for the Trip Analysis

- Using Tableau, created visualizations that show:
  - How long bikes are checked out for all riders and genders.
  - How many trips are taken by the hour for each day of the week, for all riders and genders.
  - A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.

### Created a Story and Report for the Final Presentation 

- Created a story in Tableau and write a report that describes the key outcomes of the NYC Citibike analysis.

## Results

Checkout Times for Users:

![Screen Shot 2021-01-22 at 2 55 28 PM](https://user-images.githubusercontent.com/16258584/105547863-93537e00-5cc4-11eb-94bd-67651d50a39f.png)

The line chart shows the average duration for users Citibike rides. Showing the peak of the bell curve at about 5 hours.

Checkout Times by Gender:

![Screen Shot 2021-01-22 at 2 55 12 PM](https://user-images.githubusercontent.com/16258584/105548732-a024a180-5cc5-11eb-9d98-8dc76888a0fd.png)

Theis line chart shows the average duration for user for Citibike rides broken down by gender. Showing males and females have similar peaks but different volumes. 

Trips by Weekday per Hour: 

![Screen Shot 2021-01-22 at 2 55 37 PM](https://user-images.githubusercontent.com/16258584/105548916-e24de300-5cc5-11eb-819e-00e0b59de813.png)

The heat map shows the peak hours during the weak for Citibike rides. THe hottest hours seem to be in the mornings before work and in the afternoons when users are getting off work. 

Trips by Gender by Weekday:

![Screen Shot 2021-01-22 at 2 55 44 PM](https://user-images.githubusercontent.com/16258584/105548982-fabdfd80-5cc5-11eb-904d-4d33399f10d8.png)

The heat map shows the peak hours during the weak for Citibike rides broken down by gender. THe hottest hours seem to be in the mornings before work and in the afternoons when users are getting off work. The heat map also shows the higher volume for male riders.

Top Starting Locations:

![Screen Shot 2021-01-22 at 2 55 59 PM](https://user-images.githubusercontent.com/16258584/105549209-440e4d00-5cc6-11eb-91a3-2bfc7e7b379c.png)

This geographical map shows the staring locations for NYC Citibike rides. This useful for planning bike placements. 

Top Ending Locations:

![Screen Shot 2021-01-22 at 2 56 09 PM](https://user-images.githubusercontent.com/16258584/105549282-64d6a280-5cc6-11eb-87e8-fa93af47b1ed.png)

This geographical map shows the ending locations for NYC Citibike rides. This useful for planning bike pickups. 

Gender Breakdown:

![Screen Shot 2021-01-22 at 2 56 19 PM](https://user-images.githubusercontent.com/16258584/105549405-85066180-5cc6-11eb-9004-1d7f5b26431e.png)

This pie chart shows the number of rides split between male, female, and unkown. THe chart shows that males are the majority of Citibike rides. 

## Results 

The combination of the different charts, maps, and graphs tell a vivid story on who the NYC Citibike customer base is. Citibike riders are most likely to be male and will most often be traveling before or after work during the weekdays. To gain more insight there would need to be more data so we could identify seasonal and long term trends to try to forecast the future better. 
