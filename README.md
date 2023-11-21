# INSTIs-and-Mortality
This is the R code used in the analyses of "Associations of modern initial antiretroviral therapy regimens with all-cause mortality in people living with HIV in resource-limited settings: a retrospective multicenter cohort study in China":

Wu, X., Wu, G., Ma, P., Wang, R., Li, L., Chen, Y., Xu, J., Li, Y., Li, Q., Yang, Y., Wang, L., Xin, X., Qiao, Y., Fu, G., Huang, X., Su, B., Zhang, T., Wang, H., & Zou, H. (2023). Associations of modern initial antiretroviral therapy regimens with all-cause mortality in people living with HIV in resource-limited settings: a retrospective multicenter cohort study in China. Nature communications, 14(1), 5334. https://doi.org/10.1038/s41467-023-41051-w

# Methods
The Poisson regression models were fitted using the glm function from the base R package. The robust standard errors of Poisson models were computed using the vcovHC function from the sandwich R package. The Cox Proportional models were fitted using the coxph function from the survival R package. Details were shown in the paper.

# Contact
In case of any issues with the R code, please contact the first author Xinsheng Wu (wuxsh25@mail2.sysu.edu.cn).
