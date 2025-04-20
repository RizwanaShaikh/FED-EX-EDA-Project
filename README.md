# FED-EX-EDA-Project
https://colab.research.google.com/drive/18VbRo7E5vB48TiMkSPK5-HKD4MgbVBZd?usp=drive_link

The primary objective of this project is to analyze the delivery performance of FedEx using historical shipment and supply chain data sourced from the SCMS Delivery History Dataset. The dataset provides a comprehensive record of delivery activity including vendor details, delivery status, timelines, regions, and various metrics related to order fulfillment and logistics. This analysis offers actionable insights to improve efficiency, enhance service reliability, and identify performance gaps in the delivery network.

1. Dataset Overview
The dataset comprises detailed records of delivery transactions including fields such as Delivery Status, On Time Delivery, Vendor Name, Planned Delivery Date, Actual Delivery Date, Delivery Location, Line Item Value, and more. It represents shipments from multiple vendors across different regions and spans a wide time range, offering a rich foundation for analysis of temporal trends and vendor performance.

2. Objectives
The main goals of this analysis are:

To assess delivery punctuality by evaluating the proportion of on-time vs delayed deliveries.

To identify top-performing and underperforming vendors in terms of delivery count and reliability.

To explore delivery status distribution to understand common operational challenges.

To visualize temporal delivery trends to detect seasonal patterns or disruptions.

To examine lead times and delivery delays for identifying inefficiencies.

3.  Key Analyses and Visualizations
Delivery Status Distribution:
This bar chart highlights the spread of delivery statuses (e.g., Delivered, In Transit, Cancelled, Late Delivery) providing an immediate sense of operational effectiveness.

On-Time vs Delayed Deliveries:
A comparison of on-time vs late shipments is presented to quantify delivery reliability. This metric is crucial for performance benchmarking.

Top Vendors by Delivery Volume:
Identifying vendors with the highest number of deliveries helps highlight key partners and focus attention on where volume—and risk—are concentrated.

Deliveries Over Time:
Time-series visualizations track the number of deliveries on a monthly basis, revealing any notable fluctuations or patterns due to external factors (e.g., holidays, disruptions).

Delivery Delay Analysis:
By calculating the difference between the Planned Delivery Date and the Actual Delivery Date, we visualize how frequently and by how much deliveries are delayed.

Regional Delivery Performance:
Mapping delivery locations against performance metrics helps highlight geographical disparities in delivery efficiency.

4. Tools & Technology
The project is implemented using Python in Google Colab, leveraging libraries such as Pandas for data processing, Matplotlib, Seaborn, and Plotly for data visualization. The final insights and visuals are prepared for integration into a presentation deck (FedEx.pptx) and can also be exported for dashboard use.

5. Outcomes
This project provides:

A clear understanding of delivery reliability and vendor performance.

Identification of potential bottlenecks or regions requiring process improvements.

Foundational metrics for setting Key Performance Indicators (KPIs) in future logistics operations.

