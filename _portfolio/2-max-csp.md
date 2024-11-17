---
title: "The maximum length car sequencing problem"
excerpt: "A variant of the car sequencing problem that maximizes the length of contiguous assembly line operations without violating any option constraint, associated with car features, such as sunroof, radio and air conditioning."
collection: portfolio
---

A variant of the car sequencing problem with a novel objective function. The aim is to maximize the length of the assembly line operations without violating the so-called option constraints. These constraints are associated with car features, such as sun roof, radio and air conditioning, and impose a certain spacing among the cars with given options. As the leading author of the paper, I worked on the adaptation of existing formulations from the literature to our version of the problem, proposed a new model to solve a subjacent problem related to the maximum speed of the assembly line, found lower and upper combinatorial bounds, and implemented an Iterated Local Search-based heuristic and exact algorithms to enhance performance. Also, I conducted an instance space analysis using the software Melbourne Algorithm Test Instance Library with Data Analytics (MATILDA), which brought valuable insights about the features that make this novel variant more challenging to solve. The company’s needs are solved to optimality in less than a second, while manual approaches take hours to produce a schedule and still violate the option constraints an average of 16 times per instance.

This work was done under the supervision of [Prof. Anand Subramanian](https://ci.ufpb.br/anand) and [Prof. Maria Battarra](https://researchportal.bath.ac.uk/en/persons/maria-battarra) in collaboration with my colleague [Carlos Neves](https://www.linkedin.com/in/cvneves/). It was published in the [European Journal of Operational Research (EJOR)](https://www.sciencedirect.com/science/article/pii/S0377221724001322), was awarded the Best Undergraduate Work at the [Brazilian OR Conference](https://sbpo2021.galoa.com.br/) and the [Young Researcher Award](http://www.propesq.ufpb.br/propesq/contents/noticias/xxx-enic-premiados-2022/lista-premiados-xxx_enic_2022.pdf) (1st place) in the field of Exact and Earth Sciences, and is a finalist at the [INFORMS Undergraduate OR Prize](https://www.informs.org/Recognizing-Excellence/INFORMS-Prizes/Undergraduate-Operations-Research-Prize).

The repository can be found [here](https://github.com/laradicp/max-csp).