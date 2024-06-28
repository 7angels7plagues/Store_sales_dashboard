# Store sales dashboard
A simple and interactive dashboard using advanced excel.

**OBJECTIVE-**

To analyse and create an annual report for given data of a store, while solving some sub-objectives.
+ Compare Sales and Orders.
+ Who puchased more - Men or Women.
+ Different order statues like delivered, refunded, returned and cancelled.
+ List states contributing to the sales.
+ Show relation between Age and Gender based on number of orders.
+ Channels who are contributing to maximum sales.
+ Show sales through map.

**STEPS-**
+ In data cleaning, cleaned and organised the data mainly with column header filters like checking for null value in each column, relpacing mismatch words in columns. Used replace function to replace M and W with respective Men and Women in Gender column likewise did in quantity column.
+ In data processing, added two new columns after "Age" and "Date" named respectively "Age group" and "Month" to provide more better and functional view. In Age group column used 'IF' condition to create groups in which age will fall under namely teenager, adult or senior. And month column is simply create to easily check month from date section.
+ In data analysis, created multiple pivot tables to easily analyse the data while solving some sub-objectives. Created six pivot tables, each table target one sub-objective.

**REPORT-**

A report consist of all pivot tables targeting each sub-objective connected with three slicers to make it more interactive. Three slicers named month, channel and category can be selected individually to provide specific stats at each month, sales through different channels or sales of different items.
