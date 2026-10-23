# Online Shoppers Intention Analysis 🛒

## Project Overview

This practice focuses on analyzing online shopping visitor behavior using the Online Shoppers Intention dataset.

The purpose is to understand purchasing behavior, explore the data, and identify patterns related to whether website visitors complete a purchase.

## Dataset Information

- **Dataset:** Online Shoppers Intention
- **File:** `online_shoppers_intention.csv`
- **Rows:** 12,330
- **Columns:** 18

## Tools Used

- Python
- Google Colab
- Pandas
- Matplotlib
- Microsoft Excel

## Objectives

- Explore the dataset and understand its structure.
- Examine the `Revenue` column.
- Count purchase sessions (`True`) and non-purchase sessions (`False`).
- Analyze purchase sessions by month.
- Create charts to visualize the results.
- Practice data analysis using Python and Excel.

## Key Columns

| Column | Description |
|---|---|
| `Month` | Month of the browsing session |
| `VisitorType` | Type of website visitor |
| `Weekend` | Whether the session occurred on a weekend |
| `ProductRelated` | Number of product-related pages visited |
| `ProductRelated_Duration` | Time spent on product-related pages |
| `Revenue` | Whether the session resulted in a purchase |

## Analysis Performed

### 1. Revenue Analysis

Compared sessions where `Revenue` was `True` with sessions where `Revenue` was `False`.

### 2. Revenue by Month

Grouped the data by month and counted the sessions that resulted in a purchase.

### 3. Data Visualization

Used Matplotlib to create a pie chart for purchase versus non-purchase sessions and a bar chart to compare purchase-session counts across months.

## Preliminary Findings

- November recorded 760 purchase sessions.
- February recorded 3 purchase sessions.
- Purchase-session counts varied across months.
- Purchase-session counts do not represent the amount of money earned.

These findings describe the number of sessions with purchases, not total sales revenue or the percentage of visitors who purchased.

## Files and Folders

- `online_shoppers_intention.csv` — Original dataset.
- `online_shoppers_analysis.xlsx` — Excel analysis workbook.
- `online_shoppers_analysis.ipynb` — Python analysis notebook from Google Colab.
- `images/` — Charts exported from the analysis.

## How to Reproduce the Analysis

1. Download the dataset and notebook.
2. Open the notebook in Google Colab.
3. Install or import the required Python libraries.
4. Load the dataset using Pandas.
5. Run the analysis cells.
6. Review the tables and charts.
7. Open the Excel workbook to review the Excel analysis.

## Future Improvements

- Analyze purchasing behavior by visitor type.
- Compare weekend and weekday sessions.
- Examine browsing duration and purchase behavior.
- Calculate monthly conversion rates.
- Add more charts and data-driven insights.

## Conclusion

This practice helped me develop my understanding of dataset exploration, grouping, aggregation, and visualization using Python. It also provides an opportunity to combine Python analysis with Excel.

**Status:** Ongoing learning practice.
