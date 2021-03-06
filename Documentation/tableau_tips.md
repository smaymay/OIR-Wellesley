## Tips for Tableau: 

### Re: Senior Survey Visualizations 
When you add new senior surveys to the merged file, the Tableau visualizations should automatically update as long as you: 
1. import the new data source (merged across all years)
2. keep the same variable names

I recommend inspecting the variables that each sheet uses. You can also get a general list of all variables used in the workbook by going to a sheet, clicking on the drop down next to the variable listing, and clicking “Hide All Unused Fields.”


### Re: Adding new visualizations / things I’ve learned 
* If you decide to add new visualizations that use percentages, definitely create separate calculations for the numerator and denominator, and combine with a simple third variable that just divides the two. Then you can show n values very easily in your visualizations. 

* It’s better (i.e. faster) to have a flat structure — several sheets are combined via a sheet selector into a dashboard where each sheet calculates one thing. 
Read here about sheet selectors: http://onlinehelp.tableau.com/current/pro/desktop/en-us/help.htm#dashboards_sheet_selector.html

