# SaaS Sales Analysis – Capstone 3

## About the Business  
This project analyzes sales performance of a B2B SaaS company offering various software products to diverse customer segments.  
---

## Project Description  
The aim is to conduct a deep-dive analysis on SaaS sales data to explore customer behavior, product profitability, and discount effectiveness. The goal is to deliver data-driven strategies to improve revenue, retention, and operational efficiency.

---
## Analysis Objectives  
This analysis focuses on generating actionable insights to support data-driven business decisions, specifically to:  
- Identify high-value customer segments via RFM and Customer Lifetime Value (CLV)  
- Evaluate product efficiency and profit margins  
- Assess the impact of discount strategies on sales and profitability  
- Analyze seasonal and daily trends to optimize promotion timing  
- Detect outliers affecting sales and profit distribution  
- Measure churn rates across customer segments  

---
## Project Urgency

### Thin Margins Despite High Revenue  
- Many high-volume products show very low or negative profit margins, highlighting the need to review pricing and discount strategies.  
### Dependency on Discounts  
- Heavy discounting drives sales but directly impacts profitability.  
### Untapped Customer Segment Potential  
- Segments like SMB show strong long-term revenue potential but lack efficiency and loyalty optimization.  
### Overlooked High-Margin Products  
- Some high-margin products have low sales volumes, signaling missed growth opportunities.  
### Data-Driven Decision Making is Crucial  
- SaaS companies require data-driven approaches to design effective promotions, customer retention, and product development strategies.

---

## Stakeholders Involved

| Team / Function      | Insight Benefits                                                            |
|---------------------|------------------------------------------------------------------------------|
| Sales               | Customer segmentation strategy and upsell opportunities based on revenue and margin data  |
| Marketing           | Customer personas and churn data to improve targeted campaigns per segment  |
| Finance             | Margin and profit driver insights to support pricing aligned with customer value |
| Product             | Guidance for feature development and product tiering based on user behavior  |
| Customer Success    | Onboarding and re-engagement strategies to reduce churn in high-value segments |

---

## Dataset Summary  

- **Size:** 9,994 rows with over 40 features  
- **Data Sources:** Sales transactions, customer profiles, product details  
- **Scope:** Customer segmentation, CLV, discount & margin analysis, seasonal trends, and outlier detection  
- **Special Notes:** Includes high-value and loss-making outliers analyzed in detail

---

## Key Findings and Analysis  

- **Customer Segmentation:** SMB segment accounts for over 50% of total revenue but records the lowest profit margins. Enterprise segment shows the highest profit efficiency per customer.  
- **RFM and CLV Analysis:** Customers generally score high in Recency and Frequency, aligned with CLV values up to $36K. Most customers fall into Loyal and Others segments, indicating retention potential.  
- **Product Efficiency:** Products like ContactMatcher and FinanceHub have high sales volumes but negative margins. Conversely, Alchemy and Data Smasher have high margins but low sales, representing growth opportunities.  
- **Profit Margin & Discounts:** Discounts over 30% consistently correlate with negative margins and profit volatility. Discounts below 10% maintain profitability without significantly reducing sales volume.  
- **Timing Trends:** Sales peak from October to December and on Thursdays, especially early and late in the year. However, profits have stagnated since 2021, suggesting inefficiencies or margin erosion.  
- **Churn by Segment:** Average churn rate is about 3%, reflecting effective retention strategies. Strategic segment has the highest churn (3.5%), raising concerns given their high customer value. SMB segment shows the lowest and most stable churn.

---

## Strategic Recommendations  

1. **Cap Discounts at 20%.** Maintain discount limits to preserve margin stability. Monitor and control discounts above 30%, especially on products with negative profits.  
2. **Boost Cross-Selling and Bundling of High-Margin Products.** Focus on cross-sell and bundling strategies for high-margin products like Alchemy and Data Smasher to increase profitability without relying on volume.  
3. **Strengthen Retention in Strategic Segment.** Implement proactive onboarding and measurable value realization programs for the Strategic segment, which has high CLV but elevated churn.  
4. **Optimize Promotions Based on Seasonality.** Align campaigns with peak sales periods (October–December, Thursdays) while avoiding over-reliance on heavy discounts to protect margins.  
5. **Manage Outlier Risks and Opportunities.** Identify and track high-value transactions and large loss deals to mitigate risks and uncover targeted upselling potential.  
6. **Refine SMB Strategy.** Reduce dependence on steep discounts in SMB segment and encourage upgrades to premium products and automated services to improve margin and efficiency.

---

## Tools and Technologies  
- **Python:** Data wrangling, analysis, and visualization  
- **Jupyter Notebook:** Interactive documentation and exploration  
- **Pandas, NumPy:** Data manipulation and analysis  
- **Seaborn, Plotly, Matplotlib:** Exploratory and interactive visualizations  
- **Scikit-Learn:** Customer segmentation and predictive analysis  
- **Looker Studio:** Visual dashboards for stakeholders  
- **Figma Slides:** Presentation of findings  

---

## How to Use the `.ipynb`

1. **Prepare Python Environment**  
   Ensure Python 3.10 or newer is installed.

2. **Install Dependencies**  
   Run the following command in the terminal:  
   ```bash
   pip install pandas numpy matplotlib seaborn plotly scikit-learn

3. **Open the analysis notebook**  
Use Jupyter Notebook, Google Colab, or VSCode to open:  
- Capstone 3 Eng.ipynb

4. **Follow the analysis workflow**  
- Data preprocessing and exploratory analysis  
- Customer segmentation (RFM and CLV)  
- Evaluation of discounts, margins, and profitability  
- Churn and outlier analysis  
- Insights and strategic recommendations

---

## Link Presentasi

[Capstone 3 –Enhancing SaaS Revenue through Data Driven Sales and Customer Analytics (Figma Slides)](https://www.figma.com/deck/YhycFILOuPeEm7JfbzrglG/Capstone-3?node-id=3-118&t=KGkFBTanc0tgrxAW-1)

---

## Link Looker

[Capstone 3 –Enhancing SaaS Revenue through Data Driven Sales and Customer Analytics (Google Looker Studio)](https://lookerstudio.google.com/reporting/c582073a-22dd-4d03-a820-edfcb5c507aa)

---
