# sujana_task8
Dataset- train.xlsx
Tools used- Microsoft Power Bi
First, the dataset is imported in Power Bi, after clicking on "Transform data", a custom column is created with the sytax:
              Text.Combine({Text.From(Date.MonthName([Order Date])), Text.From(Date.Year([Order Date]))}, " ")
to get the column in the format "MM-YYYY".
Then click on "Close and Apply" and create bar graphs, donut graph and line graph.
