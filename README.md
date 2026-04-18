# Electricity Price Optimization Package

This package contains a set of automations and integrations designed to optimize electricity usage, especially in relation to battery storage and solar energy utilization. Below are the key features:

1. **Cheap Price Charging**  
   Charges the battery to 82% during the bottom 25% of price periods, utilizing solar energy to minimize costs and ensure efficiency.

2. **Battery Preservation**  
   Keeps the battery on standby during middle hours (25-75% of price periods) to extend its life and maintain efficiency.

3. **Return to Normal**  
   Manages transitions during expensive hours or fallback modes to ensure minimal costs during peak pricing.

4. **Periodic Price Refresh**  
   Polls the upstream sensor every 5 minutes to keep track of real-time electricity prices, ensuring decisions are made based on the most current data.

5. **SoC Guard**  
   Stops charging the battery when the state of charge reaches a predefined ceiling, preventing overcharging and enhancing battery lifespan.

6. **Negative Price Charging**  
   Charges the battery to 95% when negative prices occur, while blocking grid export to capitalize on the negative pricing situation.

7. **Block Grid Export at Negative Prices**  
   Executes every 30 minutes to prevent any energy exports to the grid when prices are negative, protecting against unnecessary costs.

This package provides a comprehensive solution for managing energy costs and optimizing the use of stored solar energy.