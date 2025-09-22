# **REST OF THE REPORT STILL PENDING - STOCK PRICE INSIGHTS AND UTILISATION OF PYTHON PLOTS**
## **EDA AND EXPLORATORY ANALYSIS**
The iPhone is the primary revenue driver for Apple, representing over 50% of the company's total revenue. Though, the iPad and Mac account for 18% of its revenue, It is significantly less than what iPhone accounts for.
- **Apple stock is heavily influenced by iPhones than Mac and iPad developments**
## 1. **FINDING THE DATE RANGE OF THE DATASET**
--> 
<img width="269" height="99" alt="image" src="https://github.com/user-attachments/assets/0edd444b-bfd7-4a71-8080-d1393a677999" />

- The minimum and maximum date range in this dataset is **3rd Jan 2017** and **12th Dec 2022** 
- We won't be considering anything less than this date range. For some modelling tasks, we may consider 
- date ranges beyond 2018 or 2021

## 2. **FINDING THE MAXIMUM AND THE MINIMUM TRADING VOLUME FOR 2022**
--> 
<img width="300" height="64" alt="image" src="https://github.com/user-attachments/assets/69ccb1a0-a432-4eb9-9234-fa9191cd2a6c" />

- The **minimum** trding volume is **188,024** shares and the **maximum** is **4,110,100**
- These values highlight the **variability and volatility** of the stock

## 3. **AVERAGE TRADING VOLUME BY MONTH**
-->
<img width="223" height="296" alt="image" src="https://github.com/user-attachments/assets/6ffc52d7-80ce-45a6-a33b-f276a5ecc227" />

**During this year (2022), Apple launched the iPhone SE 3rd Generation and the iPhone 14**. 

