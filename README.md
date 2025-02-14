# Investment Insights: A Comprehensive Analysis

## Table of Contents
1. [Project Overview](#Project-Overview)  
2. [Objectives](#objectives)  
3. [Beneficiaries](#beneficiaries)  
4. [Data Used](#data-used)  
5. [Dashboard](#dashboard)  
6. [Key Questions](#key-questions)  
7. [Task 1: Data Overview](#task-1-data-overview)  
8. [Task 2: Gender Distribution](#task-2-gender-distribution)  
9. [Task 3: Descriptive Statistics](#task-3-descriptive-statistics)  
10. [Task 4: Most Preferred Investment Avenue](#task-4-most-preferred-investment-avenue)  
11. [Task 5: Reasons for Investment](#task-5-reasons-for-investment)  
12. [Task 6: Saving Objectives](#task-6-saving-objectives)  

## Project Overview 
In this project, I aim to analyze an investment dataset to uncover valuable insights that can guide decision-making for potential investors. The dataset includes various financial metrics and historical data points related to different investment opportunities.

## Objectives:
•	**Data Overview**: To Understand the dataset structure.

•	**Gender Distribution:** Visualize gender distribution in the dataset.

•	**Descriptive Statistics:** Present basic statistics for numerical columns.

•	**Most Preferred Investment Avenue:** Identify the most preferred investment avenue.

•	**Reasons for Investment:** Analyze and summarize reasons for investment choices.

•	**Saving Objectives**: Identify and present main savings objectives.

•	**Common Information Sources**: Analyze common sources participants rely on for investment information.

•	**Investment Duration:** Calculate the average investment duration.

•	**Expectations from Investments:** Summarize participants' expectations from investments. 

•	**Correlation Analysis:** Explore potential correlations between factors.

## Beneficiaries:
The insights from this analysis will benefit individual investors, financial advisors, and investment firms by providing data-driven recommendations to enhance investment strategies.

## DATA USED
- <a href="https://github.com/Nkemjika123/Cognifyz-Business-Analysis/blob/main/nkem-analyzed_cognifyz_intern_project_data.csv">Dataset</a>

## DASHBOARD 
- <a href="https://github.com/Nkemjika123/Cognifyz-Business-Analysis/blob/main/princessnkemjikaovuonmhen_Intern_Dashboad.pbix">Dashboard</a>

## Key Questions
1.	What are the demographic characteristics of the investors?
2.	Which investment avenues are most popular, and why?
3.	What are the primary reasons for choosing certain investments?
4.	What are the main objectives behind saving and investing?
5.	Where do investors typically get their information?
6.	What is the average duration of investments, and what factors influence this?
7.	What expectations do investors have from their investments?
8.	Are there any significant correlations between demographic factors and investment behavior?

## TASK 1: DATA OVERVIEW
 ### Data Cleaning
•	I imported the data with Pandas on Python.

•	No missing values 


I performed a descriptive statistics  to check the data informations

![Screenshot 2025-01-18 011427](https://github.com/user-attachments/assets/51a23cb9-bfba-44e8-95cf-65a0a291de2e)

**The above analysis shows that there are 40 entries, the data types and 24 columns**.


## TASK 2: GENDER DISTRIBUTION

<img src="https://github.com/user-attachments/assets/0226bf56-372b-4d58-b0cd-0a037561b311" width="400" height="250" alt="Image">

*The above bar chart shows that Male has higher distribution of 25 more than Female with 15 count distribution*.


## TASK 3: DESCRIPTIVE STATISTICS
I noticed the dataframe selected has a non-numeric data in it, which can cause issues when trying to calculate statistical measures like mean, median, and standard deviation. 

I first selected only numeric datas, 
Then I calculated descriptive statistics 

![Screenshot 2025-01-18 022031](https://github.com/user-attachments/assets/a95d73ca-90cb-4707-8bbf-1dc16d18b12f)


## STEP 4: MOST PREFERRED INVESTMENT AVENUE.

<img src="https://github.com/user-attachments/assets/2b791188-0c2d-4882-8abd-be833d82da09" width="400" height="250" alt="Image">

*The above Pie Chart shows that the most preferred investment avenue is Mutual Funds with 45% frequency.*


## TASK 5: REASONS FOR INVESTMENT

![Screenshot 2025-01-18 194554](https://github.com/user-attachments/assets/8a0503db-7005-4828-a7a2-27716235265c)


*The analysis above shows the reasons for each investment avenue based on the unique values,*

1. **Equity:**
   - Capital Appreciation: Investors are looking to increase the value of their investment over time.
   Dividend: Investors are interested in receiving regular income through dividends.
   Liquidity: The ability to quickly convert investments into cash is a priority.

2. **Mutual Funds:**
   - Better Returns: Investors are seeking higher returns compared to other investment options.
   Tax Benefits: There are advantages related to tax savings.
   Fund Diversification: Investors value spreading risk across various assets.

3. **Bonds:**
   - Safe Investment: Bonds are perceived as a secure investment choice.
   Assured Returns: Investors are attracted to the predictability of returns.
   Tax Incentives: Bonds offer certain tax-related benefits.

4. **Fixed Deposits (FD):**
   - Fixed Returns: Investors appreciate the certainty of returns.
   High Interest Rates: The appeal of earning higher interest rates.
   Risk-Free: FDs are considered a low-risk investment option.

*These summaries highlight the key motivations for choosing each investment type, reflecting the diverse priorities and goals of investors.*


## TASK 6: SAVING OBJECTIVES
![Screenshot 2025-01-18 195010](https://github.com/user-attachments/assets/b7f47ded-7741-40d8-a548-5a0f9092087e)

*The above analysis shows that the saving objectives based on this three unique values:*

1. **Retirement Plan:**
   - This objective focuses on accumulating funds to ensure financial security and stability during retirement years. It involves long-term savings to maintain a comfortable lifestyle after leaving the workforce.

2. **Health Care:**
   - Saving for health care aims to cover medical expenses, including routine check-ups, treatments, and emergencies. This objective ensures that individuals are financially prepared for health-related costs without compromising their financial well-being.

3. **Education:**
   - This objective is about setting aside funds for educational purposes, whether for oneself, children, or other family members. It includes saving for tuition, books, and other educational expenses to support academic goals and opportunities.

*These objectives reflect the diverse priorities individuals have when planning their savings, each addressing a critical aspect of financial planning.*

## TASK 7: COMMON INFORMATION SOURCES 

![Screenshot 2025-01-18 202156](https://github.com/user-attachments/assets/07cb01ad-70cf-42e2-b056-202cded69c9b)

**From the analysis above the common information sources are**

1. Financial Consultants:
   - With a count of 16, financial consultants are the most frequently used source of information. This suggests that many individuals rely on professional advice for financial decisions, valuing personalized guidance and expertise.

2. Newspapers and Magazines:
   - With a count of 14, these traditional media sources are also popular. They provide a wide range of financial news and insights, appealing to those who prefer in-depth analysis and diverse perspectives.

3. Television:
   - With a count of 6, television serves as a moderate source of financial information. It offers visual and auditory content, which can be engaging and accessible for many viewers.

4. Internet:
   - With a count of 4, the internet is the least used source in this list. Despite its vast resources and accessibility, it may be less preferred compared to more traditional or personalized sources.

*This summary highlights the varying preferences for information sources, reflecting how individuals choose to stay informed about financial matters*. 


## TASK 8: INVESMENT DURATION
I noticed that the investment duration data is stored as strings representing ranges so I create a mapping of each range to a representative numeric value. 
•	"Less than 1 year" -> 0.5

•	"1-3 years" -> 2

•	"3-5 years" -> 4

•	"More than 5 years" -> 6

After that, I calculated the mean

![Screenshot 2025-01-18 221608](https://github.com/user-attachments/assets/cc9c2f36-bf34-4e5d-8b77-ec5f2505b258)

The average investment duration of 2.975 years indicates that, on average, investors are holding their investments for just under 3 years. Here's what this could mean and how it might affect a business:

**Interpretation:**
1. Investor Behavior: This average suggests that investors are generally comfortable with medium-term commitments. They might be looking for returns within a few years rather than long-term growth.

2. Market Conditions: The duration could reflect current market conditions where medium-term investments are perceived as optimal for balancing risk and return.

 Business Implications:
1. Product Offerings: As a financial service provider, consider offering products that cater to this medium-term investment horizon, such as bonds or mutual funds with a 3-year maturity since that is what majority are interested in.

2. Marketing Strategy: Tailor your marketing messages to highlight benefits that align with medium-term goals, such as capital appreciation or moderate risk.

3. Customer Engagement: Ensure that communication and support are aligned with the investment lifecycle.

4. Risk Management: Adjust the risk management strategies to accommodate the typical investment duration, ensuring they are prepared for potential market shifts.

## TASK 9: EXPECTATIONS FROM INVESTMENTS

The common investment expectations represent the anticipated return on investment (ROI) percentages that investors are hoping to achieve.

It means that,

1. **'20%-30%'**:
   - Investors expect a return of 20% to 30% on their investments. This range suggests a moderate to high expectation for growth, indicating that investors are optimistic about the potential performance of their investments.

2. **'10%-20%'**:
   - This range reflects a more conservative expectation, where investors are looking for a 10% to 20% return. It suggests a balanced approach, possibly prioritizing stability and moderate growth.

3. '**30%-40%'**:
   - Investors with this expectation are aiming for high returns, indicating a more aggressive investment strategy. They might be willing to take on more risk for the potential of higher rewards.

![Screenshot 2025-01-18 225442](https://github.com/user-attachments/assets/8d1fe5bd-c49e-4a26-9e0c-23c71e8b47b5)

If most investors are targeting a '20%-30%' return, it could also mean that majority of the investors does not really trust the investment. This is how it might affect the business and recommendations:

### **Trust and Perception**

1. **Perceived Risk**:
   - Investors might perceive the investment as having moderate risk, which could mean they are not fully confident in its stability or potential for higher returns. This cautious approach might stem from past market volatility or economic uncertainties.

2. **Building Trust:**
   Businesses can focus on building trust by providing transparent information about investment strategies, risks, and historical performance. This can help reassure investors and potentially increase their confidence in aiming for higher returns.

3. **Enhanced Communication:**
   Regular updates and clear communication about market conditions and investment performance can help alleviate concerns and build stronger relationships with investors.

4. **Risk Mitigation Strategies**:
   Offering products with built-in risk mitigation features, such as diversified portfolios or hedging options, can appeal to investors seeking a balance between risk and return.

5. **Investor Education**:
   Educating investors about market trends, risk management, and the potential for higher returns can empower them to make more informed decisions and possibly adjust their expectations.

*By addressing these trust-related concerns, businesses can enhance investor confidence and potentially encourage a more optimistic outlook.*


## TASK 10: CORRELATION ANALYSIS

|    |    |    | 
|------------|------------|------------|
| <img src="https://github.com/user-attachments/assets/2207bade-55eb-4b3f-8b8f-473b344d9be0" width="400" height="250" alt="Image">  | <img src="https://github.com/user-attachments/assets/624c6411-774c-4083-8cd5-994d6ea0076a" width="400" height="250" alt="Image">  | <img src="https://github.com/user-attachments/assets/fe7edd0d-4cda-4177-af5d-59d71b3ca390" width="400" height="250" alt="Image"> |


**What the Correlation Coefficients Analysis Shows:**

1. **Age and Numeric_Duration (0.051756):**
   - This value is close to 0, indicating a very weak positive correlation between age and investment duration. It suggests that age has little to no impact on how long investments are held.

2. **Age and Numeric_Expected_Returns (-0.089606):**
   - This negative value, also close to 0, indicates a very weak negative correlation between age and expected returns. It suggests that age has a minimal inverse relationship with expected returns, meaning older or younger investors don't significantly differ in their return expectations.

3. **Numeric_Duration and Numeric_Expected_Returns (0.258223)**:
   - This value indicates a moderate positive correlation between investment duration and expected returns. It suggests that as the duration of investments increases, the expected returns tend to increase as well. Investors holding longer-term investments might anticipate higher returns.

**Implications for the Business**

**Targeted Strategies:** The weak correlations with age suggest that age alone may not be a strong factor in determining investment behavior or expectations. Businesses might focus on other factors, like risk tolerance or financial goals, for more targeted strategies.
  
**Product Development**: The moderate correlation between duration and expected returns could guide product offerings, emphasizing longer-term investments for those seeking higher returns.

**RECOMMENDATION**
Focus on offering investment products that align with the 20%-30% return expectation and cater to medium-term durations. Enhance investor education and communication to build trust and address any concerns, potentially increasing investor confidence and engagement.

**CONCLUSION**
- Our analysis reveals that there is a moderate positive correlation between investment duration and expected returns, suggesting that investors who hold their investments longer tend to expect higher returns. However, age does not significantly influence investment duration or expected returns, indicating that other factors may play a more crucial role in investment decisions.

- Invest more on financial consultants, since many individuals rely on professional advice for financial decisions, valuing personalized guidance and expertise.

- Focus more on Mutual Funds beecause this analysis shows that the most preferred investment avenue is Mutual Funds with 45% frequency.


**Thank You**.

*(Princess Nkemjika Ovuonmhen)*




















