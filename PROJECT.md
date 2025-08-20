# FINAL PROJECT - INDIA TRADE

## 1 Goals of the project 🎯
The primary goal of this project is to comprehensively analyze India's trade performance from 2010 to 2018. This includes monitoring overall export/import trends, identifying top global trading partners, and understanding dominant commodity groups. As an additional, focused task, the dashboard will also provide a detailed analysis of India's bilateral trade specifically with Vietnam during the same period.

### 1.1 Purpose:
To achieve these goals, the dashboard will be structured into two main analytical sections:
* Overall India Trade Performance (Main Dashboard): This section will provide a high-level overview of India's total trade, including:
* Overall export, import, and net trade values.
* Year-over-year trends for total exports, imports, and net trade.
* Top 10 global trading partners by both export and import value.
* Breakdown of total export and import values by major commodity groups.
* Analysis of India's global trade surplus and deficit with various countries.

Bilateral India-Vietnam Trade Deep Dive: This section will focus exclusively on the trade relationship between India and Vietnam, showcasing:
* Total export, import, and net trade values specifically between India and Vietnam.
* Year-over-year trends of India's exports to and imports from Vietnam.
* The trade balance (surplus/deficit) specific to India's trade with Vietnam.
* Identification of top commodity groups imported from and exported to Vietnam.

### 1.2 Key Analytical Questions:
Overall India Trade Analysis
* What are India's total export, import, and net trade values between 2010 and 2018?
* How have India's overall export and import values evolved annually during this period, indicating growth or decline trends?
* What is the overall trend of India's global net trade (trade balance) year-over-year?
* Which are India's top 10 global trading partners by both export and import value?
* Which countries contribute most to India's overall trade surplus and deficit, and how has this changed annually?
* What are the primary commodity groups driving India's total exports and imports by value?

Bilateral India-Vietnam Trade Analysis (Additional Task)
* What are the total export, import, and net trade values between India and Vietnam from 2010 to 2018?
* How have India's exports to Vietnam and imports from Vietnam changed year-over-year? What are the growth rates and key fluctuations?
* What is the specific trade balance (net trade) trend between India and Vietnam over time, and what is India's position (surplus/deficit)?
* What are the most significant commodity groups that India imports from Vietnam and exports to Vietnam?
* How does this bilateral trade contribute to India's overall global trade figures?

