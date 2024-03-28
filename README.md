# Price Sensitivity: Towards 1:1 Pricing

## Overview
This repository contains slides detailing modern/dynamic pricing approaches applied to personal unsecured loans (PUL), authored by Paul Golding in December 2018. The primary goal is to predict a borrower's sensitivity to price to optimize prices for maximum expected profit or other business objectives.

See [slides](pricing_sensitivity_public.pdf)

## Key Concepts

### Credit Risk and Terms
- **Risk as a Variable Cost**: Demonstrates how risk correlates with price sensitivity and affects profitability.
- **Terms Definitions**: Introduction to terms like Exposure at Default (EAD), Loss Given Default (LGD), and Probability of Default (PD), essential for understanding expected loss and its impact on loan pricing.

### Expected Loss
The presentation delves into the mathematical foundation for calculating expected loss, highlighting the significance of PD, EEAD, and ELGD in determining the expected profitability of a loan.

### Simplified Pricing Threshold
A simplified model to understand the relationship between risk, cost of capital, and pricing, providing a foundational understanding of risk-adjusted premium cost of capital.

### Risk Prediction and Factors
- **Risk Prediction**: Utilizing machine learning, specifically XGBoost, to model borrower risk based on observables.
- **Risk Factors**: Differentiation between borrower-dependent and product-dependent risks.

Note that any machine-learning model could be used in principle (including blackbox models) because the dynamic pricing could be an independent overlay to risk-based pricing and so, as such, need not be subjected to explainability criteria.

### Price-dependent Risk
An analysis of how increasing prices can affect the default probability and, consequently, the profitability of a loan.

### Incremental Profitability
The presentation outlines the factors influencing the profitability of a loan in relation to its price, including discussions on variable costs, profit goals, and the impact of selling or securitizing loans.

### Price Response Curve and Sensitivity Measurement
Explores the methodology for determining the price-response function and measures of price sensitivity such as slope, hazard rate, and elasticity.

### Sensitivity and Risk
A deeper dive into the relationship between price sensitivity, default rates, and the significance of understanding this interplay for optimal pricing strategies.

### Pricing/Underwriting Considerations
Insights into the challenges and considerations of pricing and underwriting, including the estimation of demand functions and the importance of considering price sensitivity in loan profitability.

### Dynamic Segmentation and WTP (Willingness to Pay)
Discussion on the importance of predicting WTP for effective pricing and the role of dynamic segmentation in achieving 1:1 pricing.

### Optimizing Prices and Efficient Frontier
An overview of methods for optimizing prices across different segments for maximum profitability and the concept of the efficient frontier in balancing return, risk, and profit.

## Conclusion
This presentation offers a comprehensive exploration of price sensitivity in personal unsecured loans, proposing a data-driven approach to achieve optimized, personalized pricing strategies. The slides serve as a valuable resource for professionals and researchers interested in dynamic pricing models and credit risk management.

---

*Paul Golding, Dec 2018 @pgolding*

