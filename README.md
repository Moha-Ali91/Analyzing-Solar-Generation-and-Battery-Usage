# Analyzing-Solar-Generation-and-Battery-Usage

Create a project that analyzes solar electricity generation, electricity usage, and battery usage data to understand the potential benefits of using a battery system to store excess solar electricity. 
The participants are required to utilize SQL and Python programming language and various libraries, including pandas for data manipulation, numpy for numerical operations, matplotlib for data visualization, and datetime for handling time-related data.

You can download the data for this project here, (it is an excel workbook) https://github.com/HarunMbaabu/Data-Analyst-Assessment/blob/main/Junior%20Data%20Analyst%20_%20Data.xlsx 

# Please do the following: 
1). Perform data visualization and checks

2). Calculate the Electricity Bought

3). Calculating Excess Solar Generation.

4). Model the Battery Charge Level

# Sample Solution: 
https://github.com/HarunMbaabu/Data-Analyst-Assessment/blob/main/Analyze%20the%20data.ipynb

# Project Overview.
This project involves analyzing solar electricity generation, electricity usage, and battery usage data to understand the potential benefits of using a battery system to store excess solar electricity. The project utilizes the Python programming language and various libraries, including pandas for data manipulation, numpy for numerical operations, matplotlib for data visualization, and datetime for handling time-related data.

# Project Steps

# Step (i): Data Visualization and Checks
The project begins by loading the provided data from an Excel file (Junior Data Analyst _ Data.xlsx) into a pandas DataFrame. 
The data contains information about solar electricity generation, electricity usage, and other relevant parameters. The goal of this step is to visualize and compare the average solar electricity generation and electricity usage for each hour in a day.

# Step (ii): Calculating Electricity Bought
In this step, the project calculates the electricity needed to be bought from the provider by subtracting the solar electricity generation from the electricity usage. The numpy library is used to efficiently perform element-wise subtraction and limit the result to non-negative values.

# Step (iii): Calculating Excess Solar Generation
The excess solar electricity generated is calculated by subtracting the electricity usage from the solar electricity generation. Similar to Step (ii), numpy is used to perform element-wise subtraction and limit the result to non-negative values.

# Step (iv): Modeling Battery Charge Level
This step models the cumulative battery charge level over time. The project assumes a maximum battery capacity of 12.5 kWh. The battery charge level is updated iteratively using a loop that considers the excess solar electricity generated and limits the charging to the battery's maximum capacity.

# Step (v): Calculating Electricity Bought with Battery
The electricity bought when using the battery is calculated by subtracting the excess solar generation from the previously calculated electricity bought. This accounts for the electricity stored in the battery that can be used instead of buying from the provider.

# Step (vi): Calculating Savings from Installing a Battery
To quantify the potential savings from installing a battery, the project calculates the cost difference between buying electricity from the provider without a battery and buying electricity with a battery. The electricity price is assumed to be $0.17 per kWh.

# Step (vii): Data Aggregation and Visualization
The project aggregates the data on a monthly basis to provide a broader perspective. The aggregated values include total solar generation, electricity usage, electricity bought without a battery, and electricity bought with a battery. This aggregated data is then visualized using a bar plot, with each month represented on the x-axis and the respective values on the y-axis.

# Conclusion
This project demonstrates the process of analyzing solar electricity generation, electricity usage, and battery usage data. It showcases various data manipulation techniques, calculations, and data visualization methods using Python and its libraries. The results provide insights into the potential benefits of utilizing a battery system to store excess solar electricity, leading to potential cost savings and increased energy efficiency.
