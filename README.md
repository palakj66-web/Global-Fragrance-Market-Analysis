# Global-Fragrance-Market-Analysis
Raw catalog data often contains unstructured formatting, delimiter issues, and duplicate listings. The objective of this project was to ingest 20,000+ unstructured perfume records, standardize data dimensions, and design an executive dashboard tracking international production, catalog size, and demographic targeting.

# 🌍 Global Fragrance Market Analysis Dashboard

## 📌 About This Project
An interactive Tableau analytics dashboard built on a dataset of over 20,000 perfumes. The objective was to transform raw, semi-structured catalog records into clear visual insights evaluating geographic manufacturing hubs, brand dominance, and demographic targeting.

---

## 🛠️ Technical Process & Methodology

- **Data Ingestion & Cleaning:** Resolved delimiter issues from the raw CSV using custom splits to standardize fields into **Perfume Name**, **Brand**, **Country**, and **Gender**.
- **Geographic Mapping:** Assigned geographic roles (`Country/Region`) to country attributes, generating spatial coordinates to plot a filled global origin map.
- **Accurate Aggregations:** Applied Distinct Count measures (`CNTD`) to evaluate unique perfume creations rather than raw row counts.
- **Top 10 Brand Ranking:** Built a descending horizontal bar chart filtered dynamically to the Top 10 brands by catalog volume (e.g., Avon, Zara, O Boticário, Guerlain, Dior).
- **Target Audience Segmentation:** Created a color-coded bar chart illustrating market volume across Women's, Unisex, and Men's lines.
- **Interactive Dashboard Actions:** Configured the global map to act as a cross-sheet filter (`Use as Filter`), enabling users to click any nation to view its domestic brand leaders and gender distributions.

---

## 💡 Key Findings
- **Geographic Concentration:** France, the United States, Italy, and Brazil lead total catalog entries globally.
- **Catalog Breadth:** Direct-to-consumer and fast-fashion giants (Avon, Zara) show catalog volumes that rival or exceed heritage Parisian luxury houses.
- **Category Trends:** While Women's scents hold the largest single share, Unisex lines represent a major segment reflecting growing gender-neutral accord trends.

---

## 📂 Source Data & Attribution
- **Dataset:** [Fragrantica Fragrance Dataset on Kaggle](https://www.kaggle.com/datasets/olgagmiufana1/fragrantica-com-fragrance-dataset)
- **Tools Used:** Tableau Desktop
