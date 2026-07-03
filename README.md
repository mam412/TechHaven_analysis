# TechHaven - E-commerce Analysis

TechHaven is a global e-commerce company founded in 2018 specializing in consumer
electronics. This analysis covers **$28M in revenue across 108K orders from 2019–2022**,
examining product performance, refunds, loyalty program performance, and marketing channels.

---

# Executive Summary

<div align="center">
  <img src="images/sales_trends.png" width="80%">
</div>

Between 2019 and 2022, TechHaven generated $28M across 108K orders, with performance accelerating sharply during the pandemic surge of 2020–2021. Elevated demand for premium electronics — especially the 27‑inch 4K Gaming Monitor, the only product to dominate across all four global regions — pushed average order value to $297 and positioned TechHaven for its strongest year on record. The surge aligned with broader gaming and streaming trends, creating a temporary tailwind that amplified the company’s core strengths.
As conditions normalized post‑2021, the business experienced a significant decline in both sales and AOV, revealing structural vulnerabilities that had been masked by pandemic‑driven demand. Revenue remained heavily concentrated in a narrow set of products, with Apple generating disproportionate refunds and gaming monitors carrying outsized revenue share. The loyalty program showed near‑zero retention, with only 39 repeat purchasers out of 38,756 members, indicating that TechHaven was acquiring customers but not building long‑term relationships. Marketing channels leaned too heavily on organic traffic, while email and affiliate — the only channels showing consistent strength — remained under‑leveraged.
The analysis also uncovered data integrity issues, including pricing anomalies across five major products and missing refund data for 2022. These gaps likely understate true performance and limit the company’s ability to make accurate, timely decisions.
Taken together, the findings depict a company that grew quickly during a period of extraordinary demand, but now must evolve its operating model to sustain long‑term growth. The path forward centers on expanding the gaming product portfolio, redesigning loyalty mechanics, correcting pricing and refund data, and rebalancing marketing investment toward channels with measurable ROI. These steps position TechHaven to transition from pandemic‑boosted momentum to a more resilient, strategically grounded future.

---
# Key Insights
- Loyalty members are high‑value but low‑retention. The program attracts the right customers but gives them no reason to return. Meaning loyalty must be redesigned around engagement between purchases rather than incentives at the point of purchase.
- Invest in the 4K Gaming Monitor and Gaming Peripherals
- TechHaven’s product portfolio is structurally imbalanced: the rise of the 4K Gaming Monitor directly and decline in MacBook demand, reveals a business overly dependent on a few high‑value products 
- Email is TechHaven’s only reliable growth and retention channel, but it is under‑leveraged.
- Pricing anomalies and missing refund records materially distort AOV, profitability, and channel performance, meaning TechHaven cannot make reliable strategic decisions until core data issues are resolved.

---
# Analysis & Insights

## Product Performance

Three products drive 82% of TechHaven's revenue with ~97% concentrated among a
handful of brands — a concentration that became a liability when MacBook began its
decline in Q4 2021. The pandemic created an artificial performance ceiling, and each
period since has seen declining sales, AOV, and order volume, with figures now falling
below pre-pandemic baselines. Meaningful recovery will require structural improvements rather than
waiting for external demand to return. The 4K Gaming Monitor's growth from 35% to 50%
revenue share is a strong signal amid that decline, though it comes directly at
MacBook's expense. The business should be actively expanding the Gaming Monitor catalog
into peripherals while simultaneously investigating whether Apple's decline is
recoverable.

| Period | Total Sales | AOV | Total Orders |
|---|---|---|---|
| 2019–2022 | $28M | $260 | 108K |
| Jan 2019–Mar 2020 | $5M | $237 | 20K |
| Mar 2020–Mar 2021 | $12M | $297 | 39K |
| Mar 2021–Jan 2022 | $7M | $246 | 30K |
| Jan 2022+ | $4M | $229 | 19K |

<div align="center">
  <img src="images/Top3 -  4K Gaming Monitor Leads Top 3 Products in Revenue.png" width="45%">
  <img src="images/Top3 - Airpods Lead Top 3 Products by Order in Total Orders.png" width="45%">
</div>

