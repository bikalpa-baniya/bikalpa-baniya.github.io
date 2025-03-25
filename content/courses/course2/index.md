---
title: "Econ 2020: Principles of Macroeconomics - Recitation Materials" 
date: 2025-01-09
lastmod: 2025-01-10
tags: ["Macroeconomics"]
author: ["Bikalpa Baniya"]
description: "Recitation Materials for Principles of Macroeconomics" 
summary: "These materials are my recitation materials for Econ 2020: Principles of Macroeconomics" 
cover:
    image: "macroeconomics.jpg"
    alt: "Principles of Macroeconomics"
    relative: false
editPost:
    URL: "https://bikalpa-baniya.github.io/courses/course2/"
    Text: "Course portal"
showToc: true
disableAnchoredHeadings: false

---

 The following notes are based on Mankiw, *Principles of Macroeconomics*, 10th Edition

---
## Thinking Like an Economist
- Economics is about trade-offs
- Opportunity Cost: It is defined as the value of the next best alternative. It is the value you forgo when you make a choice.
  
### Production Possibility Frontier (PPF)

- The following is the PPF for a country that only produces oil and cars. 

<p align="center">
  <img src="Ch2_PPF.png" alt="Ch2_PPF" width="400">
</p>

- Production efficiency means that there is no way to produce more of one good without producing less of other goods
- A: Amount of oil produced if the country only produces oil
- B: Amount of cars produced if the country only produces cars

### Opportunity cost and PPF

#### Question:  What is the opporunity cost of going from point C to D? 

<p align="center">
  <img src="Ch2_PPF_OC.png" alt="Ch2_PPF" width="400">
</p>

STEP 1: Equate production if the country only produced either of the good (i.e. $A=B$)

$$ 50 \text{ mil barrels of oil} = 30 \text{ hundred thousand cars}$$

STEP 2: Since we are increasing the production of cars make the right hand side 1
$$ \frac{50}{30} \text{ mil barrels of oil} = 1 \text{ hundred thousand cars}$$

STEP 3: Car production increases by $15-9=6$ so make the right hand side 6 by multiplying both sides by 6

$$ \frac{50}{30}*6 \text{ mil barrels of oil} = 6 \text{ hundred thousand cars} $$
$$ \Leftrightarrow 10 \text{ mil barrels of oil} = 6 \text{ hundred thousand cars} $$




So, moving from C to D requires giving up 10 mil barrels of oil. 

### Additional notes: 
- Economic growth results in the PPF shifting outwards
- Shape of PPF
    - If the PPF is a straight line the opportunity cost is constant
    - If the PPF is bowing outwards the opportunity cost in increasing
    - If the PPF is bowing inwards the opportunity cost in decreasing
### Positive statement vs Normative statement

- Positive statement - Statement that are testable
    - Example: The unemployment rate is 4%
- Normative statement - Statement that are based on opinions
    - Example: The unemployment rate should be 0%

---
## Interdependence & Gains from Trade

### Comparative Advantage vs Absolute Advantage

- Absolute advantage
    - A country (individual) has an absolute advantage if it can produce more good or service than others
    - Absolute advantage has nothing to do with gains from trade 
- Comparative advantage
    - A country (individual) has an comparative advantage if it can produce a particular good or service with lower opportunity cost
    - In other words, they have to give up less to produce this good
    - Gains from trade are based on comparative advantage

### Calcuating Comparative Advantage

Conside two countries that produce either iPhones or video games. The following table shows the number items one person can produce. Suppose that USA and China have 100 and 200 people available to work respectively. 

<div align="center">

|           | Video Games      | iPhones  |
|-----------|-----------   |-----------   |
| USA       | 12           | 24           |
| China     | 8            | 32           |

</div>


#### Question: Which country has the comparative advantage in producing video games?

<button onclick="document.getElementById('solution').style.display='block'"><span style="color: blue;">Show Solution</span></button>

<div id="solution" style="display:none;">
STEP 1: Equate production if the country only produced either of the good

