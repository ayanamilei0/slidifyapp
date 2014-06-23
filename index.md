---
title       : BMI Calculator
subtitle    : Know Better about Your Weight
author      : Min Zhong
job         : Peer Review Assignment
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
url:
# lib: ../../libraries
  assets: ../../assets
widgets     : [mathjax]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Motivation

* Overweight and obesity lead to high risk of developing serious health problems including heart disease, high blood pressure, type II diabetes, etc..
* One third of all Americans are obese.
* Assessing your weight and health risk:
    - Body Mass Index (BMI)
    - Waist circumference
    - Risk factors for diseases and conditions associated with obesity

---

## Facts about BMI

* BMI is a number calculated from a person's weight and height.
* BMI is a fairy reliable and also easy to assess indicator of body fatness for most people. It can be considered an alternative for direct measurements of body fat.
* BMI is used as a screening tool to identify possible problems for adults. It is one of the best methods for population assessment of overweight and obesity, and allow yourself to compare weight status to that of the general population.


---  

## Calculation and Interpretation of BMI

BMI is calculated the same way for both adults and children. The calculation is based on the following formulas:

###  $$BMI=\frac{weight (kg)}{height (m)^2}=703\frac{weight (lbs)}{height (inch)^2}$$

<img src="figure/1.png" title="plot of chunk 1" alt="plot of chunk 1" style="display: block; margin: auto;" />

Example: the person with height 1.65 m has a normal weight range from 50.4 kg to 68.1 kg.

---

## BMI Calcultor App on Shiny!

### You Are Just One Click Away from Your BMI!

To help you assess your weight status, we have developed an interactive app on Shinyapps website. Just go to the [app](https://ayanamilei.shinyapps.io/BMI_calculator/) and input your height and weight in your comfortable measure, the [app](https://ayanamilei.shinyapps.io/BMI_calculator/) will determine your BMI in no time! Also, the [app](https://ayanamilei.shinyapps.io/BMI_calculator/) has an general classification table for you to determine the weight range. You can also use [wiki page](http://en.wikipedia.org/wiki/Body_mass_index) if you feel necessary.

Our App will help you have better control of your body fat. Make a goal, and work for it!

![ask](assets/img/health.jpg)
