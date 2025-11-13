# Bond-Elisabeth-Project2-721-
Project 2 for RStudio class (721), Duke Masters of Biostatistics 

Data is air pollution data that measures air quality dialy from 2018-202. Each file includes the date and concentrations of CO, PM2.5, and O3; the 2020 dataset only includes data through April.

11/11: Published the Rmd file to github. Iteration one. 
The data is loaded and the data cleaning funciton has been created. I also ran all three data sets in the function and created the cleaned version. 
The funciton:
• Renames the pollutant concentration columns with more appropriate variable names (no spaces, short, informative).
• Formats the date variable correctly.
• Calculates the daily average for pollutants that had more than one entry for a single day.
• Remove any duplicate rows.
• Loops through the pollutants and sets any measured concentration that is negative to zero to fix measurement error

11/13: Iteration two
Using the cleaned data, created a merged data set with all three years and made two plots representing the data. 
The first plot has month on the x-axis and CO and O3 concentration on the y-axis. The plot displays monthly
averages, averaged over the 3 years, and includse 95% confidence interval error bars around the points. 
The second plot has month on the x-axis and PM2.5 concentration on the y-axis. It includes year as different colors.

The styler package was also run on the rmd file to make the code presentable and readable. 
