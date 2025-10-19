# Capstone Project – Hacktiv8 x IBM
# link colab: [https://colab.research.google.com/drive/19iZ56Vc5_WBjKDSLUK0hPtQ9oysGATsq?usp=sharing]
# Regional Analysis of Electricity Consumption and Efficiency in Indonesia: The Impact of GRDP and Population on National Electricity Demand Using IBM Granite AI (2017–2023)

## Project Overview
Electricity is a vital component of economic development and public welfare. Along with economic and population growth, national electricity demand in Indonesia has shown a consistent upward trend over the years.
This project analyzes interprovincial electricity consumption in Indonesia from 2017 to 2023, focusing on the influence of Gross Regional Domestic Product (GRDP) and population size on national electricity demand.
In addition to traditional statistical and visualization methods, the project integrates IBM Granite AI to:
1. Classify provinces based on energy efficiency levels (Low, Medium, High).
2. Generate automated insights and policy recommendations for sustainable national energy planning.
The analysis provides valuable information for PLN (the State Electricity Company), the Ministry of Energy and Mineral Resources (ESDM), and regional governments in developing data-driven, equitable, and efficient energy distribution strategies across Indonesia.


## Raw Dataset
All datasets used in this project are publicly available from **Statistics Indonesia (BPS)**.

- **Gross Regional Domestic Product (GRDP) by Province**  
  [https://www.bps.go.id/id/statistics-table/3/WkdVMWRYVnBkMnBvVEhKSVkyWXhNblZtTjJSbmR6MDkjMw==/produk-domestik-regional-bruto-atas-dasar-harga-berlaku---menurut-provinsi--miliar-rupiah---2022.html?year=2017]

- **Electricity Distributed by Province (GWh)**    
  [https://www.bps.go.id/id/statistics-table/2/ODU5IzI=/listrik-yang-didistribusikan-menurut-provinsi-]

- **Population by Province**   
  [https://www.bps.go.id/id/statistics-table/3/V1ZSbFRUY3lTbFpEYTNsVWNGcDZjek53YkhsNFFUMDkjMyMwMDAw/jumlah-penduduk--laju-pertumbuhan-penduduk--distribusi-persentase-penduduk--kepadatan-penduduk--rasio-jenis-kelamin-penduduk-menurut-provinsi.html?year=2023]

## Insight & Findings
This analysis shows that Indonesia’s national electricity consumption experienced a consistent increase during the 2017–2023 period, in line with the growth of the Gross Regional Domestic Product (GRDP) and population across almost all provinces.  
Java Island dominates national electricity consumption, contributing more than 70% of total usage, followed by Sumatra with around 16%, while other regions such as Kalimantan, Sulawesi, Bali–Nusa, and Papua record significantly lower consumption levels.  
These differences reflect disparities in electricity consumption closely related to the concentration of economic activities and the distribution of energy infrastructure.

Statistically, the results indicate a very strong relationship between electricity consumption and both GRDP (r = 0.91) and population (r = 0.90).  
This confirms that economic and demographic growth are the main factors driving the increase in electricity demand at the national level.  
The multiple linear regression model produced an R² value of 0.884, meaning that almost all variations in electricity consumption can be explained by these two variables.  
Furthermore, GRDP was found to have a more dominant effect than population size, indicating that economic activity contributes more significantly to rising electricity demand than population growth alone.

The interprovincial energy efficiency analysis reveals considerable disparities.  
Several economically advanced provinces, such as those in Java and Bali, show relatively low levels of energy efficiency, while regions with lower levels of industrialization such as Kalimantan, Sulawesi, and Papua demonstrate relatively higher efficiency compared to their economic scale.  
Conversely, some provinces in Sumatra and Eastern Indonesia serve as positive examples, maintaining efficient electricity consumption despite smaller GRDP values.  
This suggests that economic progress does not always align with energy efficiency, highlighting the need for context-specific and regionally tailored policy approaches.

Based on these overall findings, it can be concluded that improving national energy efficiency and ensuring equitable electricity consumption depend not only on economic growth but also on strengthening energy infrastructure outside Java and implementing comprehensive efficiency policies.  
The recommended policy directions include:

1. **Increase investment in renewable energy** in provinces with high energy efficiency to serve as innovation hubs for clean energy.  
2. **Promote electricity efficiency** in industrial and household sectors within high-consumption regions such as Java and Bali.  
3. **Develop data-driven energy policies** to support long-term planning and sustainable electricity consumption monitoring.  
4. **Expand equitable electricity access** to enhance energy security and foster balanced regional economic growth.

## AI Support Explanation
An analytical model (IBM Granite 3.3–8B) was implemented through the LangChain–Replicate integration on Google Colab to enhance the depth and interpretability of the statistical results.  
The model supported three main analytical components:

1. **Energy Efficiency Classification** – IBM Granite automatically classified provinces into low, medium, and high efficiency levels using the ratio of GRDP per capita to electricity consumption per capita.  
2. **Strategic and Policy Analysis** – The model provided data-driven policy recommendations for improving regional efficiency and promoting balanced electricity distribution across provinces.  
3. **AI-Generated Summary and Statistical Interpretation** – AI Granite summarized key national visualization and regression findings, highlighting major trends in electricity demand, economic growth, and population dynamics to ensure the insights were analytically sound and contextually relevant.

This analytical support ensures that the overall findings are both quantitatively robust and contextually meaningful, aligning statistical evidence with strategic recommendations for sustainable national energy management.
