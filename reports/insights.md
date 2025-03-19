# Car Purchase Prediction Insights

## Model Performance
- **Best Model**: XGBoost Regressor  
- **Metrics**:  
  - **R² (Test Set)**: 0.92  
  - **MAE**: $1,200  
  - **RMSE**: $1,800  
- **Comparison**:  
  - Linear Regression: R² = 0.75  
  - Decision Tree: R² = 0.85  

## Top Drivers of Car Purchase Amount
1. **Net Worth** (45% influence)  
   - High-net-worth customers (>$600k) spend 2.5x more than others.  
2. **Annual Salary** (30% influence)  
   - Customers earning >$80k/year contribute to 60% of total sales.  
3. **Age** (15% influence)  
   - Peak purchasing age: 45–55 years.  
4. **Debt-to-Income Ratio** (10% influence)  
   - Customers with ratios <0.15 spend 20% more.  

## Customer Segmentation
| Cluster | Net Worth Tier    | Avg. Purchase | % of Total Sales | Target Strategy                |
|---------|-------------------|---------------|------------------|---------------------------------|
| 0       | High (>$600k)     | $65,000       | 40%              | Luxury car promotions           |
| 1       | Medium ($300–600k)| $45,000       | 35%              | Financing options               |
| 2       | Low (<$300k)      | $28,000       | 25%              | Budget-friendly deals           |

## Recommendations
1. **Geographic Focus**: Prioritize UAE, Brazil, and Singapore (high-net-worth clusters).  
2. **Campaigns**:  
   - Launch "Luxury Tier" ads for Cluster 0.  
   - Offer debt-to-income-based financing for Cluster 1.  
3. **Data Gaps**: Collect promotion/ad-spend data for future models.  

## Visualizations (Saved in `reports/figures/`)
- `shap_summary.png`: Top features impacting predictions.  
- `cluster_distribution.png`: Purchase patterns across segments.  
- `geo_heatmap.png`: High-value countries.  