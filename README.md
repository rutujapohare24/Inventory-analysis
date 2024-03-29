# Inventory Analysis Project - Tableau Dashboard

## Data Source
The dataset used for this inventory analysis project is available on Kaggle: [Supply Chain Dataset](https://www.kaggle.com/datasets/saadatali110/supply-chain-dataset)

## Tableau Dashboard
Explore the Tableau dashboard on Tableau Public: [Inventory Analysis Tableau Dashboard](https://public.tableau.com/app/profile/rutuja.pohare/viz/InventoryAnalysisTableauDashboard/InventoryDashboard?publish=yes)

### Key Visualizations and Insights

#### 1. Average Order per Day

#### 2. Average Shipping Time

#### 3. Average Shipping Cost
- Visualization: Bar chart illustrating the average shipping cost.
- Calculation: Calculated as 5% of the difference between sales and profit for each order.
**Sales:** The total revenue generated from all orders.  
**Profit:** The total profit earned from all orders.

#### 4. Orders by Department Name and Market
- Visualization: Stacked bar chart showing the total number of orders categorized by department name and market.

#### 5. Shipping Time by Department Name and Market
- Visualization: BAR depicting the average shipping time categorized by department name and market.

#### 6. Quarterly Orders by Customer Segment
- Visualization: BAR chart displaying the quarterly trend of orders for each customer segment.

   **Customer Segments:**
   - **Customer:** Individual customers making personal purchases.
   - **Corporation:** Business entities making bulk purchases for corporate use.
   - **Home Office:** Individuals making purchases for home office use.

### How to Use the Dashboard
1. Navigate to the [Tableau Public Dashboard](https://public.tableau.com/app/profile/rutuja.pohare/viz/InventoryAnalysisTableauDashboard/InventoryDashboard?publish=yes).
2. Explore the different visualizations by clicking on various elements.
3. Utilize filters to narrow down the analysis based on specific criteria.

Certainly, I understand. Here's the corrected version to reflect that the calculations in Tableau are being verified through the Python script:

---

### Validation with Tableau

To ensure the accuracy and consistency of the calculations performed in Tableau, this Python script serves as a validation mechanism. A corresponding Tableau workbook has been included for cross-checking the results obtained through Python.

**Validation Steps:**

1. **Data Consistency:**
   - Confirm that the input data in the Python script matches the data used in the Tableau workbook.

2. **Calculation Cross-Check:**
   - Verify the key calculations, such as average shipping time, order count by department and market, and quarterly order count by customer segment, in both Tableau and Python.

3. **Result Comparison:**
   - Compare the results obtained from Tableau with those generated in the Python script. The majority of calculations should align closely.

**Note:** Differences in results may occur due to variations in precision or rounding methods between Tableau and Python.

By performing this validation, we aim to ensure the accuracy and reliability of the analytical insights derived from both Tableau and the Python script. Any notable differences in results can be investigated further to enhance the robustness of the analysis.


### Future Improvements
- Incorporate additional metrics such as inventory turnover, stockout duration, and slow-moving products.
- Enhance interactivity with user-friendly filters and tooltips.
- Provide a more detailed breakdown of sales, profit, and shipping costs.

