# Final-DA-Project
The main goal of this project is to analyze the Coal Stocks data is taken from thermal power stations across India.

# Final-Project
The main goal of this project is to analyze the Coal Stocks data is taken from thermal power stations across India.

🎯 **Objective of the Project**

This dataset gives a complete operational snapshot of coal availability at power plants in India. It helps monitor:

Daily coal supply chain efficiency
Plant fuel security level
Power station performance (via PLF)
Stock adequacy vs normative standards
Identification of critical power stationsm
Dependency on imported vs local coal

🔍 **Key Insights from Daily coal stocks**

_Wide Operational Coverage_ :- 
The dataset spans 17 states and ~189 power stations, giving a comprehensive view of coal availability and performance across India’s thermal power sector.

_Stock vs. Normative Requirements_ :-
Many observations show a gap between actual coal stock and normative stock levels, indicating that several power plants operate close to minimum safety thresholds, which increases supply-risk sensitivity.

_Indigenous vs. Imported Coal Dependence_ :- 
Indigenous coal forms the primary source of stock for most stations, while imported coal is used selectively, suggesting cost optimization but also exposure to domestic supply disruptions.

_Coal Stock Days Variability_ :-
Coal availability (measured in stock days) varies significantly across plants and states, reflecting uneven logistics, transport modes, and regional supply chain efficiency.

_Power Generation Efficiency (PLF)_ :-
The average Plant Load Factor (PLF) is moderate (~64%), implying under-utilization of installed capacity, often linked to fuel availability constraints rather than infrastructure limitations.

_Supply–Consumption Imbalance_ :- 
In several records, daily consumption exceeds daily receipts, which can lead to declining stock levels if sustained over time—an early warning signal for potential critical situations.

_Sector and Utility Differences_:- 
Performance and stock adequacy differ across sectors (State, Central, Private) and utilities, highlighting opportunities for best-practice replication from better-performing operators.


🛠️**Tools & Technologies**

Google Colab (Cloud-based Python environment)
Python Libraries:

pandas → Data cleaning & manipulation
numpy → Numerical analysis
matplotlib → Data visualization
seaborn → Advanced visualization

📈 Sample Visualizations Some of the visualizations included in this project:

📌 Pairplot  → Relationships between Required Normative Stock,Indigenous Stock and Import Stock.

📌 Pie Chart → State-wise Daily Consumption vs Daily Requirement.

📌 Bar Chart → Average Total Stock by State.

📌 Hisplot   → Distribution of state Names,Sector,Mode Of Transport,Utility.


🚀 **Future Enhancements & Scope**

_Predictive Analytics_ :- 
Apply time-series forecasting to predict future stock shortages and critical days based on historical trends.
_Logistics Optimization Analysis_ :- 
Study the impact of mode of transport (rail, road, conveyor) on stock stability and receipt efficiency.

_Integration with External Data_ :- 
Combine coal data with weather, demand forecasts, and railway movement data to improve supply-chain resilience.

_Policy & Planning Support_ :- 
Use insights to support fuel allocation planning, emergency stock policies, and infrastructure investments.

✅ Conclusion

The analysis reveals that while coal supply is largely sustained through indigenous sources, stock adequacy and logistics efficiency remain uneven across states and power stations. Moderate PLF values and recurring gaps between actual and normative stock levels indicate that fuel availability continues to be a limiting factor for optimal power generation. Overall, the dataset provides strong evidence that proactive coal stock monitoring is essential for maintaining grid reliability.

