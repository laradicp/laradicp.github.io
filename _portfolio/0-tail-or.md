---
title: "ICU hospital beds distribution"
excerpt: "Data-driven prescriptive approach to allocating Intensive Care Unit (ICU) hospital beds in Brazil's Federal District, especially during epidemics."
collection: portfolio
---

Solution proposed to the hackathon organized by Brazil’s Federal District Health Council and the Oswaldo Cruz Foundation (Fiocruz), titled “Digital Health Strategies for Combating COVID-19 in the Federal District Territories”. In three days, we built a prototype for tackling the uneven distribution of Intensive Care Unit (ICU) hospital beds in Brazil.

I was in charge of developing the prescriptive solution involving an integer linear programming (ILP) formulation that minimizes the distance of the closest ICU bed to the administrative regions in the Federal District. My teammates were responsible for training a machine learning model using data from Brazil’s Unified Health System (SUS) to predict the demands for ICU beds in each region, which the ILP model uses as input.

The repository can be found [here](https://github.com/laradicp/tail-or).
