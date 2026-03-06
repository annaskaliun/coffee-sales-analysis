# Coffee Sales Analysis

End-to-end sales analysis for a multi-market coffee retailer.
Tools: Tableau, Excel

## Dashboards

[View interactive dashboards on Tableau Public]
https://public.tableau.com/app/profile/hanna.skaliun/viz/CoffeeSalesAnalysis2019-2022/FromDatatoDecisionCoffeeRetailPerformance?publish=yes

## Business Problem

A coffee retailer sells coffee in 3 countries: USA, Ireland, and UK.
Revenue grew steadily from 2019 to 2021, peaked in 2021 and shows signs of decline in 2022.
2022 data covers January through August only.
Average revenue per customer has been dropping every year since 2019.

## Key Findings

- USA generates approximately 80% of revenue 
- ARPPU declined from $50.4 in 2019 to $45.9 in 2022
- Liberica most profitable (13% margin) but only 25% of sales
- Excelsa leads in sales volume but Liberica generates the most profit
- Robusta has the lowest profit ($541) despite being sold in comparable volumes to other types
- August consistently weakest month every year 
- Q4 is consistently the strongest quarter across all years

## Recommendations

- Focus marketing efforts on Liberica and Excelsa as they generate the most profit. Roast type does not significantly affect margins so it is not a priority for product decisions.
- Robusta has the lowest margin but instead of cutting it entirely, we can consider running a pilot to reduce promotions on Robusta in one market
  for one quarter and observe the impact on sales and overall profit.
- Ireland and UK show the same margin as the US. The priority here is a targeted marketing campaign to grow the customer base and reduce dependence on the US.
- August shows a consistent revenue dip every year. A targeted campaign in July-August could help smooth out the seasonal drop.
- Average spend per customer has been declining every year since 2019. Worth investigating whether loyalty card holders spend more than non-holders as a starting point.

## Limitations

- 2022 data covers January through August only, so year-on-year comparisons should be treated with caution.
- ARPPU decline is observed over 4 years but monthly data is highly volatile. This is a signal worth monitoring, not a confirmed trend.
- The dataset does not include operational costs, so margin figures reflect product-level gross margin only, not overall business profitability.

## Project Structure

- data/raw -- original dataset
- insights -- business report
- tableau -- dashboard screenshots
