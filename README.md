#Swire Coca-Cola Maintenance Optimization Project
##Project Overview
Swire Coca-Cola operates a vast network of production plants and distribution centers, where machine downtime due to breakdowns is a common challenge. The goal of this project is to help Swire Coca-Cola reduce unplanned maintenance events and improve productivity by providing a data-driven solution that minimizes downtime costs and optimizes the maintenance process.

##Business Problem
Swire Coca-Cola's production plants track machine breakdowns but lack a clear mechanism for preventing these unplanned downtimes. The company faces the challenge of identifying the optimal amount of planned maintenance required to reduce the likelihood of breakdowns, without incurring unnecessary costs. Our objective was to provide a solution that helps the company strike the right balance between planned and unplanned maintenance.

##Solution Overview
Initially, we attempted to address this issue using a classification model that could predict when machines are likely to fail. However, we encountered a data challenge: the dataset only included instances where breakdowns occurred, with no data on machines that didn’t break down. This limited the effectiveness of a predictive model.

After reassessing the situation, we pivoted towards a more practical solution: a Breakeven Maintenance Calculator. This tool takes inputs like the ratio of planned to unplanned maintenance hours and the hourly cost of planned versus unplanned maintenance. It calculates the optimal number of planned maintenance hours needed to minimize unplanned maintenance and keep costs under control.

##My Contribution
Exploratory Data Analysis (EDA): I played a central role in the EDA process, where I explored the relationships between variables and gained a deeper understanding of the data’s structure.
Breakeven Calculator: I developed the breakeven calculator, which delivers the exact number of planned maintenance hours required for each sector of a plant. This enables the Swire team to clearly understand the cost savings associated with planned maintenance.
Modeling: While I contributed to the overall project, I was not directly involved in the predictive modeling aspect, as our solution did not require complex models.
Business Value
The breakeven calculator delivers significant value by providing a clear, actionable output for planned maintenance hours in each sector of a plant. This tool allows Swire Coca-Cola to optimize their maintenance schedules and make data-driven decisions on how much to invest in planned maintenance to avoid costly unplanned breakdowns. The result is better cost control and improved operational efficiency.

##Challenges Encountered
Our team faced several challenges, particularly during the development of predictive models. While some datasets lend themselves well to predictive modeling, the dataset we had was not ideal for this approach, as it lacked data on machines that didn’t experience breakdowns. This led us to pivot our strategy and focus on a more practical, calculation-based solution.

##Key Takeaways
One of my major takeaways from this project is the realization that, as data analysts, we can often be drawn to complex predictive models because they are intellectually stimulating and fun. However, sometimes the best solution to a problem isn’t necessarily a predictive model at all. In this case, a simpler, more targeted approach—like the breakeven calculator—was not only more effective but also easier to implement and directly actionable.
