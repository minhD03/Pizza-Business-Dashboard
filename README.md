# Pizza Business Dashboard
## 1. Introdcution: 
This Pizza Dashboard uses Power BI to track the pizza business. This will help deciding to utilize any pizzas on the menu or ingredients for the most profit and efficiency.
## 2. Preview Screenshots:
[Live Dashboard Link](https://app.powerbi.com/groups/me/reports/beffc558-a427-4387-83b3-fc61d392f8de?ctid=6a68e2d1-d88d-412b-b982-d4aed5f51716&pbi_source=linkShare)


Below are my Dashboard Screenshots. Further report can be viewed [Here](https://github.com/minhD03/Pizza-Business-Dashboard/blob/efc0e7baf1026a1612c17c195deba439cf5ebecc/Pizza%20Business%20-%20Nhat%20Minh%20Dang.pdf)

![alt text](https://github.com/minhD03/Pizza-Business-Dashboard/blob/bec5b1eab58ff0621ea5ca19d68289535c116dbd/Images/Dashboard%201.png)
![alt text](https://github.com/minhD03/Pizza-Business-Dashboard/blob/bec5b1eab58ff0621ea5ca19d68289535c116dbd/Images/Dashboard%202.png)
![alt text](https://github.com/minhD03/Pizza-Business-Dashboard/blob/bec5b1eab58ff0621ea5ca19d68289535c116dbd/Images/Dashboard%203.png)

## 3. About the data:
The dataset contains 1 Excel File with these columns:
| Field       | Description                                                                                                                                         |
|-------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| order_id    | Unique identifier for each order placed by a table                                                                                                  |
| date        | Date the order was placed (entered into the system prior to cooking & serving)                                                                     |
| time        | Time the order was placed (entered into the system prior to cooking & serving)                                                                     |
| quantity    | Quantity ordered for each pizza of the same type and size                                                                                           |
| pizza_id    | Unique identifier for each pizza (constituted by its type and size)                                                                                 |
| size        | Size of the pizza (Small, Medium, Large, X Large or XX Large)                                                                                      |
| price       | Price of the pizza in USD                                                                                                                           |
| name        | Name of the pizza as shown in the menu                                                                                                              |
| category    | Category that the pizza falls under in the menu (Classic, Chicken, Supreme, or Veggie)                                                             |
| ingredients | Comma-delimited ingredients used in the pizza as shown in the menu (they all include Mozzarella Cheese, even if not specified and they all include Tomato Sauce, unless another sauce is specified) |

## 4. Insights gained:
### 📊 Pizza Business Insights (2015)

#### 🧭 Overall Business Performance
- **Total Revenue:** $817.86K from 21,000 orders and 50,000 pizzas.
- **Average Order Value:** $38.31 with 2.32 pizzas per order.
- **Ingredient Complexity:** Average of 6 ingredients per pizza — balancing uniqueness and cost.

#### 📅 Temporal Sales Patterns
- **Peak Hours:** 12 PM (lunch) and 7 PM (dinner) show consistent demand spikes.
- **Top Weekday:** Friday leads in revenue; Sunday underperforms due to surcharges and lifestyle factors.
- **Seasonal Trends:**
  - High-performing months: August, July, December.
  - Low-performing months: February, October.

#### 📆 Monthly Revenue Highlights
- **January:** Mid-month spike likely tied to New Year promotions and social events.
- **February:** Volatile performance with multiple peaks and troughs — suggests inconsistent demand.
- **July:** Strong weekday sales; dinner hours dominate. Weekend performance lags.
- **October:** Singular peak around the 20th; stable baseline — ideal for pre-holiday testing.
- **December:** Structured rhythm with strong end-of-month finish — driven by holiday gatherings.

#### 🍕 Menu Performance
- **Top Categories by Revenue & Quantity:**
  - 🥇 Classic
  - 🥈 Supreme
  - 🥉 Chicken
- **Optimization Opportunity:** Promote Veggie and Chicken categories to reduce reliance on Classic/Supreme.

#### 🔝 Best & Worst Performing Pizzas
- **Top by Revenue:** Thai Chicken, Barbecue Chicken, California Chicken, Classic Deluxe.
- **Bottom by Quantity & Revenue:** Spinach Supreme, Mediterranean, Brie Carre — tied to niche ingredients.
- **Insight:** Familiar, affordable flavors outperform exotic recipes.

#### 📐 Size & Ingredient Dynamics
- **Size Preferences:**
  - Classic: Small and Medium sizes dominate.
  - Other categories: Large preferred — aligns with worker demographics.
- **Ingredient Impact:**
  - Top contributors: Garlic, Tomatoes, Red Onions, Red Peppers.
  - Low performers: Brie, Plum Tomatoes, Thai Sweet Chili — may require cost-risk evaluation.

#### 📈 Correlation Analysis
- **Revenue vs Quantity:** Positive correlation — high-selling ingredients drive revenue.
- **Price vs Volume:** Negative correlation — higher prices tend to suppress total sales volume.

#### ⏱️ Order Frequency & Timing
- **Multi-pizza orders:** 61.59% of transactions; longer prep time (~10.84 mins).
- **Single orders:** 38.41%; dominate off-peak hours — bundling strategies recommended.

#### ✅ Strategic Recommendations

- **Menu Diversification:**
  - Introduce new variants in the Chicken and Veggie categories to reduce dependency on Classic and Supreme.
  - Phase out or rebrand underperforming niche pizzas with low revenue and quantity (e.g., Spinach Supreme, Brie Carre).

- **Ingredient Optimization:**
  - Prioritize high-performing ingredients (Garlic, Tomatoes, Red Onions, Red Peppers) in new recipes.
  - Monitor cost and availability of low-performing or premium ingredients to mitigate supply risks.

- **Pricing Strategy:**
  - Consider tiered pricing bundles to balance affordability and upselling (e.g., combo deals with sides/drinks).
  - A/B test pricing for premium pizzas to find optimal conversion thresholds without suppressing volume.

- **Operational Efficiency:**
  - Align staffing with peak hours (12 PM & 7 PM) and high-demand weekdays (especially Fridays).
  - Reduce labor costs during off-peak periods and Sundays with lean scheduling or automation.

- **Promotional Timing:**
  - Launch targeted campaigns during low-performing months (February, October) to stabilize revenue.
  - Replicate successful October and December strategies across other months for consistent performance.

- **Size Strategy:**
  - Promote Small and Medium sizes for Classic pizzas to maintain volume and margin.
  - Offer value bundles for Large sizes in Supreme and Chicken categories to attract worker demographics.

- **Customer Retention:**
  - Leverage loyalty programs or personalized offers for multi-pizza orders.
  - Use ingredient preferences and order timing data to tailor marketing outreach.

- **Data-Driven Experimentation:**
  - Pilot new recipes using top ingredients and monitor performance via dashboard KPIs.
  - Use correlation insights to forecast demand shifts and adjust inventory dynamically.

