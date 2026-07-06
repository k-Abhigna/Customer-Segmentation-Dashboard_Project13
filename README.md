# Customer Segmentation Dashboard (RFM Analysis)

An interactive Power BI dashboard designed to segment a company's consumer base using the **RFM (Recency, Frequency, Monetary value)** marketing analysis model. This project evaluates purchasing patterns to help businesses understand customer behavior, optimize marketing strategies, and maximize customer lifetime value.

## 📊 About the Project

RFM analysis is a data-driven customer segmentation technique that allows businesses to group customers based on three core metrics:
*   **Recency ($R$):** How long ago a customer made their last purchase.
*   **Frequency ($F$):** How often a customer makes a purchase.
*   **Monetary Value ($M$):** How much money a customer spends.

By analyzing these behavioral indicators from the provided Asian market sales datasets, this dashboard categorizes customers into distinct segments (such as *Champions*, *Loyal Customers*, *At Risk*, or *Hibernating*) to drive targeted marketing campaigns.

## 🗂️ Repository Structure

The repository contains the following essential files:
*   `Customer-Segmentation-Dashboard.pbix`: The main Power BI Desktop file containing the data model, DAX measures, and interactive visual reporting.
*   `sales_asia.csv`: Raw transactional sales data capturing customer history, order dates, and financial metrics across the region.
*   `RFM_Asia.csv`: Processed or aggregated RFM scores calculated from the sales data used to feed the segmentation matrix.
*   `LICENSE`: Licensed under the permissive MIT License.

## 🚀 Key Features of the Dashboard

*   **Dynamic Customer Segmentation:** Instantly filter and view different tiers of customers based on their RFM scores.
*   **Behavioral Insights:** Analyze high-value consumer habits compared to casual or slipping customer groups.
*   **Interactive Metrics:** Cross-filter visuals by timeline, location, and purchase values to uncover regional trends.

## 🛠️ How to View and Use

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/k-Abhigna/Customer-Segmentation-Dashboard_Project13.git](https://github.com/k-Abhigna/Customer-Segmentation-Dashboard_Project13.git)
    ```
2.  **Open the Dashboard:** 
    *   Make sure you have [Power BI Desktop](https://powerbi.microsoft.com/) installed.
    *   Open `Customer-Segmentation-Dashboard.pbix`.
3.  **Data Source Re-linking (If Required):** 
    *   If the data doesn't load initially, navigate to *Transform Data* > *Data source settings* in Power BI and point the paths to your local copies of `sales_asia.csv` and `RFM_Asia.csv`.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
