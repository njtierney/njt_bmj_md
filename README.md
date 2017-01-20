# Using decision trees to understand structure in missing data

Authors: Nicholas Tierney, Fiona Harden, Maurice Harden, Kerrie Mengersen

This GitHub repo currently hosts my paper .Rmd file. The data used to create the paper is unable to shared due for ethical and industry reasons, as it contained personal information.

You can read the paper in full [here at BMJ Open](http://bmjopen.bmj.com/content/5/6/e007450.full)

The Paper here might differ slightly as some final changes made were not entered into the .Rmd.

## Abstract

**Objectives** Demonstrate the application of decision trees—classification and regression trees (CARTs), and their cousins, boosted regression trees (BRTs)—to understand structure in missing data.

**Setting** Data taken from employees at 3 different industrial sites in Australia.
Participants 7915 observations were included.

**Materials and methods** The approach was evaluated using an occupational health data set comprising results of questionnaires, medical tests and environmental monitoring. Statistical methods included standard statistical tests and the ‘rpart’ and ‘gbm’ packages for CART and BRT analyses, respectively, from the statistical software ‘R’. A simulation study was conducted to explore the capability of decision tree models in describing data with missingness artificially introduced.

**Results** CART and BRT models were effective in highlighting a missingness structure in the data, related to the type of data (medical or environmental), the site in which it was collected, the number of visits, and the presence of extreme values. The simulation study revealed that CART models were able to identify variables and values responsible for inducing missingness. There was greater variation in variable importance for unstructured as compared to structured missingness.

**Discussion** Both CART and BRT models were effective in describing structural missingness in data. CART models may be preferred over BRT models for exploratory analysis of missing data, and selecting variables important for predicting missingness. BRT models can show how values of other variables influence missingness, which may prove useful for researchers.

**Conclusions** Researchers are encouraged to use CART and BRT models to explore and understand missing data.
