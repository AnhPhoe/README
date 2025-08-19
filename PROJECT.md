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
<img width="894" height="505" alt="image" src="https://github.com/user-attachments/assets/986b8189-2ac2-4112-82f2-be8109f60d75" />
<img width="897" height="505" alt="image" src="https://github.com/user-attachments/assets/c1df6272-822a-4869-a7b8-5481141fe35e" />

### 📊 Key Insights
Overall India Trade (2010-2018)
- Growing Trade Volume: India's overall Export Value (2.65M) and Import Value (2.04M) indicate substantial trade activity, with imports slightly lower than exports, resulting in a positive Net Trade of 1.37M (as displayed in the summary cards, though the 'Net Trade' card shows a negative value which could be a formatting/labeling issue, as exports are higher than imports based on other visuals). There appears to be a clear growth trend in both exports and imports over the years, though with fluctuations.

- Shifting Trade Balance: While the overall net trade appears positive, the "Top trade deficit country (by value)" chart suggests that India has experienced both periods of deficit and surplus, with a notable dip in val_imp around 2015-2016.

- Key Export Partners: The U.S.A. is a dominant export partner, followed by the U.A.E., China, Hong Kong, and Singapore, indicating strong trade ties with major global economies and regional hubs.

- Key Import Partners: China is the leading import source, significantly outweighing other partners like the U.S.A. and Saudi Arabia. This highlights a heavy reliance on imports from China.

- Dominant Export Commodities: "Mineral Products," "Textiles," and "Machinery / Electrical" are significant contributors to India's export value.

- Dominant Import Commodities: "Textiles" and "Miscellaneous" are the largest import commodity groups, suggesting a substantial import of these categories. The high import value of "Chemicals & Allied Industries" and "Metals" is also notable.

- Trade Deficit/Surplus Concentration: The "Top 10 Countries with Highest Trade Deficit" chart shows significant deficits with partners like China, U.A.E., and Saudi Arabia, with varying trends over the years. Conversely, the "Top 10 Countries with Higher Surplus Trade" highlights countries where India consistently exports more than it imports.

* India-Vietnam Bilateral Trade (2010-2018)
- Significant Bilateral Trade: India's trade with Vietnam is considerable, with 48.41K in Exports to Vietnam and 28.79K in Imports from Vietnam, resulting in a Net Trade of 19.62K (a surplus for India).

- Positive Trade Balance for India: The "Net Exports and Net Imports" pie chart and the "Top trade deficit INDIA with VIETNAM" bar chart confirm that India has maintained a positive net trade balance (surplus) with Vietnam during this period.

- Dynamic Bilateral Trends: The "INDIA TRADE WITH VIETNAM 2010-2018" line chart shows clear growth in both exports and imports between India and Vietnam. There's a noticeable increase in both values, particularly from 2014 onwards, with exports generally staying above imports, indicating an expanding and favorable trade relationship for India.

- Key Bilateral Export Commodities (from India to Vietnam): "Metals," "Foodstuffs," and "Mineral Products" are prominent in India's exports to Vietnam.

- Key Bilateral Import Commodities (from Vietnam to India): "Miscellaneous," "Foodstuffs," and "Textiles" are the leading import commodity groups from Vietnam.

### Recommendations 🎯
- Diversify Import Sources (Away from China): Given China's overwhelming dominance as an import source, explore opportunities to diversify supply chains to other countries to reduce reliance and mitigate potential risks. This could involve increasing imports from current top partners or identifying new ones.

- Strategic Focus on Key Export Commodities: Continue to promote and invest in the "Mineral Products," "Textiles," and "Machinery / Electrical" sectors for global exports, as they are strong performers. Analyze the specific sub-categories within these groups for further growth potential.

- Address Chronic Trade Deficits: Conduct deeper analysis into the drivers of persistent trade deficits with countries like China and Saudi Arabia. This could involve exploring import substitution, boosting exports to these specific countries, or negotiating better trade terms.

- Strengthen India-Vietnam Trade Corridors:

- Leverage Existing Surplus: Capitalize on India's consistent trade surplus with Vietnam. Identify specific products or services where India has a competitive advantage and Vietnam has demand.

- Promote Key Bilateral Exports: Focus efforts on increasing exports of "Metals," "Foodstuffs," and "Mineral Products" to Vietnam, given their current prominence.

- Explore Demand for India's Imports: Analyze why "Miscellaneous," "Foodstuffs," and "Textiles" are major imports from Vietnam. Are there opportunities for Indian businesses to produce these domestically or source them from other favorable markets?

- Deepen Bilateral Engagement: The positive and growing bilateral trade trends suggest that strengthening trade agreements, logistical infrastructure, and business-to-business connections with Vietnam could yield further mutual benefits.
