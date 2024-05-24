# Telecom-Churn-Prediction
Customer behavior during churn typically unfolds over several phases rather than being an instantaneous decision. This process is especially relevant for high-value customers who may take time to assess their options and make a decision. In the context of churn prediction, we often categorize these phases into three stages:

The 'Good' Phase: During this initial phase, customers are generally satisfied with the service they receive and exhibit typical usage behaviors. They are not actively seeking alternatives or showing signs of dissatisfaction. This phase represents a stable period where the customer's behavior aligns with their historical patterns of usage.

The 'Action' Phase: As customers move into the action phase, certain triggers or events may occur that disrupt their satisfaction or loyalty to the current service provider. These triggers could include receiving attractive offers from competitors, experiencing billing discrepancies or service quality issues, or encountering other factors that lead to dissatisfaction. In this phase, customers may begin to display behaviors that deviate from their usual patterns, indicating a potential risk of churn.

The 'Churn' Phase: The churn phase represents the final stage where customers decide to discontinue their services with the current provider and switch to a competitor. By this stage, the dissatisfaction or triggers from the action phase have likely escalated to a point where the customer actively seeks alternatives and initiates the process of leaving the current service provider.

In a typical four-month window scenario, such as the one mentioned in the competition, these phases can be mapped accordingly:

Months 1-2 (Good Phase): Customers are content and exhibit normal usage behaviors.
Month 3 (Action Phase): Signs of dissatisfaction or deviations from normal behavior may start to appear due to various triggers.
Month 4 (Churn Phase - September in the context mentioned): Customers officially churn, indicating their decision to switch to another provider.
Identifying high-churn-risk customers during the action phase is crucial because it provides an opportunity for the company to intervene, such as offering competitive deals, improving service quality, or addressing specific issues that may be driving customers away. By predicting churn during the action phase, companies can implement proactive strategies to retain valuable customers before they reach the point of churn.

![image](https://github.com/sandeep822/Telecom-Churn-Prediction/assets/50867031/310fa1b9-bb73-4bfb-a2c4-569004aedb3c)

The scatter plot visualizes the relationship between total_and_mou_8 and total_rech_amt_7. Each point on the plot represents a data entry from the dataset, where the x-coordinate corresponds to the total_and_mou_8 variable, which likely indicates some kind of total minutes of usage, and the y-coordinate represents total_rech_amt_7, which likely indicates the total recharge amount during a specific period.

The plot appears to show a positive correlation between these two variables. As the total outgoing minutes (total_and_mou_8) increase, there seems to be a general trend of higher total recharge amounts (total_rech_amt_7). However, there is also some spread in the data, indicating that other factors may influence the total recharge amount apart from just the total outgoing minutes. This scatter plot helps visualize the overall relationship and the variability in the data points, suggesting a connection between usage and recharge behavior but with some variability that could be due to various customer-specific factors or plans.

![image](https://github.com/sandeep822/Telecom-Churn-Prediction/assets/50867031/76b34bb6-75ea-4549-bda0-1addadf99ed5)

The line plot depicts the relationship between tenure (AON - Age on Network, representing how long a customer has been with the network) and total recharge amount for three different months: June, July, and August. Each line on the plot represents the trend of total recharge amount over tenure for a specific month. The plot helps to visualize if there's any discernible pattern or trend in total recharge amount concerning customer tenure. If the lines show an upward trend, it indicates that as the tenure of customers increases, their total recharge amount also tends to increase. Conversely, a downward trend would suggest that as tenure increases, the total recharge amount decreases. This visualization can provide insights into how customer spending behavior changes over their duration of being on the network.

![image](https://github.com/sandeep822/Telecom-Churn-Prediction/assets/50867031/f5421857-a946-49b4-9486-a0123e59956b)

Principal Component Analysis (PCA) on the scaled training data (X_train_filtered2) to reduce its dimensionality. It then transforms the data into two principal components (pca_components[:,0] and pca_components[:,1]) and creates a scatter plot using seaborn (sns.scatterplot). The scatter plot visualizes the relationship between these two principal components, with points colored by the target variable (y_train), specifically representing churn probability categories (0 and 1). This visualization helps in understanding the distribution of data points in reduced dimensional space and any potential clustering or separation between churn and non-churn instances.

![image](https://github.com/sandeep822/Telecom-Churn-Prediction/assets/50867031/a7d66e8e-bf75-4f79-8b06-c28c5803b5f2)

A scatter plot using seaborn (sns.scatterplot) with the second principal component (pca_components[:,1]) on the x-axis and the third principal component (pca_components[:,2]) on the y-axis. The data points are colored based on the churn probability categories (0 and 1) from the target variable (y_train). This scatter plot visualizes the relationship between these two principal components, providing insight into any clustering or separation patterns between churn and non-churn instances in the reduced dimensional space defined by PCA.