- The reason why we see a negative reaction of the stock is because the phone had mixed opinions.
- The phone **had a button** (some people liked it, some didn't, especially after the iPhone X), the phone had no **face ID**,
the phone was much **cheaper** than their flagships.
- iPhone 13 was looked at as a **better option** than the IPhone SE 3 and iPhone 14
- Jumping to **Aug-Sep**, **IPhone 14** was announced in **August** and was launched in **September**. We see a good increase in the stock volume during the month of August

## **But why the volume drop during October**
- Apple had to cut back production of **IPhone 14** and **IPhone 14 Plus** models due to **weaker demand**
- Raised **doubts** about Apple's product strategy
- Moreover, there were economic conditions like **inflation, recession fears and global uncertainties**

## 4. **LOWEST AND HIGHEST CLOSING PRICE FOR 2021 AND 2022**
-->
<img width="492" height="53" alt="image" src="https://github.com/user-attachments/assets/6cf2cfea-c0a4-4a36-b7a2-71ffa58812b1" />

The **closing share price** in 2021 was higher than compared to 2022.

## **Why is that the case?**
- The IPhone 13 was widely **more popular** than the newer models - IPhone 14 and IPhone 15
- Even **in 2025**, IPhone 13 has a **market share of 16.03%**, that's pretty good for an older IPhone
- **IPhone 14** was a **dissappointment** overall, only the flagship **Pro and Pro Max models** saw a **rise in sales** enough to compete with the IPhone 13
- As IPhone 13 went down in price as newer models released, fearing recession and global economic uncertanity, people saw IPhone 13 as a **value for money** phone

## 5. **RETURNS (%) THROUGHOUT ALL WEEKDAYS OF A YEAR**
-->
<img width="330" height="139" alt="image" src="https://github.com/user-attachments/assets/5393d315-f20b-4880-858b-60fc69f583f8" />

Apple’s stock dipped on Mondays and Fridays, while mid-week days (especially Thursday) saw better average daily gains in 2022

## **Why?**
- Investors may react to news or events that occurred over the weekends. The more negative sentiment builds up, the more the stock reacts - either negatively or positively
- Some traders sell shares on Friday's to avoid exposure to weekend news risks
- Behavioral finance shows investors behave differently on specific weekdays based on risk tolerance, liquidity needs, and scheduled news releases
- Weekdays are more nuanced as investors behave more based on emotions, compared to an algorithm that exploits this

## **In my opinion, weekdays are the thriving days for an algorithm (might dive into this deeper in the future)**

## 6. **AVERAGE CLOSING PRICE FOR YEARS 2020-2022 AND DIFFERENCE BETWEEN THEM**
-->
<img width="262" height="99" alt="image" src="https://github.com/user-attachments/assets/349effab-9d65-4dd1-85b2-6fb757d3ff4c" />

Apple stock showed a massive closing price increase in 2021, but then dipped back in 2022

## **What might be the case?**
- One **plausible explanation** is the **release** of iPhone 13, Apple saw a very **positive response** from consumers
- Investors liked Apple's **product strategy** and started putting money
- In 2022, iPhone 14 released, didn't see much popularity. Prices dropped, maybe due to **market correction**?

# **CAUSES OF TRENDS (PYTHON)**
## 7. **CLOSING PRICE TREND**
-->
<img width="695" height="545" alt="image" src="https://github.com/user-attachments/assets/e3435f15-df17-4010-8ef2-f8c20c032bab" />

<img width="850" height="545" alt="image" src="https://github.com/user-attachments/assets/017e61a5-02fe-4711-9491-825dc3b75986" />

The closing stock price started at **$145**, a steady growth trend throughout until **2022**.  
The closing price saw its highest in those sample dates at **$160** before dropping in **2023**.


## **Why?**
- Everything signals it towards being an **iPhone 14** problem and **recession fears**, but is that the only cause for this?  
- In 2022, the **federal reserve interest rates** went up and a rise in **inflation** were the causes as well  
- The market shot up in **2021**, resulted in a **market correction** in **2022**  


## BUT, BUT, some things we haven't touched upon
- **Russia invaded Ukraine** right around this time, impacting the global market  
- **OpenAI's ChatGPT** was released right around this time, a technological disruption  
- Companies overreacted and started **laying off several employees**  
- But, laying off signalled **operational inefficiency**, **future doubts** about the company, and added **geopolitical tension** to the mix, caused a downtrend  


## 8. **DEATH CROSS/GOLDEN CROSS AND MOVING AVERAGES**
-->
<img width="857" height="622" alt="image" src="https://github.com/user-attachments/assets/8a0e646e-6d00-4e1d-b8fe-52bd1e65ca34" />

- Around mid-**2020**, the **50-day MA** crossed above the **200-day MA** briefly as the stock price started a strong upward trend, suggesting a major **bullish momentum**.  
- Near the end of **2021** or early **2022**, the **50-day MA** crossed below the **200-day MA** indicating a **death cross**. This coincided with the price peak and subsequent downtrend in **2022**  
- Early **2023** (or close to end of **2022**) shows the **50-day MA** again crossing above the **200-day MA**, possible new **bullish cycle** hinted?  
- The chart explains how **golden and death crosses** can be **leading indicators** for trend changes. The **50-day and 200-day MA crossovers** matched well with significant price trends in Apple stock over this time.  


## 9. **DAILY RETURNS DISTRIBUTION PLOT**
-->
<img width="650" height="545" alt="image" src="https://github.com/user-attachments/assets/0d820d44-5e19-4a2d-82d7-71e69f21baa7" />

- The central **red box** represents the **interquartile range** (middle 50% of daily returns).  
- The horizontal line inside the box marks the **median daily return**, which is close to zero.  
- Whiskers extend to show the general spread, individual dots are days when returns were much higher or lower than normal.  


## **What does the chart say?**
- Returns are **clutered around 0**, signalling that price movements weren't so **volatile**  
- There are **outliers**, however, tells us that there were occasional major price moves - launch of a **new chip, product, war, recession** etc.  
- But these outliers were more **positive** than negative. The **uptrends** were bigger than the downtrends.  


## 10. **RATE OF VOLATILITY**
-->
<img width="609" height="468" alt="image" src="https://github.com/user-attachments/assets/4fd6f2a9-e886-4644-bd11-3a951615311f" />

- High **volatility** in **2020** can be hinted towards the **pandemic**  
- In **2022**, it was the high **interest rates**, **Russia-Ukraine war**, **recession fears**, **AI disruption**  
- In **2021**, the volatility being low hints towards more stable market movement. As we looked at the closing prices for **2021**, they were not far apart and were partially close. Even around the launch of the **iPhone 13**, the market moved up gradually in terms of share volume  


## 11. **RELATIVE STRENGTH INDEX**
-->
<img width="864" height="699" alt="image" src="https://github.com/user-attachments/assets/0200ac7c-fa32-4faf-acc2-9126f2e1927f" />

- I can't help but connect the dots for **2022** again. **2021 October** saw investors **overselling** their stock  
- It opened up a **buying opportunity** for potential investors. Apple Inc. is considered a very good long term investment by analysts.  
- We could see that, just a month or two later, the stock shot up over an index of **70** again.  
- But ofcourse, investor psychology, it drops back down again. Buy low, sell high, repeat. But such massive changes in index is only explained by other **economic conditions** and not just psychology (the points we discuseed above - **war, AI disruption, layoffs, pandemic, recession fears, etc.**)  

# 12. **LINEAR REGRESSION**
-->
<img width="845" height="680" alt="image" src="https://github.com/user-attachments/assets/acd06249-2852-4c22-a0b3-eb884b02b9da" />

- The **blue** line represents the **actual** observed closing prices.
- The **orange** line represents the model’s **predicted** closing prices.
- Both lines closely follow each other, indicating the model is capturing the **overall trend**, including **rises, drops**, and **volatility**, quite well.
- Minor **deviations** where orange and blue separate show where the model was **less accurate**, often during **sudden large price fluctuation**

# 13. **RANDOM FOREEST REGRESSOR AND MSE**
--> 
**[MSE = 6.12, RFR = 10.89, RMSE = 2.47, MAE = 1.89]**
- The **Mean Squared Error** (MSE) of **6.12** for **Linear Regression** is quite **low** for **volatile stock data**, indicating the model predicts closing prices **close to the actuals**
- The **Random Forest Regressor MSE** is slightly **higher** at **10.89** but **still reflects** decent predictive performance.
- The **Root Mean Squared Error** (RMSE) of about **2.47** means predictions on average **deviate** from actual values by this margin.
- The **Mean Absolute Error** (MAE) around **1.89** further confirms that **predicted closing prices** are within **roughly 2 units** of the true price.

# **Predictions?**
- The Output of **25 days of predicted prices** in a steady **range around 155** shows the **model expects stability or modest growth**
- The values don't mean the price is going to hover around 155, but just means we can expect no big price fluctuations for those days
- However, **blindly trusting models** without your **own intuition** can lead to **bad results**


