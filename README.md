# session34-Assignment1
DATA ANALYTICS WITH R, EXCEL AND TABLEAU SESSION 34 ASSIGNMENT 1

SESSION 34: TABLEAU DESKTOP (CONTD.)
Assignment 1
5. Problem Statement 
1. Create a Waterfall chart which would show running total profit over a period of time. 
2. The color of the mark should be red if the profit recorded for that Month is less than the profit recorded compared to previous month, else Green 
3. Adjust the tooltip to show as given in the picture below. 



Waterfall charts are powerful visuals for your data dashboard because they effectively display the cumulative effect of 
sequential positive and negative values. Building waterfall charts in Tableau requires a few specific steps. 
1) Connect to the “Sample – Superstore Subset (Excel)” excel file (2014 – 2017) given as link by AcadGild
2) Drag the Orders worksheet into the Drag Sheets Here section and select the orange Go to Worksheet button.
3) Drag a dimension (order data(month)) to the Columns Shelf and (profit (sum profit)) measure to the Rows Shelf. 
4) Right-click on the Month field on the Columns Shelf to convert it to “Discrete”.
5) Add a Running Sum of Total Table Calculation to the measure on the rows shelf. To do this, right-click on the Profit pill, 
6) select Add Table Calculation, and add the table calculation:



6)Change the mark type from Automatic to Gantt Bar in the Marks Card.
7) Create a calculated filed named “-Profit” and write the following formula: -[Profit] 

8) Drag the new measure “- Profit” to the size tab on the Marks Card. Positive values will therefore extend our bar upwards and negative values will extend the bar downwards.
9) Add the Profit measure to the color tab on the marks card and edit the colors and change the color palette to be two stepped.  Now, we
 have a working waterfall chart showing growth and contraction in profit from one quarter to the next.
10) All the graph details obtained are provided as screen shot for easy reference

