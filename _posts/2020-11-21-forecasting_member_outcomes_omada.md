---
layout: post
title: Forecasting Member Outcomes at Omada
---

Forecasting Member Outcomes at Omada
-----

![data_processing](/images/forecasting_data_process.png)

In my current role as a researcher at Omada, a digital chronic health management company, I worked to forecast 
our pre-diabetic member's outcomes. This task is challenging given the unpredictability 
of behavior change but critical because our business model charges 
people based on their health outcomes. Due to the project constraints we ended up
building a powerful but complex tool augmenting data we extract into our data warehouse, 
the capabilities of our internal machine learning platform, and our data orchestration repository.

I led data science for the overall project including model development and deployment. 
I pair-programmed on the data orchestration module with a data engineering partner taking lead. 
The final results reduced outcome forecasting error by up to 72% and may be one of the most comprehensive 
automated accounting solutions for value-based care organizations.

## Key takeaways

* Behavior change is hard to predict, but someone's past actions were the best predictor 
we found of their future changes. 
* While we had some error at the individual level,
at the aggregate level we found over time we got very close to the actual results.

