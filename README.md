# EDM Ad Analytics & Bid Optimization  

## Project Overview  
This project focuses on optimizing EDM’s Google Ads bidding strategy using **analytics-driven modeling**. By leveraging **linear forecasting** and **Solver optimization**, we determine the most effective bid allocations to maximize profit while balancing CPC, clicks, and conversions.  

## Data & Methodology  
- **Dataset**: The data includes bid values, estimated CPC, conversion rates, and click-through rates for multiple keywords.  
- **Forecasting Model**: **Linear regression (FORECAST.LINEAR)** was used to predict estimated CPC and clicks/day based on bid values.  
- **Optimization**: The **Excel Solver** tool was used to optimize bid allocation under budget constraints.  
- **Comparative Analysis**: The model was run with and without budget restrictions to assess the impact on total profit.  

## Key Findings  
- Under a **$10 budget**, optimal bids were allocated strategically to maximize ROI.  
- Without budget constraints, bids increased for high-performing keywords, leading to **higher conversions and total profit**.  
- Diminishing returns were observed, emphasizing the need for balanced bid adjustments.  

## How to Use  
1. Open the **Excel file** and navigate to the **Solver setup**.  
2. Adjust bid values and run Solver to **optimize** based on budget constraints.  
3. Compare results by modifying budget limits and analyzing **profit changes**.  

## Files  
- `EDM_data.xlsx` – Source data for bids, CPC, and conversion rates.  
- `Bid_Optimization.xlsx` – Model with linear forecasting and Solver optimization.  
- `README.md` – Project documentation.  

## Future Improvements  
- **Machine Learning Approach**: Using regression models to enhance bid predictions.  
- **Automated Bidding Strategy**: Implementing Python-based ad bidding algorithms.  
- **A/B Testing**: Validating optimized bids with real campaign performance.  


