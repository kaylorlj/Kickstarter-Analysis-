# Kickstarter-Analysis-

# Kickstarting With Excel
# Overview: 
	In this project, we were to create a pivot table and line graph to showcase the Outcomes based on Launch Date in Delieverable One. The second goal of this Challenge 
was to create a table as well as a second line graph to show the Goals. In both Delieverables, the general purpose was to exhibit data that was in the workbook into
both more comprehensive and user-friendly understanding.he purpose of this project in regards to this class is to get comfortable with simple tasks in Microsoft Excel and as an introduction into data analytics. Industry-wide businesses use 
Microsoft Excel on a daily basis and it is fundamental to understand how to show basic data in a computer language that is most heavily used in the job market. 

## Analysis and Challenges: 
	The first step was to find the years data in the workbook, this would be the first challenge I ran into. I was unsure how how to go about this, but I figured out a formula to convert Epoch time in Microsoft Excel workbooks. 
I did resort to Google to look for this formula. I was able to click on the row and convert each one.The Formula is: +(A1/86400)+DATE(1970,1,1). I found this formula by looking up Epoch time and how to create a formula with it in Excel. 
Through this I was able to accomplish the first task. The pivot table was much easier though I could not find how the data was supposed to be broken down into months instead of years.
After correcting the position of the row labels, I was able to get to 4064. Creating the final pivot table was simple; break it down into only the theatre category. 
I did not run into issues with the creation of final pivot table. Creating the line graph was not as simple as I had assumed, presumably because in my work it converted to years instead of monthes like in the example 
of Challenge 1 but my line graph did not look the same. It did depict the data though with years instead of monthes. In the second delieverable, we were to create a table, familiarize ourselves with the COUNTIFS() function. 
This took about an hour of practice before I was able to comprehensively understand how to use it. Even then, I know there are a few spaces where I overlooked mistakes.
We were to use this function to be able to extract large pieces of data without having to sit for hours scouring for it. 
Based on the data of the first pivot table, we were to find the overall 'successful','cancelled' and 'failures' Kickstarters and convert this information into a pivot table. 
Then, we were to decrease the data even more by only looking at Theatre 'successes' and 'failures'. In the grand total, there was 37 cancelled, 493 failed and 839 successful. 
The Outcomes Based on Goals shown that the smaller Kickstarter's were the most successful, keeping their 'successes' small. I created a table as instructed, finding that 1764 of the 1860 Kickstater's with less than $1,000 raised had a 94% success rate. 
As for failures, the vice versa is true. The more money to be raised, the less successful the Kickstarter's were. For $45,000 to $49,999, 11 failed and 6 succeeded making that a 62% fail rate. 
I faced the biggest challenge on Delieverable 1 when moving the data from the pivot table to create a line graph. I could not get the data to show similarly to the line
graph that is shown to give us an idea of what it should look like. The second difficultly came with Delieverable 2, with the COUNTIFs().
I was unable to get an accurate reflection of the table data onto the line graphs. I had this same issue with creating the line graph for Outcomes Based on Launch Date. 

### Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
	The year 2015 had the most successes in Kickstarters hitting their goals than any year between 2009 and 2017. Overall, very seldom were Kickstarter campaigns cancelled even if they did not meet their financial goal. 
- What can you conclude about the Outcomes based on Goals?
	The most 'sucessful' Kickstater's achieved the least amount of money in the 'Goals' table. Those whose goal was less than $1,000 were the most likely to achieve their goal with a 94% success rate. 
- What are some limitations of this dataset?
	The main limitation on this Kickstarter data is that firstly, it is only for certain genres. Secondly, with the categorization of different years, it does not really tell us if WHEN the Kickstarter was launched could plausibly
effect its outcome. Another limitation is how Kickstater's were viewed from a financial goal, which puts a skewed view on the term 'successful'. 
- What are some other possible tables and/or graphs that we could create?
	I think that using a bar graph would be beneficial in viewing the data as well as a reconfiguation of the pivot table. For the data of Theatre Outcomes by Launch Date, it could have been 
broken down into quarterly then we could have made a Box and Whisker plot. 
