---
layout: post
title:  "Titanic"
date:   2013-06-05 17:06:25
categories: jekyll update
---

## The Survivors and Viticms on the Titanic
The Titanic was set to port along the east coast of New York, however, on April 15,1912, more then 1,500 people lost their [lives](https://history.com/topics/titanic). Our objective was to investigate the survivors and vitcims who tragically lost their lives. 

We were given demographics and passenger information from **891** of the **2224** passangers and crew on board [Titanic Data](https://d17h27t6h515a5.cloudfront.net/topher/2016/September/57e9a84c_titanic-data/titanic-data.csv). We wish to ask the question: *what factors made people more likely to survive?* 

If you wish to view our source code for this ```python``` project please click [here](https://github.com/krismanaya/udacity_data_analyst/blob/master/project_2/titanic_src/Titanic%20Project%202%20.ipynb)

## What are the sample metrics? 
The Titanic data allows us to get a sample of the passangers who survived, class, name, sex, age, number of siblings; number of parents/children aboard, ticket number, passanger fare, cabin and where they embarked. Of the **891** passengers aboard we found that **38%** of passangers survived on the titanic at an average age of **24** years old. Mostly the survival was in the class 2 seating at an average fare of **$32**:

* **Survived** : **38%** 
* **Victims**  : **62%** 
* **Age**      : **24** 
* **Class**    : **2** 
  * First Class Survivors: **136**  
  * First Class Vicitims: **80** 
  * Second Class Survivors: **87**
  * Second Class Victims: **97** 
  * Third Class Survivors: **119** 
  * Third Class Victims: **372** 

* **Fare**     : **$32** 

## How many people survived and were victims by class? 
The most interesting insight (IMO) was there a better survival outcome based on socio-economic status? Given your position on the ship and sex what was the likely hood of your survival? 

### Male Survival & Male Victims: 
<img src="/images/MS.png" class="left"/>
<img src="/images/MD.png" class="right"/>

The histograms shows the sample population of **577** men who survived and were victims by each class. You may notice that first class males survived in a larger amount then were victims but only 4. Within the total sample poulation of males, first class men had **7.8%** percent chance of survival and a **13%** chance of deat while, third class males had a **8.1%** chance of survival and a **52%** chance of death. 

### Female Survival & Female Victims: 
<img src="/images/FS.png" class="left"/>
<img src="/images/FD.png" class="right"/>

For the female histograms the total sample population of females were **314**. And as you can see from the visualization women had a better chance of survival. In fact, withint the total sample population of women on the Titanic, first class females had a **29%** chance of survival and only **1%** chance of death, while third class female passangers had **23%** chance of survival and a equal percantage of death.  