## 2 Data sources 🗂️
Name: India - Trade Data (https://www.kaggle.com/datasets/lakshyaag/india-trade-data/data)
The data set 2018-2010_export.csv and 2018-2010_import.csv with data on: export and import 

## 3 Data overview 🔍
Structure:
* HS code: HS stands for Harmonized System. It was developed by the WCO (World Customs Organization) as a multipurpose international product nomenclature that describes the type of good that is shipped HS Code Structure.
* Commodity: the column contains chapter wise commodity category. In each commodity Category there are various commodities.
* Value: values for export and import of commodities in million USD.
* Country: countries imported/ exported.
* Year: that commodities imported/ exported between 2010 to 2021.

## 4 Methodology
### 4.1 Analytical tools used in the project 📚
* Language: Python
* Analysis: pandas, numpy
* Visualization: matplotlib, seaborn, Power BI
* Browser-based coding environment: Google Colab/Jupyter Notebook
### 4.2 Exploratory Data Analysis (EDA) 🕵️‍♀️
Data Understanding & Quality Check:
- Variables:
- Geographic: country (e.g., India, Vietnam, USA).
- Temporal: year (2010-2018).
- Numerical Measures: val_exp (export value), val_imp (import value), net_trade (calculated as val_exp - val_imp).
- Categorical: CommodityGroup (e.g., Textiles, Machinery, Mineral Products).

Initial Explorations (Hypothesis Generation):
- Overall Trends: What are the general trends for India's total exports, imports, and net trade between 2010 and 2018? Is trade growing, declining, or stable?
- Top Partners: Which countries are consistently India's top 10 export and import partners? Have these rankings changed over time?
- Commodity Dominance: Which CommodityGroups dominate India's exports and imports? Are there shifts in key commodities over the years?
- Trade Balance Drivers: What factors (countries, commodities) contribute most significantly to India's trade surplus or deficit?

### 4.3 Visualization & Storytelling
Visualizations for EDA:
* During EDA, visuals are used for discovery, not just presentation.
* Line charts: To observe val_exp, val_imp, and net_trade trends over year for India overall, and then specifically for India-Vietnam trade.
* Bar charts: To rank top 10 countries by val_exp and val_imp, and for Top 10 countries with higher surplus trade and Top 10 countries with highest trade deficit.
* Treemaps/Bar charts: To analyze Export value by CommodityGroup and Import value by CommodityGroup (e.g., showing proportion of value).
Scatter plots (optional): To check for correlations between val_exp and val_imp.
* Card visuals: To quickly display total VALUE EXPORT, VALUE IMPORT, and NET TRADE.

## 5 Results
<img width="777" height="438" alt="image" src="https://github.com/user-attachments/assets/4da686b5-a17f-47cd-b75f-f632089bde73" />
<img width="777" height="442" alt="image" src="https://github.com/user-attachments/assets/785f7798-60a6-4a1a-a6a0-240f54d6127e" />


### 📊 Key Insights
Overall India Trade (2010-2018)
- Growing Trade Volume: India's overall Export Value (2.65M) and Import Value (2.04M) indicate substantial trade activity, with imports slightly lower than exports, resulting in a positive Net Trade of 1.37M (as displayed in the summary cards, though the 'Net Trade' card shows a negative value which could be a formatting/labeling issue, as exports are higher than imports based on other visuals). There appears to be a clear growth trend in both exports and imports over the years, though with fluctuations.

- Shifting Trade Balance: While the overall net trade appears positive, the "Top trade deficit country (by value)" chart suggests that India has experienced both periods of deficit and surplus, with a notable dip in val_imp around 2015-2016.

- Key Export Partners: The U.S.A. is a dominant export partner, followed by the U.A.E., China, Hong Kong, and Singapore, indicating strong trade ties with major global economies and regional hubs.

- Key Import Partners: China is the leading import source, significantly outweighing other partners like the U.S.A. and Saudi Arabia. This highlights a heavy reliance on imports from China.

- Dominant Export Commodities: "Mineral Products," "Textiles," and "Stone/ Glass" are significant contributors to India's export value.

- Dominant Import Commodities: "Textiles" and "Miscellaneous" are the largest import commodity groups, suggesting a substantial import of these categories. The high import value of "Chemicals & Allied Industries" and "Metals" is also notable.

- Trade Deficit/Surplus Concentration: The "Top 10 Countries with Highest Trade Deficit" chart shows significant deficits with partners like China, U.A.E., and Saudi Arabia, with varying trends over the years. Conversely, the "Top 10 Countries with Higher Surplus Trade" highlights countries where India consistently exports more than it imports.

* India-Vietnam Bilateral Trade (2010-2018)
- Growing Trade Volume & Favorable Balance: India's trade with Vietnam has shown significant growth. With $48.41K in Exports to Vietnam and $28.79K in Imports from Vietnam, India maintains a healthy Net Trade surplus of $19.62K with Vietnam. This indicates a mutually expanding trade relationship where India's exports to Vietnam are consistently higher than its imports from Vietnam.

- The "Net Exports and Net Imports" pie chart visually confirms this, with exports (62.67%) significantly outweighing imports (37.33%) in value.

- Strong Growth Trajectory: The "INDIA TRADE WITH VIETNAM 2010-2018" line chart clearly illustrates a robust upward trend in both India's exports to and imports from Vietnam over the period. Both VALUE EXP and VALUE IMP lines show consistent, sometimes rapid, growth, indicating deepening trade ties. There's a notable surge in values from around 2014-2015 onwards.

- Specific Trade Balance Dynamics: The "Top trade deficit INDIA with VIETNAM" bar chart, despite its label, actually shows India's positive net trade balance with Vietnam increasing over the years, particularly after 2014-2015. This reinforces India's surplus position in this bilateral relationship.

- Key Bilateral Export Commodities (from India to Vietnam): "Animal & Animal Products" leads significantly at $383.41K, followed by "Vegetable Products" ($76.21K) and "Textiles" ($53.85K). "Metals" and "Chemicals & Allied Industries" also contribute substantially. This suggests India primarily exports raw materials, agricultural products, and some manufactured goods to Vietnam.

- Key Bilateral Import Commodities (from Vietnam to India): "Miscellaneous" dominates imports from Vietnam at $39.38K, followed by "Foodstuffs" ($37.94K), "Textiles" ($32.86K), and "Wood & Wood Products" ($28.52K). "Metals," "Chemicals & Allied Industries," and "Mineral Products" are also notable. This indicates India imports a diverse range of finished or semi-finished goods, agricultural products, and some raw materials from Vietnam.

### Recommendations 🎯
- Boost Exports: Focus on enhancing the competitiveness and volume of exports in dominant sectors like "Mineral Products," "Chemicals & Allied Industries," and "Machinery & Electrical." Explore new markets for these products.

- Diversify Import Sources: Reduce over-reliance on single import sources, particularly China. Actively seek alternative suppliers for key import commodities to mitigate supply chain risks and potentially improve terms of trade.

#### Strategic Engagement with Key Partners:

- Leverage Export Strength: Strengthen trade relationships with top export partners like the U.S.A. to further increase market access and volume.

- Target Deficit Partners: Implement specific strategies to reduce deficits with countries like China and Saudi Arabia. This could involve promoting Indian exports to these nations or exploring opportunities for import substitution.

#### Commodity-Specific Strategies:

- Export Promotion: Analyze the growth potential of current top export commodity groups. Identify emerging sectors where India can build export capacity.

- Import Optimization: For major import commodities, evaluate if domestic production can be ramped up, or if more cost-effective import sources exist.

- Long-term Trade Policy Review: The consistent deficit trend suggests a need for a deeper review of India's long-term trade policies, including tariffs, subsidies, and export promotion schemes, to foster sustainable trade growth and reduce the deficit.

#### Sustain and Expand Export Growth to Vietnam:

- Capitalize on the strong performance of "Animal & Animal Products" and "Vegetable Products" in exports to Vietnam. Explore opportunities to expand these sectors.

- Investigate the potential for growth in other emerging export commodities that currently have smaller shares but high demand in Vietnam (e.g., machinery, electronics, pharmaceuticals).

#### Optimize Import Basket from Vietnam:

- Analyze the "Miscellaneous" category of imports from Vietnam to understand the specific products driving this high value. This could reveal opportunities for import substitution or strategic sourcing.

- Given the significant import of "Foodstuffs" and "Textiles" from Vietnam, explore opportunities for collaboration, joint ventures, or technology transfer to enhance domestic production or diversify import sources.

- Leverage Bilateral Agreements: Proactively engage in and leverage existing (or future) free trade agreements or bilateral investment treaties between India and Vietnam to further reduce trade barriers and facilitate smoother trade flows.

- Promote Value-Added Exports: While raw materials and agricultural products are strong, encourage and support Indian industries to export more value-added and finished goods to Vietnam, moving up the value chain.

- Strengthen Logistics and Connectivity: As trade volumes grow, assess and recommend improvements in shipping routes, port infrastructure, and customs procedures between India and Vietnam to enhance efficiency and reduce costs.

- Continuous Monitoring of Trade Balance: While currently in surplus, continuously monitor the "Net Trade" trend with Vietnam to ensure the balance remains favorable or aligns with strategic objectives. Investigate any significant shifts or sustained periods of decline in the surplus.
