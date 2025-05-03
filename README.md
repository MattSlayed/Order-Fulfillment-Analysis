# Order-Fulfillment-Analysis
Order Fulfillment Process Analysis
Project Overview
This project analyzes the order fulfillment process of a simulated e-commerce company to identify bottlenecks and propose improvements. It demonstrates business analyst skills in process mapping, data analysis, visualization, and actionable recommendations.
Objective
* Map the order fulfillment process (Order Received ? Processing ? Shipping ? Delivery).
* Analyze processing, shipping, and delivery times to identify inefficiencies.
* Propose data-driven improvements to enhance efficiency and customer satisfaction.
Dataset
Simulated dataset (order_fulfillment.csv) with 1,000 orders, including:
* OrderID: Unique order identifier.
* OrderDate: Date of order placement.
* ProcessingTime: Hours to process order.
* ShippingTime: Hours to ship order.
* DeliveryTime: Total hours to deliver order.
* CustomerSatisfaction: Rating (1–5).
Methodology
1. Data Creation: Generated simulated data using Python.
2. Process Mapping: Created a flowchart using draw.io.
3. Analysis: Calculated average times and identified bottlenecks (>48 hours).
4. Visualization: Plotted processing time distribution and satisfaction vs. delivery time.
5. Recommendations: Proposed automation, faster shipping, and better communication.
Key Findings
* Bottlenecks: DeliveryTime (48 hours) exceed 48 hours.
* Customer Impact: Longer delivery times correlate with lower satisfaction.
* Variability: Processing time is consistent (~24 hours), but delivery time varies widely.
Recommendations
* Automate order processing to reduce time to <20 hours.
* Partner with faster shipping providers to cut delivery time to <48 hours.
* Communicate expected delivery times to improve customer satisfaction.
Repository Structure
* Order_Fulfillment_Analysis.ipynb: Jupyter Notebook with code and analysis.
* order_fulfillment.csv: Simulated dataset.
* process_map.png: Process flowchart.
* processing_time_dist.png: Distribution of processing times.
* satisfaction_vs_delivery.png: Satisfaction vs. delivery time scatter plot.
* process_summary.txt: Summary of findings and recommendations.
How to Run
1. Install Python and required libraries:
2. pip install pandas numpy matplotlib seaborn
3. Clone this repository:
4. git clone https://github.com/your-username/Order-Fulfillment-Analysis.git
5. Open Order_Fulfillment_Analysis.ipynb in Jupyter Notebook and run all cells.
6. View outputs: process_map.png, processing_time_dist.png, satisfaction_vs_delivery.png, process_summary.txt.
Tools Used
* Python Libraries: Pandas, NumPy, Matplotlib, Seaborn
* Process Mapping: draw.io
* Environment: Jupyter Notebook
Future Improvements
* Incorporate real-world data from an e-commerce company.
* Create a BPMN diagram for detailed process modeling.
* Simulate improvement scenarios (e.g., 20% reduction in delivery time).
Contact
For feedback or questions, reach out via [matthewkoeberg13@gmail.com] or GitHub Issues.

