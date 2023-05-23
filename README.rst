===============================
Data Visualization with Tableau
===============================


1.)	Data Overview
The data was collected from Neighborhood Crime Rates - City of Toronto Open Data Portal. The data was published by Toronto Police Service and was last refreshed in May 2022. The data consists of the crime counts and rates of various types of crime across 140 different neighborhoods in Toronto. 

The data was changed from a wide format to a long format to make manipulation in Tableau easier. 

2.)	Dashboard 1: Distribution of Crime in Toronto Neighborhoods

2.1) Explanation of Visuals: See Figure 1 (page 2):
I.	The color scheme for the overall dashboard was chosen to be blue as it is the color scheme used by the Toronto Police Department. 
II.	Left Section: Shows the legends and the different filters that can be chosen. All three filters impact all the visuals, except “Number of Crimes”. “Number of Crimes” does not show rate information as the dataset did not contain that information. The filters work as follows:
•	Select Rate/Count: Select if the dashboard should show the data based on the rate of crime or the actual count.
•	Type: Select what type of crime to show. Examples are assault, shooting, etc.
•	Year: Select what year’s data the dashboard should show.
III.	Number of Crimes: Shows the total number of crimes, filtered by Type and Year.
IV.	Highest Crime: Shows the neighborhood with the highest crime, filtered by Rate/Count, Type, and Year.
V.	Average Crime per Hood: Shows the average crime per neighborhood, filtered by Rate/Count, Type, and Year.
VI.	Top 5 Highest Neighborhoods: This bar chart shows the top 5 neighborhoods with the most crimes for the given type and year, filtered by Rate/Count, Year, and Type. The hood names can be selected to be shown on the map and the “Number of Crimes” will also change accordingly.
VII.	Heat Map: This shows the heat map of crime, filtered by Rate/Count, Type, and Year. Selecting a region changes the “Spread of Crime” pie chart to represent that hood. The different hoods can also be hovered over to see the crime/rate. 
VIII.	“Proportion of Crime”: This pie chart shows the sorted proportion of crimes, filtered by Year, Type, and Hood (chosen using the map). This also acts as a filter of Type for every other visual.
 
Figure 1: Distribution of Crime in Toronto Neighborhoods

2.2) Insights:
The First dashboard’s purpose is to understand crime in different neighborhoods. The dashboard allows you to quickly see which neighborhood contains the most amount of crime and which neighborhoods are relatively safer. Users interested in the distribution of crimes in a particular location can do so using the pie chart. The important takeaways can also be seen at the top. Users interested in only a particular crime can also filter by that crime. 

Example use case: A user interested in the count of Assault cases for 2021 can input those filters. The user will quickly see the total number of crimes in 2021 for assault cases was 19,044. The highest crime was 971 and the average number of cases per neighborhood was 136. The user will also be able to see the top 5 worst neighborhoods in terms of Assault where they can click on the bars to have the neighborhoods highlighted on the map. They will also be able to tell, at a glance, how assault crimes are spread across Toronto. 



3.)	Dashboard 2: Crime over the years in Toronto

3.1) Explanation of Visuals: See Figure 2 (page 4):
I.	The color scheme for the overall dashboard was chosen to be blue as it is the color scheme used by the Toronto Police Department. 
II.	Left Section: Shows the legends and the different filters that can be chosen.  Both filters impact all the visuals, except “Distribution of Crime”. “Distribution of Crime” is not impacted by Type as it is showing different types. The filters work as follows:
a.	Type: Select what type of crime to show. Examples are assault, shooting, etc.
b.	Neighborhood: Select what neighborhood’s data to show
III.	Year of Highest Crime: This section shows the year for the highest crime, filtered by Type and Neighborhood.
IV.	Year of Lowest Crime: This section shows the year for the lowest crime, filtered by Type and Neighborhood.
V.	Average crime: This section shows the average crime over the 2014-2021 period, filtered by Type and Neighborhood.
VI.	Distribution of Crime: This bar chart shows the sorted distribution of crime for 2014-2021, filtered by neighborhood.
VII.	Crimes 2014-2021: This line graph shows how crime has been changing over the years for a particular hood, filtered by Type and Neighborhood.
VIII.	% Change in crime: This graph shows the percentage change of a type of crime for a particular hood when compared to its previous year, filtered by Type and Neighborhood

3.2) Insights:
The Second dashboard’s purpose is to understand crime over the years in Toronto neighborhoods. The dashboard allows you to quickly see which years had the highest and lowest number of crimes and what the average number of crimes per year is in Toronto. The bottom portion shows gives the user an idea of how the type of crime has been evolving over the years.

Example use case: A user interested in Assault crimes in York University Heights can quickly see that 2019 had the highest number of assault-related crimes (382), whereas 2016 had the lowest (273) and that approximately 340 assaults take place in York University Heights each year. They also get to see the sorted distribution of the crimes in York University Heights over the 8-year period. The last portion shows how assault crimes have evolved in York University Heights throughout the years and how they change year to year. 2020 to 2021 see a sudden dip in the number of assault crimes. This is almost certainly due to Covid Lockdowns. 
 Figure 2: Crime over


Credits
-------

This package was created with Cookiecutter_ and the `audreyr/cookiecutter-pypackage`_ project template.

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`audreyr/cookiecutter-pypackage`: https://github.com/audreyr/cookiecutter-pypackage
