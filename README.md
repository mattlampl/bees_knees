# To Bee or Not To Bee
![Apis_mellifera_Western_honey_bee](https://user-images.githubusercontent.com/13319538/206924122-beefe2c5-5185-4278-93f0-52ddfaaee572.jpg)


## How to navigate this repo:
**All cleaned data is already uploaded to this repo. You may skip the first step and move straight to `02 - ML and Simulation Models`**

### 01 - Data Cleaning and Feature Generation
*All data cleaning, imputation, feature generation, and merging taks*

### 02 - ML and Simulation Models
*ML modelling and Simulation tasks*

### 03 - Report and Documentation
*Final report, presentation, and any supporting documentation*

### 04 - Data
*Cleaned datasets used for ML and Simulation models*

---
**Our question**: To what extent do factors such as the usage of various pesticides, rainfall, temperature, and more impact the number of honeybee colonies as well as honey yield? In modeling honeybee colony decline, can we effectively predict and simulate honeybee production in a given state and/or region? 


**Why our question is interesting**: In recent decades, the number of honey bees has significantly declined, a phenomenon called colony collapse.[1] Researchers have identified many reasons for this decline, among them habitat loss,[2] usage of harmful pesticides,[3] and infectious diseases.[4] Declining populations pose a huge threat to the food system: honeybees pollinate roughly one-third of all food eaten by Americans,[5] including crops ranging from pumpkins to cranberries to almonds.[6] Our project will analyze honeybee data from 1998 to 2017 to determine the causes and trends of honey bee population decline. Our findings will allow us to formulate effective policy interventions to strengthen hives, ensuring long-term viability in the American food system. 


**Why our question is challenging**: Finding, cleaning, and joining data will pose a challenge. While our primary source includes data on honey production and the number of bee colonies, it is not a rich source of feature data: e.g., temperature, rainfall, level of urbanization, and more. In addition, as described above, researchers have identified a multitude of factors that impact honeybee populations, which further adds complexity. Thus, there are many components to consider, requiring that we have a wide array of feature data to build effective models.


**Analytical Methods**: We will complete two main analyses to address our research questions: 
1. Prediction: Predict the number of honeybees and level of honey production in a given state and/or region
   1. Methods: Regression (Ridge, LASSO, linear, polynomial); Regression Trees
2. Simulation: Simulate random events that affect our prediction model – e.g., pesticide drift, severe weather
   1. Methods: stochastic sampling of continuous distributions, Monte Carlo method for discrete events

	
**Relevance to course**: Our project leverages advanced quantitative methods to address a fundamental problem: long-term food security. Without honeybees, the food system in the US would collapse, one-third of the American diet vanishing. We will leverage techniques and skills we have gained in this course – such as regression, CART, and simulation – to answer our research questions. Our project aligns with the timeline of the course because we will have learned the skills and tools necessary to complete the project prior to the final deadline.
________________
[1] EPA, "Pollinator Protection: Colony Collapse Disorder." 
[2] Dhruba Naug, "Nutritional stress due to habitat loss may explain recent honeybee colony collapses.
[3] EPA, "Pollinator Protection: Colony Collapse Disorder." 
[4] Lewis J. Bartlett, et al, "Persistent effects of management history on honeybee colony virus abundances.”
[5] Ibid. 
[6] FDA, "Helping Agriculture's Helpful Honey Bees."
