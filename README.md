# 🌊 Aquaculture Market Analysis: Identifying High-Potential Countries for Expansion

### *Still a draft

## 📖 Introduction
This project analyzes global aquaculture production data to uncover trends, top species, and countries with high potential for market expansion. 

Assumed business case: You're a data analyst at a company that sells aquaculture tools and want to identify **top 5 target countries** to expand into, based on **volume, growth rate, and species trends**.

## 📂 Dataset Description
- Source: [FAO Fishery Statistics](https://www.fao.org/fishery/statistics-query/en/global_production/global_production_quantity)
- Years: 2000–2024
- Fields: Country, Species, Year, Source (Capture/Aquaculture), Production (tons)

## 🧼 Data Cleaning Summary
- Edited the name of the column
- Filtered Aquacultur
- Aggregated by country/species/year
- Handled missing values and zeros

## 📊 Exploratory Data Analysis (EDA)
Key questions answered:
- Which countries produce the most from aquaculture?
- How has production changed over time?
- What are the top aquaculture species globally and per country?
- Where do sudden drops or increases occur (e.g., Indonesia seaweed in 2021)?

![Top Producers, *remember to add the embeded](visuals/top_producers.png)

## 🔬 Trend Analysis & Country Ranking
- Used linear regression to calculate production growth rate (2010–2024)
- Combined total production + growth with a weighting system
- Selected 5 high-potential countries based on:
   - High production volume
   - Positive growth rate
   - Dominant aquaculture species

## 📈 Clustering & Segmentation
- PCA used to reduce dimensionality of country-species production matrix
- KMeans clustering revealed 4 groups of countries with similar species profiles
- Identified dominant species per cluster for marketing targeting

![Embed the table here](visuals/top_producers.png)

## 🧠 Final Business Insights
- Recommend expansion into: Indonesia, India, Bangladesh, Vietnam, Egypt
- Reasoning:
   - Strong production
   - High or consistent growth
   - Common species: Tilapia, Carp, Seaweed
- Each cluster can inform product strategy (e.g., tech intensity, pricing)

## 🚀 How to Run, fix this later
git clone https://github.com/yourusername/aquaculture-market-analysis.git
cd aquaculture-market-analysis
jupyter notebook

## 🙋‍♂️ About Me
I'm Fadil M Nasrudy, a data analyst transitioning from fisheries science into data analytics. This project shows my ability to combine domain expertise with analytical thinking and present actionable insights for business decisions.







