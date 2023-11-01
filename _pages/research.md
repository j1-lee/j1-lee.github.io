---
layout: page
permalink: /research/
title: Research
nav: true
nav_order: 2
---

{% assign lee_son_pdf = "assets/pdf/lee_son_distributional_impacts_2023_oct.pdf" | relative_url %}
{% assign jmp_pdf = "assets/pdf/jmp_feasible_robust.pdf" | relative_url %}

### Working Papers

- **[Computationally feasible identification-robust inference on discrete choice demand]({{ jmp_pdf }})** _Job Market Paper_

  **Abstract**: The possibility of instruments being weak is a central debate in empirical industrial organization, particularly in the context of demand estimation. This paper applies an identification-robust confidence set proposed by Andrews (2018) in the context of the discrete choice demand model by Berry, Levinsohn, and Pakes (1995), offering a technique to enhance its computational feasibility. Given that the computational cost stems from grid searches over a large dimensional parameter space, I provide a condition under which the dimensionality of the required grid can be significantly reduced. Monte Carlo simulations show that the robust confidence set obtained by utilizing my dimension reduction technique achieves desired properties when the condition is met. Even when the potentially restrictive condition, namely homoscedasticity, is violated, this technique is able to achieve a close approximation of the confidence set that would have been obtained through a full grid search. This suggests that the technique can also guide the formation of a full grid, especially when a researcher lacks prior information.

- **[Distributional impacts of centralized school choice]({{ lee_son_pdf }})** (with [Suk Joon Son](https://sites.google.com/view/sukjoon-son))

  **Abstract**: Informational frictions in centralized school choice can significantly influence its distributional consequences. Recognition of such frictions is also necessary to accurately measure welfare. We build a model of school applications, allowing applicants to consider only a limited set of schools and to have mistaken beliefs about their admission chances. Quasi-experimental variation and rich information in students’ rank-ordered lists enable identification. Utilizing this model, we evaluate the impacts of centralized school choice in New York City on racial segregation and equity in welfare, decomposing the contributions of the frictions and the preferences of students and schools. We also quantify matching stability and deviations from truthful reporting. Our results show that while school choice improves welfare across races, limited consideration substantially compromises these gains, particularly for Black and Hispanic students. A counterfactual policy involving personalized school recommendations designed using our model is projected to recover 20–36% of the welfare losses.

### Work in Progress

- **Correct standard errors in discrete choice demand estimation when using Hausman instruments**

  Existing asymptotic results for the BLP estimator are based on the independence of instruments and structural errors across markets. However, I find that a class of instruments, commonly referred to as Hausman instruments, violates this assumption by introducing correlation across markets, resulting in inaccuracies in the conventionally calculated standard errors. I confirm the phenomenon through Monte Carlo simulations. Then I apply techniques from spatial econometrics and time series econometrics to address the across-market correlation, discussing methods to correctly calculate the standard errors for different subclasses of Hausman instruments.

### Publications

- **Long-term changes in old-age incomes: Results from cohort analyses** (2015) with [Chulhee Lee](https://sites.google.com/view/chullee98), _Journal of Korean Economic Studies_, 33(3), 5–34, in Korean.