Revenue is heavily concentrated in Gaming Monitor ($9.8M), AirPods ($7.7M), and
MacBook ($6.3M) - together 82% of total revenue - meaning losing any one of them
meaningfully changes the business, as MacBook's decline is already demonstrating.
Order leadership tells a different story: AirPods lead at 48K orders, followed by
Gaming Monitor at 23K and Samsung Charging Cable at 22K. Samsung Charging Cable and
Samsung Webcam don't move the revenue needle, but their high order volumes make them
natural candidates for bundling with higher-value purchases to increase cart size
without requiring new customer acquisition.

### Product Spotlight

<div align="center">
  <img src="images/Top3 - 4K Gaming Monitor Overtakes Macbook in all Regions.png" width="80%">
</div>

<div align="center">
  <img src="images/Macbook North American AoV Fluctuates with 4Q22 Outlier.png" width="70%">
</div>

Gaming Monitor is TechHaven's growth story - the most popular product across all
regions, growing from 35% to 50%+ revenue share by late 2022 and peaking at ~$186K
monthly in NA in January 2022. A late-2022 NA uptick suggests potential renewed
demand, making this a product line worth expanding into peripherals. Apple MacBook
is the risk - declining steadily since Q4 2021 with sales and order volume falling
in lockstep, confirming this is a demand problem.
A Q4 2022 AOV drop to ~$1,200 from a typical $1,500–$1,700 range adds another
flag worth investigating. AirPods remain the most consistent volume driver in the 
portfolio at 48K orders, showing no dramatic
spikes or collapses - and Apple's refund concentration across its
full product line warrants close monitoring. See [Refunds](#refunds) for the full
breakdown.

### Pricing Anomalies

Several products show orders at price ranges inconsistent with known retail pricing.
These anomalies likely understate AOV for affected products, meaning real performance
may be stronger than reported. They should be flagged in any AOV or revenue analysis
until resolved.

| Product | Suspicious Price Range | Order Count | AOV |
|---|---|---|---|
| 27in 4K Gaming Monitor | $1–$100 | 73 | $421 |
| Apple AirPods | $1–$50 | 183 | $160 |
| MacBook Air Laptop | $1–$1,000 | 259 | $1,591 |
| Samsung Charging Cable Pack | $1,000+ | 1 | $20 |
| ThinkPad Laptop | <$1,000 | 550 | $1,101 |

- **ThinkPad and MacBook** carry the largest exposure — 550 and 259 orders at prices
  well below retail; resolving these could meaningfully improve reported AOV for both
  products
- **Samsung Charging Cable's** single $1,000+ order is almost certainly a data entry
  error and should be excluded from any channel or product-level averages

---

## Refunds

<div align="center">
  <img src="images/Reunds - Treemap.png" width="45%">
  <img src="images/Refunds - Total Avg.png" width="50%">
</div>

There are two drivers of refund risk — volume and AOV — and they point to different
products. MacBook Air generates the highest total refund value at $717K not because
it has the most returns, but because its $1,588 AOV means each return erases
significantly more revenue than any other product. AirPods generate the most refund
volume at 2,636 returns — nearly double their 2019 volume during the 2020 pandemic
surge — but their $160 AOV limits the per-return financial impact to $421K total.
Apple's product line accounts for 58% of all refunds, and while the 2020 spike
appears tied to pandemic order volume rather than a product-specific issue, the
concentration warrants a dedicated post-purchase support strategy as order volume
recovers.

- **⚠️ 2022 data flag:** 0 refunds recorded despite 21,565 orders — a consistent
  prior-year rate would suggest ~1,000+ refunds; almost certainly a data integrity
  issue rather than a true zero
- Loyalty member refund behavior surfaces a broader pattern about program
  effectiveness - see [Loyalty Program Performance](#loyalty-program-performance)

---

## Loyalty Program Performance

Loyalty members are high‑value but low‑retention. The program attracts the right customers but gives them no reason to return. Loyalty members spend more per product than non-loyalty across nearly every
category - MacBook loyalty AOV ~$1,700 vs. ~$1,600 for non-loyalty, and Gaming
Monitor loyalty AOV is ~$460 vs. ~$390. Despite this, only 39 of 38,756 members ever
made a second purchase. These aren't discount hunters - they're genuinely higher-value
customers who buy once and never return.

<div align="center">
  <img src="images/39 Returning Loyalty Members; $29K Total Sales.png" width="80%">
</div>

<div align="center">
  <img src="images/Loyalty Program AoV2.png" width="45%">
  <img src="images/Loyalty Program Total Sales Outpace Non Members 2Q-2021 but Falter Q4-2022.png" width="45%">
</div>

The program's sales advantage over non-loyalty since Q2 2021 is real, but the reason
matters. Loyalty didn't accelerate - non-loyalty declined. Non-loyalty generated
~$17M (61%) vs. loyalty's ~$11M (39%) across the full period, and by Q4 2022
non-loyalty was pulling ahead again on both sales and AOV. The loyalty AOV crossover
follows the same logic - non-loyalty AOV spiked to ~$380 during the pandemic then
crashed back, making loyalty appear stronger by comparison rather than because members
were actually spending more over time.

<div align="center">
  <img src="images/Loyalty - Loyalty Members Return More Often2.png" width="50%">
</div>

TechHaven’s loyalty program isn’t failing because customers are disengaged — it’s failing because the product catalog itself doesn’t create natural repeat‑purchase behavior. High‑AOV, single‑purchase electronics mean customers buy once, then have no inherent reason to return, so loyalty must shift from purchase‑based incentives to engagement between purchases.

---

## Marketing Channel Performance

Email is the standout channel — the only one to grow in both 2020 (+223%) and 2021
(+24%) — driven primarily by loyalty members, who account for 11K of Email's total
orders vs. 8K from non-loyalty. Every other channel declined in 2021 after the
pandemic spike, which means Email isn't just a volume channel — it's demonstrably
reaching the customers TechHaven is trying to retain. This makes Email the most
direct lever for any loyalty restructuring effort.  The Affiliate Program channel has
The highest AOV at ~$303 - consistently attracting higher-intent,
  higher-value customers. This warrants increased investment; however, given its sharp
  2021 decline (-41%) and sensitivity to market conditions, performance should be
  closely monitored. If meaningful return isn't evident within 6 months, the program
  should be discontinued

![Marketing Channel Chart](images/marketing_channel.png)

- **Affiliate:** Highest AOV at ~$303 — consistently attracts higher-intent,
  higher-value customers and warrants increased investment; however, given its sharp
  2021 decline (-41%) and sensitivity to market conditions, performance should be
  closely monitored. If meaningful return isn't evident within 6 months, the program
  should be discontinued
- **⚠️ Unknown channel:** Spiked +2,325% in 2020 and +295% in 2022, contrasting
  sharply with declines across every other channel — almost certainly a tracking
  or attribution failure that needs to be resolved before drawing channel-level
  conclusions

| Channel | Order Count | Refund Rate | 2020 YoY | 2021 YoY |
|---|---|---|---|---|
| Email | 18,553 | 4.76% | +222.60% | +24.46% |
| Direct | 83,884 | 5.03% | +160.59% | -12.70% |
| Affiliate | 2,900 | 4.76% | +86.36% | -41.29% |
| Social Media | 1,293 | 7.58% | +95.02% | -21.32% |
| Unknown | 1,469 | 2.45% | +2,324.56% | -12.32% |

---

# Recommendations

| Priority | Department | Recommendation |
|---|---|---|
| 🔴 High | **Product** | Expand Gaming Monitor catalog into peripherals — growing from 35% to 50%+ revenue share signals strong demand worth building on |
| 🔴 High | **Product** | Resolve pricing anomalies across 5 products — current data likely understates AOV, meaning performance may be stronger than reported |
| 🔴 High | **CRM** | Restructure loyalty program — 38,756 members, only 39 repeat purchasers; the program is attracting quality customers but has no retention mechanism |
| 🔴 High | **Marketing** | Invest in Email — only channel growing in both 2020 and 2021; primary touchpoint for loyalty members and the clearest lever for retention |
| 🟡 Medium | **Sales** | Expand brand portfolio to reduce ~97% revenue concentration - MacBook's decline shows how quickly a top-3 product can erode total revenue |
| 🟡 Medium | **Sales** | Bundle Samsung Charging Cables and Webcams with higher-value purchases - high order volumes make them natural add-ons to increase basket size without new customer acquisition |
| 🟡 Medium | **CRM** | Introduce loyalty member benefits between purchases — exclusive offers, shipping perks, or early product access to create engagement touchpoints in a catalog that doesn't naturally drive repeat visits |
| 🟡 Medium | **Marketing** | Increase Affiliate investment and monitor closely — highest AOV channel at $303 warrants a push, but if meaningful return isn't evident within 6 months, discontinue the program |
| 🟢 Low | **Data** | Validate 2022 refund data — 0 refunds across 21,565 orders is almost certainly an error and limits the ability to draw trend conclusions |
