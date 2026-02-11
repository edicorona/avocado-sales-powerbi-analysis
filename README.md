# avocado-sales-powerbi-analysis
Interactive Power BI analysis of U.S. avocado sales, pricing trends, and product mix (2015–2018).

Overview

This project analyzes U.S. avocado sales and pricing trends using Hass Avocado Board data (2015–2018).

The dashboard provides:
A category-level overview of total avocado sales (bagged + loose)
A deeper analytical focus on loose avocado performance by PLU (4046, 4225, 4770)
A pricing and demand analysis exploring the relationship between median average price and units sold
While both bagged and loose formats are included in overall category metrics, the primary analytical emphasis is placed on loose avocados, as they represent the majority of unit volume and provide greater SKU-level depth for analysis.

The report is structured to mirror how business stakeholders consume data: **orientation first, analysis second**.

---

## Dataset

**Source:** Hass Avocado Board (via Kaggle)
**Time Period:** 2015–2018

> 2018 data represents partial-year performance (Year-to-Date). It should not be interpreted as a full-year comparison.

**Key Fields:**

* Date (Year / Quarter / Month hierarchy)
* Region (U.S. metro markets)
* Product identifiers (PLUs 4046, 4225, 4770)
* Bag sizes (Small, Large, XLarge)
* Units sold
* Sales ($)
* Average price

Data is aggregated at the metro-market level.

---

## Dashboard Structure

### 1. Overview Page

Designed for first-glance orientation.

Includes:

* Total category sales (bagged + loose)
* Total units sold
* Packaging mix (bagged vs loose)
* Year-over-year sales trend

This page answers:

* How large is the avocado category?
* How has it changed over time?
* What packaging formats drive performance?

---

### 2. Loose & Bagged Breakdown

Drill-down pages allow users to explore:

* Loose avocado performance by PLU (4046, 4225, 4770)
* Bagged avocado performance by bag size
* Regional market performance
* Product line comparisons across years

Interactive slicers enable filtering by:

* Year
* Quarter / Month
* Region (Metro Areas)
* Product type (Conventional / Organic)

---

### 3. Pricing & Demand Analysis

The report includes a pricing analysis visual showing:

**Median Average Price vs Units Sold (Quarterly, with Monthly Drill-Down)**

* Default view displays quarterly trends
* Users can drill down to monthly levels
* Dual-axis visualization highlights price–volume dynamics

This analysis explores potential demand sensitivity patterns across time.

---

## Key Insights

* Loose avocados remain the dominant packaging format, though bagged products account for a significant and growing share of total volume.
* PLU 4225 consistently drives the highest unit volume among loose avocados.
* Total sales increased steadily from 2015 to 2017, with 2018 reflecting partial-year data.
* Higher median average prices are generally associated with lower units sold, suggesting price sensitivity within the category.

---

## Tools Used

* Power BI Desktop
* Power Query for transformation
* DAX for calculated measures
* Excel for preliminary inspection

---

## Notes & Limitations

* Data is aggregated at the metro-market level and does not represent individual transaction-level records.
* The dataset provides average prices by market and period; therefore, **median values of average price** were used in pricing comparisons to reduce distortion from extreme regional values.
* 2018 figures reflect Year-to-Date data and are not directly comparable to full-year totals from prior years.

---

## Viewing the Report

Screenshots are included in this repository.
The full interactive experience can be accessed by opening the `.pbix` file in **Power BI Desktop**.



