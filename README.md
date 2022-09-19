# Superstore Sales KPI Dashboard

In this Project, I normalized a superstore dataset using **MS Excel** and extracted meaningful insights from it using **Power BI**.

## Data Sourcing:
The data used in this case study is present in the `Data source` folder.
## Data Normalizing:
The given data is in the form of table which include all the permanent and the continuous data. Firstly, I seperate the data into seperate sheets of **Sales**, **Customers**, **Sales Reps**, and **Locations** and **Products**.

![denormalized SalesData](https://user-images.githubusercontent.com/107538510/175783961-4fb009fe-1c89-4861-9a76-b6184f1f474d.PNG)

After seperating the columns into different sheets.

![normalized data](https://user-images.githubusercontent.com/107538510/175783987-080e0d3c-94b7-4bf9-a2c1-f05d7a04e9e9.PNG)

## Data Modelling in Power BI:
After normalizing the data, I just upload MS Excel data file in the Power BI where the power query is opened. I then clean and modify the data by making some changes like the first row assign ass header row and deleting unnecessary blank rows in the power query. Then load the data in Power BI. After checking the above tabs, I opened the model tab view and connect the fact table (continuous data table) keys to the dimension (permanent data table) keys.

![model tab](https://user-images.githubusercontent.com/107538510/175784265-aaf85467-050f-438b-b2ab-05306f2c75fb.PNG)

## Creating report In Power BI:
After building the relationship between different tables, it is easier to visualize the data for quick and better understanding of the Sales to region and to find the maximum number of Sales done by which Salesperson. All the insights shows the answers to every question about sales, customer, profit, and the regions where maximum sales are done.

![Superstore Sales KPI Dashboard](https://user-images.githubusercontent.com/96622330/190966013-f8d7aad7-9f5f-4868-a1b0-c6cee85f9e3a.png)
