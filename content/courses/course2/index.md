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
- Opportunity Cost
  - Definition: It is defined as the value of the next best alternative. It is the value you forgo when you make a choice.
---
## Interdependence & Gains from Trade
### Production Possibility Forntier (PPF)

- The following is the PPF for a country that only produces oil and cars. 

<p align="center">
  <img src="Ch2_PPF.png" alt="Ch2_PPF" width="400">
</p>

- Production efficiency means that there is no way to produce more of one good without producing less of other goods
- A: Amount of oil produced if the country only produces oil
- B: Amount of cards produced if the country only produces cars

### Oppoutunity cost and PPF

- What is the opporunity cost of going from point C to D? 

<p align="center">
  <img src="Ch2_PPF_OC.png" alt="Ch2_PPF" width="400">
</p>

Step 1: Equate production if the country only produced either of the good

$$ 50 \text{ mil barrels of oil} = 30 \text{ hundred thousand cars}$$

Step 2: Since we are increasing the production of cars make the right hand side 1
$$ \frac{50}{30} \text{ mil barrels of oil} = 1 \text{ hundred thousand cars}$$

Step 3: Car production increases by $15-9=6$ so make the right hand side 6 by multiplying both sides by 6

$$ \frac{50}{30}*6 \text{ mil barrels of oil} = 6 \text{ hundred thousand cars} $$
$$ \Leftrightarrow 10 \text{ mil barrels of oil} = 6 \text{ hundred thousand cars} $$




So, moving from C to B requies giving up 10 mil barrels of oil. 

Additional notes: 
- Economic growth results in the PPF shifting outwards
- Shape of PPF
    - If the PPF is a straight line the opporunity cost is constant
    - If the PPF is bowing outwards the opporunity cost in increasing
    - If the PPF is bowing inwards the opporunity cost in decreasing
### Positive statement vs Normative statement

- Positive statement - Statement that are testable
    - Example: The unempolyent rate is 4%
- Normative statement - Statement that are based on opinions
    - Example: The unemployment rate should be 0%


---
## Application to International Trade

### Comparative Advantage vs Absolute Advantage

- Absolute advantage
    - A country (individual) has an absolute advantage if it can produce more good or service than others
    - Absolute advantage has nothing to do with gains from trade 
- Comparative advantage
    - A country (individual) has an comparative advantage if it can produce a particular good or service with lower opportunity cost
    - In other words, they have to give up less
    - Gains from trade are based on comparative advantage

### Calcuating Comparative Advantage

Conside two countries that produce either Iphones or video games. The following table shows the number of people required to build one of either. Suppose that USA and China have 100 and 200 people avaiable to work respectively. 


|           | Video Games      | Iphones  |
|-----------|-----------   |-----------   |
| USA       | 12           | 24           |
| China     | 8            | 32           |


#### Question: Which country has the comparative advantage in producing video games?

<button onclick="document.getElementById('solution').style.display='block'"><span style="color: blue;">Show Solution</span></button>

<div id="solution" style="display:none;">
STEP 1: Equate production if the country only produced either of the good

- USA
$$ 12 * 100 \text{Video Games} = 24 * 100\text{Iphones}$$
- China
$$ 8 * 200 \text{ Video Game} = 32 * 200\text{ Iphones}$$


STEP 2: Since we are interested in the opprtunity cost of video Games, make the left hand side 1. 

- USA
$$ 1 \text{ Video Game} = \frac{24 * 100}{12*100}\text{ Iphones}$$
$$ 1 \text{ Video Game} = 2 \text{ Iphones}$$
- China

$$ 1 \text{ Video Game} = \frac{32 * 200}{8*200}\text{ Iphones}}$$
$$ 1 \text{ Video Game} = 4 \text{ Iphones}$$

STEP 3: Find which country has the smaller opportunity cost (or who has to give up less). In this case it is the USA. So, USA has the comparative advantage in producing video games. 
</div>


#### Question: Which country has the comparative advantage in producing Iphones?

<button onclick="document.getElementById('solution').style.display='block'"><span style="color: blue;">Show Solution</span></button>

<div id="solution" style="display:none;">

STEP 1: Equate production if the country only produced either of the good

- USA
$$ 12 * 100 \text{Video Games} = 24 * 100\text{ Iphones}$$
- China
$$ 8 * 200 \text{ Video Game} = 32 * 200\text{ Iphones}$$


STEP 2: Since we are now interested in the opprtunity cost of Iphones, make the right hand side 1. 

- USA
$$\frac{12 * 100}{24*100} \text{Video Games} = 1\text{ Iphones}$$
$$\frac{1}{2} \text{Video Games} = 1 \text{ Iphones}$$
- China

$$ \frac{8 * 200}{32*200} \text{Video Games} = 1 \text{ Iphones}$$
$$\frac{1}{4} \text{Video Games} = 1 \text{ Iphones}$$

STEP 3: Find which country has the smaller opportunity cost (or who has to give up less). In this case it is China. So, China has the comparative advantage in producing Iphones. 
    
</div>



### Gains from Trade 
- Main idea: Trade allows countries to consume at a level in the PPF that is otherwise infeasible. This requires that each country only produce the good in which they have comparative advantage. 
- See Chapter 3 Question 3 

---
## Measuring a Nation's Income



The formula of GPD is 
$$ GDP = C + I + G + Ex - Im $$

,where
- $C$ is consumption 
- $I$ is invesetment 
- $G$ is goverment expenditure 
- $Ex$ is the nation's export 
- $Im$ is the nation's import 


### GDP deflator and Inflation Rate

GDP deflator is given by 

$$ \text{GDP Deflator}=100 * \frac{\text{Nominal GDP}}{\text{Real GDP}} $$

The inflation rate between year $X$ and year $Y$ (where $X>Y$) is given by 
$$   \text{Inflation Rate}=100 * \frac{   \text{GDP Deflator at year X}- \text{GDP Deflator at year Y}  }{ \text{GDP Deflator at year Y} }  $$

---
## Measuring Prices & Cost of Living

### CPI and Basket of Goods
The formula for CPI is 
$$CPI = \frac{\text{Basket Cost in Current Year}}{\text{Basket Cost in Base Year}}$$

### CPI vs GDP Deflator

### Interest Rate

The real interest rate is given by 
$$\text{Real Interest Rate} = \text{Nominal Interest Rate} - \text{Inflation Rate}$$


---
## Production & Economic Growth
---
## Savings, Investment & the Financial System
---
## Unemployment
---
## The Monetary System
---
## Money Growth & Inflation 
---
## Open-Economy Macro: The Basics
---
## Aggregate Demand & Aggregate Supply
---
## Monetary & Fiscal Policies
---
