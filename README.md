# Global Arms Trade and Military Spending Dashboard (1970s–2022)

## Project Objective
The objective of this project is to provide an interactive Excel dashboard analyzing global arms trade and military spending trends from the 1970s to 2022. It allows users to explore arms imports and exports, defense spending as a percentage of GDP, and total military personnel over time. The dashboard also compares BRICS and G7 countries to highlight key differences in defense strategies and spending priorities. This tool is designed to support researchers, policy analysts, and stakeholders in understanding global defense dynamics.

## Dataset Used
Data sourced from Gapminder.  
[Gapminder Global Arms Data](https://github.com/open-numbers/ddf--gapminder--systema_globalis/blob/master/countries-etc-datapoints/ddf--datapoints--arms_exports_us_inflation_adjusted--by--geo--time.csv)

## Questions
- Which countries are the largest arms exporters and importers, and how has this changed over time?  
- How dependent are different regions (e.g., Africa) on arms imports compared to exports?  
- How do BRICS and G7 countries differ in arms trade volume and defense strategies?  
- Which nations maintain the largest and smallest military forces worldwide?  
- How does military spending as a percentage of GDP vary across countries and regions?  
- What were the trends in U.S. arms exports during the War on Terror (2001–2011)?  

## Process
- Collected four datasets from Gapminder: arms exports, arms imports, military spending (% GDP), and total military personnel.  
- Combined them into one Excel file for integrated analysis.  
- Used Power Query to:  
  - Unpivot and restructure the datasets into long format.  
  - Standardize date and country identifiers.  
  - Remove nulls and tidy column formats.  
  - Add calculated measures for comparisons (e.g., % share of global exports, total personnel by income group).  
- Built interactive Excel visuals and slicers to explore data by country, region, and economic group.  
- Designed a dashboard to compare BRICS and G7 defense patterns across time.  

## Dashboard
![Dashboard Screenshot](https://github.com/youneselkaisi/Global-Arms-Trade-Dashboard/blob/main/Dashboard%20screenshot.png)

## Project Insights
- The USA consistently leads global arms exports with **$14.5B in 2022**, far surpassing France ($3.0B) and Russia ($2.8B).  
- **Africa** relies heavily on imports, with 93.7% of its arms trade being inbound.  
- Among **BRICS**, India is the largest arms importer ($2.85B), while the USA leads the **G7** with $837M. In recent years, BRICS nations have narrowed the gap with the G7 in arms trade.  
- Countries like **Luxembourg** and **Nigeria** contribute negligible arms exports (<$10M), highlighting limited participation.  
- **China (2.99M)** and **India (2.75M)** lead in military personnel, far exceeding the USA (1.43M).  
- **Haiti (120)** and **Iceland (200)** maintain the smallest forces, often relying on partnerships for security.  
- **Upper-Middle Income countries** collectively employ 9.9M personnel, more than High-Income nations (5.4M).  
- Countries such as **Libya, Saudi Arabia, and Oman** allocate very high percentages of GDP to defense, while Western nations like Germany, Japan, and Canada spend far less (around 1–2% of GDP).  
- During the **War on Terror (2001–2011)**, U.S. arms exports nearly doubled (from $4.9B to $8.9B), with Saudi Arabia, UAE, and Egypt as the top buyers.  

## Conclusion
The Global Arms Trade and Military Spending Dashboard reveals how defense priorities vary widely across regions, economic groups, and time. The USA remains the dominant exporter, while Africa is heavily reliant on imports. BRICS nations are rapidly approaching G7 levels of arms trade activity, reflecting shifting global power dynamics. Military personnel distributions show the demographic and strategic weight of Asia, while spending patterns highlight the differing defense philosophies of oil-rich Middle Eastern states versus Western allies. This dashboard equips policymakers, researchers, and analysts with insights into long-term global defense trends.
**
