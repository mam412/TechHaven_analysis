# **TechHaven_analysis**
Sales trends analysis for e-commerce company

---

## 🚀 **Overview**
TechHaven is an e-commerce company founded in 2018, specializing in popular consumer electronics. With a strong global presence across both their website and mobile app, they have grown into a $28M business offering products from top brands including Apple, Samsung, Bose, and Lenovo. Customers are reached through a mix of marketing channels including email campaigns, SEO, and affiliate links.

TechHaven's Head of Operations has requested a comprehensive analysis of company performance between 2019 and 2022. This analysis addresses key business questions across sales trends, product performance, regional insights, customer loyalty, and operational efficiency — providing actionable insights and recommendations to support sustained growth.

This analysis covers five key areas of TechHaven's business performance.

***Sales Trends***: Examines year-over-year and month-over-month growth patterns, including seasonality drivers.\
***Product Performance***: Identifies top and bottom performers across product lines, with a focus on refund rates and revenue concentration.\
***Regional Performance***: Explores how products perform across global markets and highlights emerging growth opportunities.\
***Loyalty Program Performance***: Evaluates the effectiveness of the loyalty program and whether continued investment is warranted.\
***Marketing Channel Performance***: Analyzes how each acquisition channel contributes to order volume, revenue, and customer quality.


## **Recommendations**

<table>
  <tr>
    <th>Department</th>
    <th>Recommendations</th>
  </tr>

  <tr>
    <td><strong>Sales</strong></td>
    <td>
      • Use high‑volume, lower‑value items as upsell levers<br>
      • Expand brand portfolio to reduce dependency concentration<br>
      • Verify low sales for Bose in 2022 as being accurate and not an error
    </td>
  </tr>

  <tr>
    <td><strong>Product</strong></td>
    <td>
      • Expand Samsung portfolio as strong Post Pandemic performance<br>
      • Investigate and evaluate Bose product line<br>
      • Investigate pricing outliers and discount leakage<br>
      • Improve product content to reduce return rates
    </td>
  </tr>

  <tr>
    <td><strong>CRM</strong></td>
    <td>
      • Sustain and expand the loyalty program<br>
      • Introduce tiered loyalty benefits to drive higher spending<br>
      • Develop win‑back campaigns for lapsed non‑loyalty customers<br>
      • Audit “Unknown” channel attribution
    </td>
  </tr>

  <tr>
    <td><strong>Marketing</strong></td>
    <td>
      • Prioritize high‑revenue and high‑volume products<br>
      • Optimize campaigns by region & seasonality<br>
      • Scale affiliate channel<br>
      • Audit “Unknown” channel attribution
    </td>
  </tr>

</table>



## **Anaysis & Insights**

### <ins>Sales Trends<ins>
*TechHaven generated $28M in total revenue between 2019 and 2022, with growth peaking in 2021 
before a broad market contraction in 2022 brought performance closer to pre-pandemic baselines.*

![Sales Trends Chart](images/sales_trends.png)

- **Overall Revenue & Regional Distribution:** North America was the dominant market, 
contributing ~54% of total revenue ($14M), followed by EMEA at ~30% ($8M). Sales remain 
heavily concentrated in these two regions, with other markets representing a relatively 
small share of total volume.

- **Year-over-Year Growth:** 2020 saw a significant spike in both order volume (+101%) and 
sales, largely driven by pandemic-related demand. Growth peaked in 2021 before declining 
sharply in 2022 (-40% in order volume), though 2022 figures still remained above pre-pandemic 
2019 levels.

- **Month-over-Month Seasonality:** Performance consistently dips in September–October and 
again in February, before rebounding in March and peaking during the November–December holiday 
period. These seasonal patterns held across nearly every year in the dataset.

- **2022 Contraction:** October 2022 marked the sharpest single-month decline in the dataset, 
with total sales falling -55%, AOV dropping -16%, and order count declining -47%. This 
contraction was broad-based, affecting all regions and product categories simultaneously.

- **AOV Stability:** Despite significant swings in order volume and total sales, Average Order 
Value remained relatively stable throughout the period. Notably, AOV dipped in November — 
suggesting holiday-driven volume was fueled by lower-priced items or promotions rather than 
higher-value purchases.


### <ins>Product Performance<ins>
*A small number of products drive the vast majority of TechHaven's revenue and order volume, 
while high-AOV items like ThinkPad and MacBook carry disproportionate financial risk 
from refunds.*

![Product Performance Chart](images/product_performance.png)

- **Top Performers by Revenue:** Gaming Monitor led all products at $9.8M in total revenue, 
followed by AirPods at $7.7M and MacBook at $6.2M. Together these three products account 
for the majority of TechHaven's total revenue, indicating a high concentration risk across 
the portfolio.

- **Top Performers by Order Volume:** AirPods dominated order share at ~45% of total orders, 
followed by Gaming Monitors at 22% and Samsung Charging Cables at 20%. Collectively these 
three products represent ~87% of all orders placed across the four-year period.

- **Refund Rates by Product:** Lenovo (ThinkPad) carried the highest refund rate at 12%, 
and while MacBook's refund count was relatively low at 453, its $1,588 AOV means each return 
carries significant financial impact. Samsung Charging Cables and Webcams maintained low 
refund rates of ~2%, posing minimal financial risk.

- **Brand Concentration:** Apple, Lenovo, and a small group of key brands collectively account 
for ~97% of total revenue. While these brands are clearly resonating with customers, this 
level of concentration presents a dependency risk if any one brand relationship were to change.

