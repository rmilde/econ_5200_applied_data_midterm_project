# Econ 5200 Applied Data Analytics in Econ - Midterm Project
This repository contains all the elements for Econ 5200: Applied Data Analytics in Econ midterm project for Spring 2026. 

For this project, I have chosen Track A: The Causal Policy Track (Difference-in-Differences), looking at the option 1 paper: Card, D., & Krueger, A. B. (1994). Minimum Wages and Employment: A Case Study of the Fast-Food Industry in New Jersey and Pennsylvania.

This paper aims to explore the questions of how increasing minimum wage affects employment growth. They did this by comparing fast-food restaurants, where people often work at mimimum wage, between New Jersey and Pennsylvania, both before and after New Jersey implemented an increase in its minimum wage from $4.25 to $5.05 in 1992. They collected this information through surveys both before and after the wage change went into effect. This provides evidence in the policy debate of whether or not to raise minimum wage, due to the potential for it to decrease employment. However this paper found no evidence that an increase in minum wage negatively effected employment.

To extend the original analysis, I implement a heterogeneous treatment effects (HTE) framework to examine whether the impact of the minimum wage increase varies across different types of restaurants. Specifically, I interact the New Jersey treatment indicator with key characteristics already present in the dataset, including initial wage levels, chain affiliation, and geographic location.

The results show that the original finding remains robust—there is still no evidence that the minimum wage increase reduced employment, and estimated effects remain positive. However, the extension provides additional context by showing limited evidence of heterogeneity based on initial wage levels, suggesting the average treatment effect is broadly representative. Some variation emerges across chains, indicating firm-level differences in response, while geographic differences are relatively modest.

Overall, this extension does not weaken the conclusions of the original paper, but rather deepens them by showing that the positive average effect reflects a combination of heterogeneous responses across firms rather than a uniform impact across all establishments.


