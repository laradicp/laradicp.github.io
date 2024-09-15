---
title: "ICU hospital beds management"
excerpt: "Data-driven prescriptive approach to allocate resources for the management of Intensive Care Unit (ICU) hospital beds in Brazil's Federal District, especially during public health emergencies."
collection: portfolio
---

Solution proposed to the hackathon organized by Brazil’s Federal District Health Council and the Oswaldo Cruz Foundation (Fiocruz), titled “Digital Health Strategies for Combating COVID-19 in the Federal District Territories”. We developed a model to minimize the costs of resource allocation in the ICU bed management of Brazil's Federal District during public health emergencies, such as pandemics.

I was in charge of the prescriptive core of the project. I formulated and implemented an integer programming (IP) model that minimizes the costs related to constructing new hospitals and acquiring, repairing, and transferring relevant resources among hospitals for the ICU bed management. My teammates were responsible for training a machine learning model using public data from Brazil’s Unified Health System (SUS) to predict the demands for ICU beds in each region, which the IP model uses as input, and for developing a web service to be the interface of our tool and the health managers.

The repository can be found [here](https://github.com/TAIL-OR/tailor-infra).