- **Declining & At-Risk Products:** Bose experienced a -91% decline in 2022 and had only 27 
total orders over four years, making it difficult to draw meaningful conclusions from its 0% 
refund rate. Samsung Webcams saw exceptional growth in 2021 (+134%) driven by remote work 
demand, though this trend is unlikely to sustain as the market normalizes.

### <ins>Regional Performance<ins>
*TechHaven's performance is heavily concentrated in North America and EMEA, though growth 
and decline patterns are broadly consistent across all regions — with LATAM emerging as a 
notable exception with its own distinct seasonality.*

![Regional Trends Chart](images/regional_trends.png)

- **Regional Sales Concentration:** North America is the clear leader, accounting for ~54% 
of total revenue ($14M), followed by EMEA at ~30% ($8M). The remaining regions make up a 
relatively small share of total sales, highlighting both how dependent TechHaven is on these 
two markets and the untapped growth potential elsewhere.

- **Consistent Growth & Decline Patterns:** Growth and decline trends were largely mirrored 
across all regions throughout 2019–2022 — the 2020 pandemic spike, 2021 peak, and 2022 
contraction were global in nature. However, North America deviated slightly, experiencing a 
smaller decline in 2021 (-16%) compared to other regions, before seeing a relatively steeper 
drop in 2022 (-39%).

- **Holiday Seasonality Across Regions:** November and December represented peak growth 
periods across NA, EMEA, and APAC, consistent with holiday-driven demand patterns. This 
alignment suggests a shared customer behavior across these markets that can be planned 
around with coordinated seasonal campaigns.

- **LATAM Seasonality Divergence:** LATAM stands out as the only region that deviates from 
the broader holiday seasonality pattern, showing its strongest performance in July rather 
than November–December. This suggests region-specific demand drivers that warrant a tailored 
marketing approach rather than a one-size-fits-all global campaign strategy.

- **North America Refund Concentration:** North America accounts for ~50% of total refunds, 
making it the primary driver of refund-related financial impact across the business. Given 
its dominant share of both revenue and refunds, improvements to product content, return 
policies, and post-purchase experience in this market will have an outsized effect on 
overall refund metrics.

### <ins>Loyalty Program Performance<ins>
*Despite a lower Average Order Value, loyalty members have demonstrated greater revenue 
stability and resilience during downturns — making a strong case for continued investment 
in the program.*

![Loyalty Program Chart](images/loyalty_performance.png)

- **Revenue Contribution:** Since 2021, loyalty members have consistently generated higher 
total sales compared to non-loyalty customers. While non-loyalty customers led in order 
volume through 2020, loyalty members surpassed them in Q1 2021 and have maintained stronger 
revenue contribution since — even as both segments declined in 2022.

- **AOV Dynamics:** Loyalty members generally carry a lower AOV than non-loyalty customers, 
though the gap narrowed in 2022 as non-loyalty AOV declined while loyalty AOV remained 
stable. This stability suggests loyalty members are less sensitive to the broader market 
conditions that drove non-loyalty customers to spend less per order.

- **Resilience During Downturns:** Both segments spiked in 2020 and normalized through 
2021–2022, but loyalty members showed measurably greater resilience — maintaining consistent 
spend levels while non-loyalty customers experienced steeper declines in both sales and order 
volume.

- **Refund Behavior:** Loyalty members generate more refunds than non-loyalty customers 
despite placing fewer total orders (45K vs. 62K), and tend to return lower-value items. 
This points to more lenient return expectations among loyalty members and warrants monitoring 
to avoid policy abuse.

- **Program Verdict:** The loyalty program is performing well and should be retained. The 
focus going forward should shift toward increasing AOV within the segment through tiered 
benefits, targeted upsell strategies, and personalized promotions



### <ins>Marketing Channel Performance<ins>
*The Direct channel dominates TechHaven's order volume by a wide margin, while the Affiliate 
channel punches above its weight on order value — pointing to an underinvested but 
high-potential acquisition channel.*

![Marketing Channel Chart](images/marketing_channel.png)

- **Channel Contribution:** Direct is the dominant driver of order volume at ~83K orders, 
significantly outperforming all other channels. Email is the next largest contributor at 
~18K orders, while Affiliate, Social Media, and Unknown channels each contribute fewer 
than 3K orders combined.

- **Affiliate Channel Opportunity:** Despite its low order volume, Affiliate delivers the 
highest AOV of any channel at ~$303 — suggesting it consistently attracts higher-intent, 
higher-value customers. This channel appears underinvested relative to the quality of 
customers it brings in.

- **Email & Loyalty Refund Risk:** Email drives a disproportionately high number of refunds 
among loyalty members (636 refunds), suggesting a potential mismatch between promotional 
messaging and product expectations within this segment. This warrants a closer review of 
email targeting and offer strategy for loyalty customers specifically.

- **Social Media Refund Rate:** Social media carries the highest refund rate of any channel 
at ~8%, despite contributing minimal order volume (~1K orders). This points to a disconnect 
between how products are positioned in social ads and what customers actually receive.

- **Unknown Channel Anomaly:** The Unknown channel spiked +2,325% in 2020 and +295% in 2022 
— sharply contrasting with declines of -30% to -60% across all other channels in the same 
periods. This is almost certainly a tracking or attribution issue and should be investigated 
and resolved before drawing any conclusions from this channel's performance.

