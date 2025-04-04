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

### Productivity 

It is the quantity of good and services produced from each unit of labor. In other words, it is $\frac{Y}{L}$ where $Y$ the country's output and $L$ is the country's labor. Productivity is a key determinant in living standard in a country 

### How is it determined?

There are four things that determines productivity

1. Physical capital per labor, $\frac{K}{L}$
2. Human capital per labor, $\frac{H}{L}$
    - This is average work expreience and education of the labor force
3. Natural resources per labor, $\frac{N}{L}$
4. Technological knowledge $A$

### Production function of output 

$$ Y = A \times F(L,K,H,N) $$
$$ \frac{Y}{L} = A \times F( 1, \frac{K}{L},\frac{H}{L},\frac{N}{L})$$

The above represents how the four things affect producitivity (output per capita)


### Diminishing returns to scale of capital
<p align="center">
  <img src="Ch12_Returns_scale_capital.png" alt="Ch9_Traiff" width="350">
</p>
Diminishing returns to scale of capital means that as you increase capital while keeping other factors constant, you get less output out of additional increase in capital if you have more of it. 

In the graph, the x-axis represents capital per worker ($\frac{K}{L}$), while the y-axis represents output per worker ($\frac{Y}{L}$). At low levels of $\frac{K}{L}$ (green), increasing capital leads to large gains in output per worker ($\frac{Y}{L}$). However, as $\frac{K}{L}$ increases (orange), the curve flattens, meaning each additional unit of capital contributes smaller increases in $\frac{Y}{L}$. This shows that while capital investment boosts output per worker, its effect weakens over time.



### Catch-up effect 

The Catch-Up Effect suggests that poorer countries grow faster than richer ones due to diminishing returns to capital. The curve shows that at low levels of capital, additional investment leads to large output per worker gains, whereas at higher levels, the gains diminish. This explains why countries with low initial capital grow faster as they benefit more from investment. 

- Example: In the 1960s, South Korea was a relatively poor country with low K/L and Y/L. However, due to high savings, investment in education, and technology adoption, its economy grew rapidly, catching up to more developed countries like the U.S. and Japan. By investing in capital (factories, infrastructure, human capital, etc.), Korea experienced high returns on investment, similar to the green section in the graph. Over time, as K/L increased, its growth rate slowed, following the trend shown in the graph.

---
## Savings, Investment & the Financial System

### Stock

Stock are claim of partial ownership of a firm (think Shark Tank and the entrepreneurs giving away a percent of their company). People sell stocks to raise money and this fund raising is called **equity finance**. The price of a stock (for example, in Wall Street) is determined by supply and demand of the stock. 

Finally, **stock exchange** are places where stocks are traded but a **stock index** is just a place that list the prices of stock. 

### Bonds 

These are a certificate of indebtedness. This means that if you have bonds in a company, the company has to pay to first. When people sell bonds to raise money it is called **debt finance**. There are four things that characterizes a bond. 

1. **Term**: length of time until the bond matures
    - Long term bonds: riskier, higher interest
2. **Credit risk**: probability of borrower default
    - High probability of default: higher intere
3. **Tax treatment**: way the tax laws treat the interest earned on the bond
    - Municipal bonds (issued by state and local governments): no tax, lower interest rates
4. Does it offer **inflation protection**?
    - Indexed to a measure of inflation: when prices rise, the payments rise proportionately
    
### Savings 

Remember that GDP is $Y=C+I+G+NX$. Assume that we have a closed economy, i.e. $NX=0$. 

No rearranging gives us $$ I = Y - C - G $$

We assume that investment is equals national savings so $$ \text{National Savings} =  Y-C-G $$

Performing additional basic algebra below, where $T$ is taxes, we get, 

<p align="center">
  <img src="Ch13_Private_Public_Savings.png" alt="Ch9_Traiff" width="300">
</p>

So, if $\text{Public Savings} = T-G>0$, we have a surplus and if $\text{Public Savings}=T-G<0$, we have a deficit.

### Market for loanable funds

Please review from the slides

---
## Unemployment

### Types of People 

There are four types of people in the economy

1. **Employed** : People who have a job (even part time job)
2. **Unemployed** : People who do not have a job but were looking for a job in the past four weeks 
3. **Out of the labor force**: People who do not have a job but were **not** looking for a job in the past four weeks
    - Example, Retired folks, students, new mothers, discouraged workers (Folks who like to have a job but gave up searching for jobs)
4. **Children**: People below the age of 16

### Formulas and Definitions 

$$ \text{Labor Force} = \text{Number of Employed}+ \text{Number of unemployed}$$
$$ \text{Unemployment Rate} = \frac{\text{Number of unemployed}}{\text{Labor Force}}*100 $$
$$ \text{Labor-Force Participation Rate} = \frac{\text{Labor Force}}{\text{Adult Population}}*100 $$

### Types of unemployment 

There are three types of unemployment 
1. **Frictional unemployment**: Short term unemployment that occurs because it takes time to look for jobs (in-between jobs unemployment) 
2. **Structural unemployment**: Occurs because of there are insufficient jobs available
3. **Cyclical unemployment**: Unemployment that occurs due to seasonal or recession related downturns; for example, Mall Santa Clause

### Structural unemloyment: A closer look into unions and minimum wage
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

- Why? To ensure they have enough cash on hand to meet withdrawal demands from customers. This requirement helps maintain stability in the banking system, preventing issues like bank runs, where too many people try to withdraw money at once. It also allows central banks to control the money supply and regulate economic activity.
- Example: During the 2008 financial crisis, banks like Lehman Brothers and Washington Mutual didn’t have enough reserves because they had invested heavily in risky assets, like mortgage-backed securities. When the housing market collapsed and customers began fearing for their money, they rushed to withdraw their deposits. Because these banks didn’t have enough cash reserves to meet the demand, they faced insolvency, leading to their collapse. This highlights the importance of reserve requirements, which ensure banks have enough liquidity to handle withdrawals and maintain stability in times of financial stress.
    
Reserve Ratio

- Fraction of deposits that banks hold as reserve 
- Percent of total deposits that banks have to hold as reserve 
    
Useful formulas 

$$ \text{Reserve}=\text{Demand Deposits}-\text{Loans}$$
$$ \text{Required Reserve}=\text{Demand Deposits}\times\text{Reserve Ratio} $$


#### Changes in Money Supply 

Money vs Wealth: Bank make loans from their deposits to create money but it does not create wealth 
- Money Multipliers
$$ \text{Money Multiplier}=\frac{1}{\text{Reserve Ratio}} $$

Inutition: The money multiplier shows how banks can create more money through lending.

For example, if you deposit 1,000 dollars and the reserve ratio is 10%, the bank must keep $100 in reserve and can lend out 900 dollars. The borrower spends the 900 dollars, which gets deposited in another bank, and that bank lends out 90% of the deposit again.

This process repeats, and the total money created can be calculated as:

$$ \text{Money Multiplier}=\frac{1}{\text{Reserve Ratio}} = \frac{1}{10 \text{ percent}}=\frac{1}{0.1}=10 $$

So, an initial deposit of 1,000 dollars could create up to 10,000 dollars in total money but the wealth is still only 1,000 dollars.

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