- USA
$$ 12 * 100 \text{ Video Games} = 24 * 100\text{ iPhones}$$
- China
$$ 8 * 200 \text{ Video Game} = 32 * 200\text{ iPhones}$$


STEP 2: Since we are interested in the opportunity cost of video games, make the left hand side 1. 

- USA
$$ 1 \text{ Video Game} = \frac{24 * 100}{12*100}\text{ iPhones}$$
$$ \Leftrightarrow 1 \text{ Video Game} = 2 \text{ iPhones}$$
- China

$$ 1 \text{ Video Game} = \frac{32 * 200}{8*200}\text{ iPhones}$$
$$ \Leftrightarrow 1 \text{ Video Game} = 4 \text{ iPhones}$$

STEP 3: Find out which country has the smaller opportunity cost (or who has to give up less). In this case it is the USA. So, USA has the comparative advantage in producing video games. 

Note: If you are trying to find which country has the comparative advantage in producing iPhones, step 1 and 3 are identical and you just have to make the right hand side 1 in step 2. 

</div>






### Gains from Trade 

Main idea: Trade allows countries to consume at a level in the PPF that is otherwise infeasible. This requires that each country only produce the good in which they have comparative advantage. 

See Chapter 3 Question 3 


---
## Application to International Trade

### Consumer and Producer Surplus 

<p align="center">
  <img src="Ch9_CS_PS.png" alt="Ch9_CS_PS" width="800">
</p>

$$\text{Total Surplus }=\text{ Consumer Surplus }+\text{ Producer Surplus }$$

To calculate the numeric value for the surplus use the area of the triangle formula 
$\frac{1}{2} * \text{Base} * \text{Height}$

### Surplus and Gains from Trade when World Price $P_W$ is different than Domestic Price $P_D$

<p align="center">
  <img src="Ch9_Domestic_World_Price.png" alt="Ch9_Domestic_World_Price" width="800">
</p>

Things to note
<div align="center">

|                        | **$P_W > P_D$** | **$P_W < P_D$** |
|:----------------------:|:----------:|:----------:|
| **Direction of Trade** |  Export   |  Imports   |
| **Consumer Surplus**   |   Falls    |   Rises    |
| **Producer Surplus**   |   Rises    |   Falls    |
| **Total Surplus**      |   Rises    |   Rises    |
| **Who gets the Gains from Trade**      |   Producers   |   Consumers    |

</div>



### Tariffs

<p align="center">
  <img src="Ch9_Traiff.png" alt="Ch9_Traiff" width="800">
</p>
Things to note

- Tariff causes the World Price $P_W$ to increase
- If the country was importing 
    - The new import is going to be smaller
    - The consumer surplus is going to decrease but the producer surplus will increase 
    - There is Deadweight Loss (DWL) from the traiffs



---
## Measuring a Nation's Income

### Gross Domestic Product (GDP)

GDP is the total value of all goods and services produced within a country. It is used to capture the overall health of the economy. 

It includes the following
- Goods and services produced legally in the country 
- Final good 
    - For example, a car that is sold to a consumer not the intermediate goods such car engines or other body parts
- Year $X$ GDP only includes value procuded in year $X$ and not the value produced in the prior years, regardless of when the good was consumed. 
- Tangible goods (like food, mountain bikes, beer) and intangible service (dry cleaning, concerts, haircuts)

GDP excludes
- Goods and services produced at home or illegally 
- Intermediate goods 
    - These are not included to avoid double counting. For example if you include both the final car and the car engines, you end up counting this value twice
- Value of goods produced in other year
- Goods that produced in another country but not imported

** In short, GDP includes value the government can $accurately$ measure $within$ the $entire$ country in a $given$ $time$. **

### 
The formula of GPD is 
$$ GDP = C + I + G + Ex - Im $$

where
- $C$ is consumption 
- $I$ is investment
- $G$ is government expenditure 
- $Ex$ is the nation's export 
- $Im$ is the nation's import 

