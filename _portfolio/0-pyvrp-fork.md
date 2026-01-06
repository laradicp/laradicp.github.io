---
title: "VRP with Route Clustering and Soft Distance Penalties"
excerpt: "An extension to the PyVRP vehicle routing framework that implements support for clustered routes and soft distance penalties."
collection: portfolio
---

The work was developed in the context of an operations analytics role at [Praso](https://praso.com.br), focusing on improving delivery feasibility and service levels at scale.

Due to a high frequency of closed-customer events and re-delivery attempts occurring throughout the day, the company’s operations favored circular routes. To support this operational requirement, I introduced penalties for excessive distances between consecutive customers as well as between the first and last customers on a route.

In addition, drivers may receive supplemental compensation once a route exceeds a predefined maximum distance. This operational policy motivated the implementation of soft distance penalties, allowing the model to exceed distance limits when necessary while explicitly accounting for the associated cost trade-offs.

The implementation is available as a fork of PyVRP on GitHub:  
[https://github.com/laradicp/PyVRP](https://github.com/laradicp/PyVRP)