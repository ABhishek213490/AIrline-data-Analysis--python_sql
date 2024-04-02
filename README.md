# AIrline-data-Analysis--python_sql
# Airline Data Analysis: Leveraging Python Libraries and SQL Queries

## Project Description

A company, provider of air transportation services, faces profitability challenges amidst regulatory constraints and rising costs. To address this, we're launching an analysis project focusing on optimizing occupancy rates to boost per-seat profitability.

### Objective
The primary objective of this project is to analyze our airline database using Python libraries such as Pandas, NumPy, Seaborn, Matplotlib, and SQLite. We aim to increase the occupancy rate, improve pricing strategy, and enhance customer experience.

# Main Business Challenges

### Stricter Environmental Regulations
The airlines industry is facing increasing pressure to reduce its carbon footprint, leading to the implementation of more stringent environmental laws. These regulations not only raise operating costs but also restrict the potential for expansion.

### Higher Flight Taxes
Governments worldwide are imposing heavier taxes on aircraft as a means to address environmental concerns and generate revenue. This increase in flight taxes has raised the overall cost of flying, subsequently reducing demand.

### Tight Labor Market Resulting in Increased Labor Costs
The aviation sector is experiencing a scarcity of skilled workers, leading to higher labor costs and an increase in turnover rates.

# Approach

## Data Preparation
- The dataset includes multiple tables:
  ![6](https://github.com/ABhishek213490/AIrline-data-Analysis--python_sql/assets/161066148/bc280472-b798-466a-aeaf-60a6a149b735)

- All necessary libraries for data analysis were imported, and SQLite was used to combine all tables into a single database file.
- A connection to the SQLite database was established, and a cursor was created to execute SQL queries.
- Data from each table was fetched and separate dataframes were created for easy access.
- Data cleaning was not required as the dataset contains no duplicate or missing values.

## Exploratory Data Analysis (EDA)
- Important columns from all tables were explored to understand the dataset's characteristics.
- Basic analysis was performed to gain insights such as the number of planes with more than 100 seats, changes in the number of tickets booked and total amount earned over time, and average fare for each aircraft with different fare conditions.
- Findings from the EDA will inform strategies to increase occupancy rates and optimize pricing for each aircraft.
  ### How many planes have more than 100 seats?
  ![Capture6](https://github.com/ABhishek213490/AIrline-data-Analysis--python_sql/assets/161066148/6b5d21dd-9257-4726-b3fa-2613c61bf76a)
  ![image](https://github.com/ABhishek213490/AIrline-data-Analysis--python_sql/assets/161066148/c30dd713-b32a-4436-b977-ef2f9a627f2f)

  ### How the number of tickets booked and total amount earned changed over time?
  ![Capture](https://github.com/ABhishek213490/AIrline-data-Analysis--python_sql/assets/161066148/077585fe-43ef-4634-baa9-379cbec1fde8)

  ![image](https://github.com/ABhishek213490/AIrline-data-Analysis--python_sql/assets/161066148/dd4f9c85-fc85-4e09-a52c-f5643da98ebc)

  ![image](https://github.com/ABhishek213490/AIrline-data-Analysis--python_sql/assets/161066148/e4566041-c910-4492-ac93-ca9aa1933de2)



## Analyzing Occupancy Rate
- By increasing the occupancy rate, we aim to boost the average profit earned per seat and mitigate the impact of the challenges we are facing.
- Strategies will be developed to optimize flight schedules, seating arrangements, and ticket pricing to maximize occupancy.
- 
  ![Capture3](https://github.com/ABhishek213490/AIrline-data-Analysis--python_sql/assets/161066148/e8f6b8bd-3dbd-44ca-b63f-beaccb84d978)

  ![Capture3](https://github.com/ABhishek213490/AIrline-data-Analysis--python_sql/assets/161066148/63d0fbec-eb20-4c23-9664-6b2dc71ef573)

  - Calculations were performed to determine the potential increase in seat Occupancy by 10 %  to increase productivity and total annual turnover.
  


- Revenue streams were analyzed to maximize profitability, considering metrics such as overall income per year and average revenue per ticket.
- This analysis aids in pricing optimization and resource allocation for profitable routes.

## Potential Increase in Total Annual Turnover
- Calculations were performed to determine the potential increase in total annual turnover by giving all aircraft a 10% higher occupancy rate.


### 2. Improve Pricing Strategy
- Develop a comprehensive pricing strategy that considers market changes and customer preferences.
- Pricing models will be analyzed to ensure competitiveness while maintaining profitability.

  ![Capture1](https://github.com/ABhishek213490/AIrline-data-Analysis--python_sql/assets/161066148/4ac41b32-780a-41dd-9aa0-863f09af22af)

  ![image](https://github.com/ABhishek213490/AIrline-data-Analysis--python_sql/assets/161066148/261ca88f-cf10-4c12-844e-6d4fa0c1102d)

## Potential Increase in Total Annual Turnover
- Calculations were performed to determine the potential increase in total annual turnover by giving all aircraft a 10% higher occupancy rate.

  ![Capture4](https://github.com/ABhishek213490/AIrline-data-Analysis--python_sql/assets/161066148/d77c3536-4a86-42d6-ad22-e5ff72160cc9)

- By increasing the occupancy rate, we aim to boost the average profit earned per seat and mitigate the impact of the challenges we are facing.
  Strategies will be developed to optimize flight schedules, seating arrangements, and ticket pricing to maximize occupancy.


### 3. Enhance Customer Experience
- Focus on providing a seamless customer experience from booking to boarding.
  ![Capture7](https://github.com/ABhishek213490/AIrline-data-Analysis--python_sql/assets/161066148/b15305fb-0a80-4b0a-9807-5b6777898e38)

  ![image](https://github.com/ABhishek213490/AIrline-data-Analysis--python_sql/assets/161066148/060d38cd-127d-4055-9b1a-06603caea832)

Based on the provided data, it is apparent that the aircraft type 319 has the highest average pricing in the Business category. However, the SU9 aircraft has the highest number of tickets booked. Despite the fact that the average pricing for Economy class in SU9 is relatively low, the number of booked tickets is the highest. This suggests that the SU9 aircraft is providing superior services to customers, leading to maximum revenue generation. Other aircraft types should prioritize enhancing customer experience and adjusting pricing strategies to increase revenue.

### Main Goal
- The main goal of this study is to identify opportunities to increase the occupancy rate in order to boost the average profit earned per seat.

## Conclusion
To summarize, analyzing revenue data such as total revenue per year, average revenue per ticket, and average occupancy rate per aircraft is critical for airlines to maximize profitability. Airlines can find areas for improvement and modify their pricing to reflect the result of these indicators. A greater occupancy rate is one important feature that can enhance profitability by generating more revenue while minimizing operational costs associated with vacant seats.

The airline should revise the price for each aircraft as keeping the price too low or too high drives customer ticket purchasing behavior. They should decide on a reasonable price as per the facilities offered and the condition of the aircraft.