Notes about the components
- $C$ includes spending by households on good and service but excludes the purchase of the house itself because it might be "produced" in a different year 
- $I$ includes spending on goods that will be used to produce future goods (like inventory) but excluded spending on financial assets
- $G$ includes spending on the goods and services purchased by the government but excludes tranfer of payments like unemployment insurance benefits
- $Ex$ increases GDP while $Im$ decreases GDP 

### Real vs Nominal GDP 
Nomial GDP is the total value of goods and service **not corrected** for inflation while Real GDP is the value of goods and service **corrected** for inflation.
- For base year Nomial GDP $=$ Real GDP

### GDP deflator and Inflation Rate

GDP deflator is given by 

$$ \text{GDP Deflator}=100 * \frac{\text{Nominal GDP}}{\text{Real GDP}} $$

The inflation rate between year $X$ and year $Y$ (where $X>Y$) is given by 
$$   \text{Inflation Rate}=100 * \frac{   \text{GDP Deflator at year X}- \text{GDP Deflator at year Y}  }{ \text{GDP Deflator at year Y} }  $$



---
## Measuring Prices & Cost of Living

### Basket of Goods
The government wants to see how expensive things are getting in the economy every year. To do so in a standardized way, the BLS identifies a "basket of goods" a typical consumer buys and compares the total cost of this basket over time. (See [here](https://www.bls.gov/cpi/questions-and-answers.htm) for the things that are included in this basket)


### CPI and Inflation Rate
Once we find the total cost of a basket for different years, we can see how expensive things are getting using the Consumer Price Index (CPI) and Inflation rate. There are other measures but these two are the most popular. 

The formula for CPI is 
$$CPI = \frac{\text{Basket Cost in Current Year}}{\text{Basket Cost in Base Year}}$$


The inflation rate between year $X$ and year $Y$ (where $X>Y$) is given by 
$$   \text{Inflation Rate}=100 * \frac{   \text{CPI in year X}- \text{CPI in year Y}  }{ \text{CPI in year Y} }  $$



### CPI vs GDP Deflator
In short, CPI measures how expensive things are getting for the **consumer** and the GDP Deflator measures how expensive things are getting for the **producers**.

- Note that things that affect both the consumers and the producers are included in both measures. For example, rise in the price of textbook affects both consumers (consumer now buy less) and produces (sellers now produce more due to rise in profit margins). So, it is included in both measures.

### Comparing Prices from different times

Comparing nominal dollar amounts across different times is not a fair comparison because the value of these amounts differs. For example, the value of 100K wage in 2025 is not the same as the value of a 100K wage in 1980. To make a fair comparison we need to convert prior year amounts to base year.

Let $X$ be the base year and $Y$ be the prior year. The conversion formula is 

$$   \text{Amount in year $X$ dollars}= \text{Amount in year $Y$ dollars} * \frac{   \text{Price Index in $X$}  }{ \text{Price Index in $Y$ }}  $$


### Interest Rate

Interest rates are important because it determines the growth in value of your deposit. However, the actual interest rate on your saving might not be the stated nominal interest rate. This is because while nominal interest rate (for example, the rate given by your bank) might increase the value of your savings, the inflation rate will decrease this value through decrease in purchasing power. So, to find the rate the you actually face on your deposit use the following adjustment. 

The real interest rate is given by 
$$\text{Real Interest Rate} = \text{Nominal Interest Rate} - \text{Inflation Rate}$$


---
## Production & Economic Growth
---
## Savings, Investment & the Financial System
---
## Unemployment

### Types of People 

There are four types of people in the economy

1. Employed : People who have a job (even part time job)
2. Unemployed : People who do not have a job but were looking for a job in the past four weeks 
3. Out of the labor force: People who do not have a job but were **not** looking for a job in the past four weeks
    - Example, Retired folks, students, new mothers, discouraged workers (Folks who like to have a job but gave up searching for jobs)
4. Children: People below the age of 16

### Formulas and Definitions 

$$ \text{Labor Force} = \text{Number of Employed}+ \text{Number of unemployed}$$
$$ $$
$$ $$

### Types of unemployment 
1. Frictional unemployment 
2. Structural unemployment 
3. Cyclical unemployment

### Structural unemloyment: A closer look into unions
....

### Theory of Efficieny wages

Firm want to voluntarly pay workers above equilibrium wages to boost recruitment and workers productivity





---
## The Monetary System

### Use of Money 

- Medium of exchange: Purchasing goods or services
    - Liquidity: It refers to how quickly something can be bought or sold in the market  
    - Highly liquid assets: Cash
    - Less liquid assess: Real estate or collectibles
- Unit of account: Comparing value and debts 
- Store of value: Record of purchasing power
 
### Types of Money 

- Commodity Money: Has intrinsic value, for example, Gold coins
- Fiat Money: No intrinsic value but government decrees a value, for example, US dollars

#### Money in the US Economy 

There are two kinds of money in the US economy
1. Currency: Paper bills 
2. Demand Deposits: Balance in bank accounts 

Money Stock: Total amount of money circulating in the economy

- M1 is a narrower more liquid measure of money
    - Currency, Demand deposit, etc. 
- M2: M1 plus other assets that are less liquid 
    - Savings accounts, Time deposit, Money Market Account etc. 

Common Mistake: M2 = M1 + less liquid asset. It is a common mistake to assume M2 is only less liquid asset. 

### The Federal Reserve System (Fed)
- Fed is the central bank of the US
- A central bank is a public institution responsible for managing a country's currency and monetary policy 
- Fed's Job 
    - Regulate Banks: Help banks operates and make loans to banks 
    - Control Money Supply: Control interest rates and other monetary policy 

#### Bank Reserve

Bank have to keep a fraction of their deposits that they cannot loan out 
    - Why? ...........
    
Reserve Ratio
    - Fraction of deposits that banks hold as reserve 
    - Percent of total deposits that banks have to hold as reserve 
    
Useful formulas 

$$ \text{Reserve}=\text{Demand Deposits}-\text{Loans}$$
$$ \text{Required Reserve}=\text{Demand Deposits}\times\text{Reserve Ratio} $$


#### Changes in Money Supply 

- Money vs Wealth: Bank make loans from their deposits to create money but it does not create wealth 
- Money Multipliers
$$ \text{Money Multiplier}=\frac{1}{\text{Reserve Ratio}} $$

Inutition: ..............

### Balance Sheet
A bank's balance sheet is a financial statement that shows the bank's financial position. It helps assess the bank's financial health by providing a snapshot of its assets, liabilities and equity.
- Assets are inflow of funds to the bank and liabilities are the out flow of funds out of the bank
- When you add to assets, you have to add it to liabilities too. You have to figure out where to add it.
- Please review the lecture slides to see examples of balancing a budget

<div align="center">

|          Assets        | Liabilities |
|:----------------------:|:----------:|
| Reserves               |  Deposits  |  
| Loans                  |   Debt     |  
| Securities            |   Capital (Owners's equity)    |  

</div>

  
Leverage ratio measures the financial risk of a bank and shows how much the bank is relying on borrowed money (debt) versus its own capital (equity).
$$ \text{Leverage Ratio}=\frac{\text{Assets}}{\text{Capital}}=\frac{\text{Reserves}+\text{Loans}+\text{Securities}}{\text{Capital}} $$

You can also use the money multiplier to determine the impact of injecting funds into the money supply.

$$ \text{Change in Demand Deposits }=\frac{\text{Initial Depost }}{\text{Required Reserve Ratio}} $$ 
#### Interest Rate and Money Supply 

How can the Fed influence money supply? 

- The Fed can influence the money supply by adjusting the interest rate on loans it provides to banks and other financial institutions.

Example 

- If the Fed lowers the interest rate it charges banks for borrowing money, banks will be more likely to borrow funds. This increases the amount of money available for lending to businesses and consumers, thus expanding the money supply. 

- Conversely, if the Fed raises the interest rate, borrowing becomes more expensive, leading to a decrease in lending and a reduction in the money supply.

---
## Money Growth & Inflation 
---
## Open-Economy Macro: The Basics
---
## Aggregate Demand & Aggregate Supply
---
## Monetary & Fiscal Policies
---
