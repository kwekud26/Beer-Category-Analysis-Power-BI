# Beer Category Performance Analysis – Power BI (Molson Coors Sample Data)

A complete CPG analytics case study evaluating Beer category performance for a retailer using **sample data provided for an interview with Molson Coors**.  
Built in **Power BI** with category diagnostics, subsegment insights, and brand-level opportunity identification.

---

## Beer Category Dashboard – Power BI

An end-to-end analytics project analyzing retailer vs. total market performance across the Beer category.  
The dashboard answers three key questions:

1. How is the Beer category performing at the retailer vs. the Total Market?  
2. Which subsegments are driving growth or decline?  
3. Which subsegment and brands offer the greatest opportunity to improve retailer performance?

---

## Project Links

> 🔗 **GitHub Repository:** (add your repo link here)  
> 🔗 **Sample Dataset (optional):** (add link or note if not shared)

---

## Table of Contents
- [Project Overview](#project-overview)
- [Project Scope](#project-scope)
- [Business Objective](#business-objective)
- [Document Purpose](#document-purpose)
- [Use Case](#use-case)
- [Skills Demonstrated](#skills-demonstrated)
- [Data Source](#data-source)
- [Data Preparation & Processing](#data-preparation--processing)
- [Insights Summary (Questions 1–3)](#insights-summary-questions-13)
  - [Question 1: Category Performance](#question-1--category-performance)
  - [Question 2: Subsegment Drivers](#question-2--subsegment-drivers)
  - [Question 3: Brand Opportunity & Recommendation](#question-3--brand-opportunity--recommendation)
- [Recommendation Summary](#recommendation-summary)
- [Conclusion](#conclusion)
- [Built With](#built-with)
- [Roadmap](#roadmap)
- [Contact](#contact)

---

## Project Overview

This project evaluates the **Beer category** performance at a retailer and compares it to the **Total Market** using sample data provided by Molson Coors for an interview case study.

The analysis focuses on:

- Overall category performance (Retailer vs. Total Market)  
- Subsegment-level growth and decline  
- Brand-level optimization opportunities within a chosen subsegment (Malt Liquor)  

All insights are built into a **3-page Power BI dashboard**:

1. **Category Performance Overview**  <img width="1310" height="721" alt="image" src="https://github.com/user-attachments/assets/77819a4a-2881-40f6-add0-d3c32ed03572" />

2. **Subsegment Growth & Decline Analysis**  <img width="1307" height="733" alt="image" src="https://github.com/user-attachments/assets/05c30395-daff-43a8-8aa1-d5ba3e5ae504" />

3. **Brand Opportunity & Recommendations** <img width="1313" height="728" alt="image" src="https://github.com/user-attachments/assets/25f7ae9b-1e09-47e4-8265-afdfc7e4c29d" />


---

## Project Scope

- Analyze retailer vs. total market Beer category performance  
- Combine Spirits, Total Beer, and Beer Alternatives into a total category view  
- Identify which subsegments drive growth and decline  
- Drill into a high-opportunity subsegment (Malt Liquor)  
- Evaluate brand-level performance, price, and unit trends  
- Provide actionable recommendations to improve retailer outcomes  

---

## Business Objective

Provide the retailer with:

- A clear understanding of how the Beer category is performing vs. the Total Market  
- Insight into which subsegments are driving growth or decline  
- Identification of underperforming brands where there is clear upside  
- Data-driven recommendations to recover share and improve sales

---

## Document Purpose

This project demonstrates a **full analytics workflow** typical of a Category Manager or Category Analyst in CPG:

- From sample data → to modeling → to visualization → to insights → to recommendations  
- Combines technical skills (Power BI, DAX) with commercial thinking (pricing, subsegment roles, brand strategy)

---

## Use Case

**Scenario:**  
A retailer wants to understand why its Beer category is underperforming slightly versus the Total Market and where it has the biggest opportunities to improve.  

This analysis helps them:

- See total category performance vs. market  
- Understand which subsegments are growing/declining  
- Focus on a high-opportunity subsegment (Malt Liquor)  
- Act on specific brand-level recommendations

---

## Skills Demonstrated

- Power BI data modeling & dashboard design  
- DAX measures and calculated columns  
- Category management analytics (CPG-focused)  
- Retailer vs. Total Market performance comparison  
- Price, unit, and dollar performance analysis  
- Subsegment growth/decline diagnostics  
- Brand opportunity sizing and prioritization  
- Business storytelling and executive-ready documentation  
- GitHub documentation and project organization  

---

## Data Source

- **Provider:** Sample data used for an interview case study  
- **Format:** Excel/CSV  
- **Category:** Beer (Spirits, Total Beer, Beer Alternative)  
- **Key Fields:** Dollar Sales, Unit Sales, Price, Category, Subsegment, Brand/Franchise, Market vs. Retailer splits  
- **Note:** Data is **sample/mock**, contains **no real client names**, and is safe for public portfolio use.

---

## Data Preparation & Processing

- Cleaned and standardized category and subsegment fields  
- Created measures for:
  - Dollar % Change (Current Year vs. Year Ago)  
  - Unit % Change  
  - Price Change  
- Defined total category by summing:
  - Spirits  
  - Total Beer  
  - Beer Alternatives    
- Added conditional formatting (red/yellow/green) for quick performance diagnostics  

---

## Insights Summary (Questions 1–3)

### Question 1 – Category Performance  

<img width="1310" height="721" alt="image" src="https://github.com/user-attachments/assets/77819a4a-2881-40f6-add0-d3c32ed03572" />


> **How is the Beer category performing at the retailer, and how does that compare to the Total Market?**

- When Spirits, Total Beer, and Beer Alternatives are combined, the retailer is down **–3.55%**, while the Total Market is down **–3.42%**.  
- This indicates the retailer is **slightly underperforming** the market.  
- The primary driver is **Total Beer**, which represents the majority of category volume and is declining more at the retailer than in the market.  
- Spirits and Beer Alternatives perform relatively better but are too small to offset the Total Beer decline.

**Key Insight:**  
The retailer’s underperformance is mostly driven by a deeper decline in **Total Beer**, not by the entire category moving differently.

---

### Question 2 – Subsegment Drivers

<img width="1307" height="733" alt="image" src="https://github.com/user-attachments/assets/05c30395-daff-43a8-8aa1-d5ba3e5ae504" />

> **What subsegments are driving growth or decline in the category?**

**Growth Drivers:**

- **Spirits-Based Premixed Cocktails (RTDs)** – strongest positive contributor  
- **Super Premium** – solid growth and meaningful dollar impact  
- **Cider** – smaller but positive contribution  

**Decliners:**

- **Seltzers (RTDs)** – largest negative driver  
- **Premium Light** – notable contraction  
- Several core beer subsegments also show year-over-year declines  

**Key Insight:**  
Category growth is concentrated in **premium and RTD-style subsegments**, while declines are driven primarily by traditional beer and Seltzers.

---

### Question 3 – Brand Opportunity & Recommendation 

<img width="1313" height="728" alt="image" src="https://github.com/user-attachments/assets/273b1235-2cc2-41a1-a44d-78345cf48091" />


> **Select one subsegment and provide a recommendation on which brand(s) the retailer has the greatest opportunity to improve performance on.**

I selected **Malt Liquor** as the key opportunity subsegment because the **Total Market is growing**, while the retailer is **declining**, indicating lost share and missed demand.

Within Malt Liquor, two brands stand out:

#### Agile Cassowary

- Retailer dollar sales: **–16.98%**  
- Total Market dollar sales: **+4.60%**  
- Retailer unit price **decreased** from **$2.55 → $2.51**, yet sales still declined  
- Market price is lower at **$2.31**  

**Insight:**  
The fact that sales declined even after a price reduction suggests that **price is not the primary issue**.  
This points to deeper issues such as:

- Distribution gaps  
- Poor shelf visibility  
- Fewer facings vs. competitors  
- Weaker in-store execution

Simply lowering price further is unlikely to fix the decline on its own.

---

#### Agile Donkey

- Retailer dollar sales: **+7.59%**, showing positive momentum  
- Retailer price: **$5.20** vs. Market price: **$3.11**  
- Total Market unit growth suggests additional upside if pricing is more competitive  

**Insight:**  
There is still headroom to grow Agile Donkey. The large price premium likely holds back even stronger unit growth. Tactical price reductions or feature promotions could unlock additional volume.

---

## Recommendation Summary

To improve Malt Liquor performance, the retailer should:

- **Agile Cassowary**
  - Focus on distribution, facings, and visibility rather than only price  
  - Ensure consistent in-stock position and competitive shelf placement  
  - Consider promotional support to re-engage shoppers  

- **Agile Donkey**
  - Reduce the price gap or use targeted temporary price reductions (TPRs)  
  - Support with features, displays, or digital activation to drive trial  

By addressing **execution for Agile Cassowary** and **pricing for Agile Donkey**, the retailer can better participate in the growth that the Total Market is already experiencing in Malt Liquor.

---

## Conclusion

This Power BI project shows how a Category Analyst can:

- Diagnose retailer vs. market performance  
- Identify which subsegments are driving trends  
- Drill down to brand-level performance and pricing dynamics  
- Turn data into clear, actionable recommendations  

The approach is directly applicable to real CPG category management and retail collaboration.

---

## Built With

- **Power BI Desktop**  
- **DAX**  
- **Excel / CSV**  
 

---

## Roadmap

- Add decomposition trees for deeper subsegment and brand drill-down  
- Integrate forecast models to project future subsegment trends  
- Publish an interactive version via Power BI Service or embedded link  
- Add scenario analysis (e.g., price elasticity simulations)  

---

## Contact

**Kweku Darko**  
Email: **kaydarko7@gmail.com**  
LinkedIn: **[Kweku Darko](https://www.linkedin.com/in/kweku-darko-b880b4161/)**  

> *This project uses sample/mock data provided for interview practice and contains no real client or retailer names.*
