# Home-Credit-Risk-Model-Stability

Consumer finance providers often face significant challenges when issuing loans due to two major factors:

1. Lack of Credit History: This can stem from various reasons such as young age, a preference for cash transactions, or recent relocation from a different country. These factors can negatively impact a customer's ability to get approved for a loan.

2. Volatility of Scorecards: Scorecards, which are models that predict loan risk, must be regularly updated to reflect the dynamic nature of clients' habits. Client behaviors evolve constantly, necessitating frequent updates to these models. This process is time-consuming and often reactive, occurring after a client has already missed a payment.

To address these challenges, it is crucial to develop models that remain stable over time. Achieving stability can be complex and often requires trade-offs, as improving model stability can sometimes compromise performance.

The goal of this notebook is to build a machine learning model that maintains stability over time while attempting to address the aforementioned challenges.

### Dataset

The dataset comprised 16 tables containing information on 1.5 million active loans, indexed by case ID. The data was sourced from both internal and external origins and included fundamental details about the clients associated with each case ID. It also encompassed information on previous loan applications, internal deposit and debit card data, as well as data from credit bureaus and tax registry providers. The raw data featured 465 unique attributes, and various predictors were transformed and encoded by Home Credit before being provided. Transformations included P for days-past-due, M for masking, A for amounts, D for dates, and T and L for unspecified transformations.

