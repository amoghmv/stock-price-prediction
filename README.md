## **EDA AND EXPLORATORY ANALYSIS (SQL QUERIES)**
The iPhone is the primary revenue driver for Apple, representing over 50% of the company's total revenue. Though, the iPad and Mac account for 18% of its revenue, It is significantly less than what iPhone accounts for.
- **Apple stock is heavily influenced by iPhones than Mac and iPad developments**
1. **FINDING THE DATE RANGE OF THE DATASET**
--> 
![SQL query result showing minimum date as January 3, 2017, and maximum date as December 12, 2022, indicating the dataset date range for Apple stock data](<MySQL Workbench 18-09-2025 09_37_57.png>)
- The minimum and maximum date range in this dataset is **3rd Jan 2017** to **12th Dec 2022** 
- We won't be considering anything less than this date range. For some modelling tasks, we may consider 
- date ranges beyond 2018 and 2021.

2. **FINDING THE MAXIMUM AND THE MINIMUM TRADING VOLUME FOR 2022**
--> 
![SQL query output showing Apple’s minimum trading volume at 188,024 shares and maximum trading volume at 4,110,100 shares for the year 2022](<MySQL Workbench 18-09-2025 09_52_07.png>)
The minimum trding volume is 188024 shares and the maximum is 4110100
These values highlight the variability and volatility of the stock

3. **AVERAGE TRADING VOLUME BY MONTH**
-->
![Monthly average trading volume for Apple stock in 2022, showing peak and low months, highlighting market activity around iPhone SE 3rd gen and iPhone 14 launch](<MySQL Workbench 18-09-2025 10_18_50.png>)
During this year (2022), Apple launched the **iPhone SE 3rd Generation**. 

The reason why we see a negative reaction of the stock is because the phone had mixed opinions.
--The phone **had a button** (people were used to seeing the IPhone X without the button), the phone had no **face ID**,
the phone was very much **cheaper** than their flagships.
--iPhone 13 was looked at as a better option than the IPhone SE 3
--Jumping to **Aug-Sep**, **IPhone 14** was announced in **August** and was launched in **September**. We see a good increase in the stock volume during the month of August

#### **But why the volume drop during October**
--Apple had to cut back production of **IPhone 14** and **IPhone 14 Plus** models due to **weaker demand**
--Raised **doubts** about Apple's product strategy
--Moreover, there were economic conditions like **inflation, recession fears and global uncertanities**

4. **LOWEST AND HIGHEST CLOSING PRICE FOR 2021 AND 2022**
-->
![Yearly average Apple stock closing prices showing $144.66 in 2021 and $132 in 2022, illustrating price rise in 2021 followed by a dip in 2022](<MySQL Workbench 18-09-2025 10_54_21.png>)
The **closing share price** in 2021 was higher than compared to 2022.

#### **Why is that the case?**
--The IPhone 13 was widely **more popular** than the newer models - IPhone 14 and IPhone 15
--Even in 2025, IPhone 13 has a market share of 16.03%, that's pretty good for an older IPhone
--**IPhone 14** was a dissappointment overall, only the flagship **Pro and Pro Max models** saw a **rise in sales** enough to compete with the IPhone 13
--As IPhone 13 went down in price as newer models released, fearing recession and global economic uncertanity, people saw IPhone 13 as a **value for money** phone

5. **RETURNS (%) THROUGHOUT ALL WEEKDAYS OF A YEAR**
-->
![Table of average daily percent returns for Apple stock by weekday in 2021 and 2022, showing negative returns on Mondays and Fridays and positive returns midweek](<MySQL Workbench 18-09-2025 11_47_45.png>)
Apple’s stock dipped on Mondays and Fridays, while mid-week days (especially Thursday) saw better average daily gains in 2022

### **Why?**
--Investors may react to news or events that occurred over the weekends. The more negative sentiment builds up, the more the stock reacts - either negatively or positively
--Some traders sell shares on Friday's to avoid exposure to weekend news risks
--Behavioral finance shows investors behave differently on specific weekdays based on risk tolerance, liquidity needs, and scheduled news releases
--Weekdays are more nuanced as investors behave more based on emotions, compared to an algorithm that exploits this

**In my opinion, weekdays are the thriving days for an algorithm (might dive into this in a future blog)**

6. **AVERAGE CLOSING PRICE FOR YEARS 2020-2022 AND DIFFERENCE BETWEEN THEM**
-->
![Yearly average closing price of Apple stock from 2020 to 2022 with calculated year-on-year differences, showing a strong rise in 2021 and decline in 2022](<MySQL Workbench 18-09-2025 12_05_46.png>)
Apple stock showed a massive closing price increase in 2021, but then dipped back in 2022

#### **What might be the case?**
--One plausible explanation is the **release** of iPhone 13, Apple saw a very **positive response** from consumers
--Investors liked Apple's product strategy and started putting money
--In 2022, iPhone 14 released, didn't see much popularity. Prices dropped, maybe due to **market correction**?

