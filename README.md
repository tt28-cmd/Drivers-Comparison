## 🏎️F1 Telemetry Analysis: Vettel vs Raikkonen (Monza 2018)

**Project Overview**
This project provides a deep-dive technical analysis of the historic qualifying session at the 2018 Italian Grand Prix.Using telemetry data, I compared the performance of Sebastian Vettel and Kimmi Raikkonen to identify the marginal differences that led to the, at the time, fastest lap in Formula 1 history.

This analysis combines Python for telemetry processing and visualization with SQL for data aggregation, showcasing a complete data science workflow.

🛠️**Tech & Tools**:
* *Language*: Python🐍
* *Libraries*: FastF1, Pandas, Seaborn, Matplotlib
* *Database*: SQLite(for stint and sector time aggregation)
* *Environment*: Google Colab/Jupyter Notebook

**Key Features & Analysis**

* **Telemetry** : Merged and aligned speed, throttle, and brake data over track distance for accurate comparison.
* **Live Delta Time** : Calculated the real-time gap between drivers to pinpoint where time was gained or lost.
* **SQL**: Used to calculate average sector times and track performance consistency across multiple stints.
* **Driver Input**: Analyzed throttle and braking traces to compare the aggressive style of Vettel and the smooth approach of Raikkonen.

💡**Key Insights**

1.**Sector 3 Decider**: While Vettel was stronger in the heavy braking zones in Sector 1, Raikkonen's minimum cornering speed in the  *Lesmos* and exit from the *Parabolica* secured the pole position.

2.**Track Evolution**: SQL aggregation confirms that both drivers successfully utilized track evolution in Q3, with lap times dropping consistently as grip levels peaked.

3.**Efficiency**: The final gap of 0.1s highlights the identical performance of the Ferrari SF71H, where driving style became the deciding factor.

🚀**How to Run**

1. install the required libraries: pip install fastf1, pandas, matplotlib
2. open the .ipynb file in Google Colab or Jupyter
3. Run the cells.
