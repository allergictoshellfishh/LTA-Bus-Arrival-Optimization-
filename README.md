# LTA-Bus-Arrival-Optimization-

This project applies distributed data pipeline concepts to address a real-world public transport problem: bus clustering and unpredictable waiting times during off-peak hours. Using Alteryx Designer, I built an end-to-end pipeline that combines real-time bus arrival data and scheduled frequency data from multiple LTA DataMall APIs to support more consistent and commuter-centric bus services.

Three Alteryx workflows were designed. The first retrieves real-time bus arrival information based on a user-input bus stop code, processing JSON API responses into a clean, readable dataset showing arrival gaps, vehicle types, and load levels. The second workflow extracts scheduled bus frequency data across peak and off-peak periods, while the third validates user inputs by retrieving all valid bus stop codes in Singapore.

To operationalise the pipeline, an interactive Power BI dashboard was built and connected to Alteryx using Power Automate. Users can input a bus stop code, trigger backend updates, and visually compare scheduled versus actual arrival intervals through combined bar and line charts. This allows transport planners and commuters to easily identify bus clustering and irregular service gaps in real time.

Overall, this project demonstrates how real-time APIs, data transformation, and frontend visualisation can be integrated into a practical decision-support system. The solution highlights inconsistencies in off-peak bus operations and provides actionable insights that can help authorities optimise dispatch intervals, improve service reliability, and enhance the daily commuting experience.

Key Tools & Concepts: Alteryx Designer, JSON parsing, data pipelines, Power BI, Power Automate, real-time data processing, public transport analytics.
