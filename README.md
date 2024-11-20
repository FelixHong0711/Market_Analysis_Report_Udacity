# Targeted Marketing Campaign Analysis

## Business Requirement

An online national clothing chain needs assistance in creating a targeted marketing campaign. Sales have been flat, and the company wants to lure lost customers back. They aim to advertise specific products to specific customers in specific locations, but currently lack insight into who to target. The products in focus include:

- **Shirt**: $25  
- **Sweater**: $100  
- **Leather Bag**: $1,000  

The goal is to analyze the provided data to determine the best product to advertise to each customer.

## Analysis and Insights Based on the Provided Visualizations

### Correlation (R² value) between Sales and Income: **0.78**
- **Insight**: A strong correlation suggests that sales are a significant predictor of income and vice versa.

### Correlation (R² value) between Customer Ratings and Product Return Rate: **-0.69**
- **Insight**: A moderate negative correlation indicates that higher customer ratings are associated with lower return rates.

### Linear Regression Formula to Predict Customer Income from Sales:  
**y = 72.43*x + 72638.21**

where x represents sales and y represents predicted customer income.

- **Insight**: Income increases by approximately $72.43 for every additional unit of sales.

### Customer Predicted to Have the Highest Income: **Jon Little ($0.45M)**
- **Insight**: Jon Little represents a high-value customer segment for personalized marketing efforts.  
  - *Action*: Offer exclusive discounts, early access to products, or tailored promotions to retain loyalty.

### Product Advertised the Most: **Shirt**
- **Insight**: Shirts dominate recommendations, reflecting their popularity or profitability.  
  - *Action*: Expand the variety or quality of shirts to meet demand and explore complementary product promotions (e.g., sweaters or accessories).

## Additional Insights

- **Regional Targeting**: The income heatmap identifies areas with dense high-income households, offering opportunities for region-specific campaigns.
- **State-wise Recommendation**: States like California feature prominently in recommendations, indicating significant demand.  
  - *Action*: Allocate more resources to advertising and stocking in these regions.
- **Marketing Target**: Products with high marketing scores (like shirts) indicate strong visibility or profitability margins.  
  - *Action*: Optimize advertising budgets around these products.

## Strategic Takeaways

1. **Regional Focus**: Invest in regions or states with higher sales-to-income correlation.
2. **Customer Satisfaction**: Enhance customer satisfaction to reduce return rates and improve loyalty.
3. **High-Value Customers**: Personalize campaigns for high-value customers like Jon Little.
4. **Product Strategy**: Focus on top-performing products (e.g., shirts) and explore opportunities for upselling or cross-selling related items.
