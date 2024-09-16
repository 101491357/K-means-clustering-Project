# K-means-clustering-Project Summary
#I employed K-means clustering to segment customers based on purchase behavior, basis of purchase, and demographics. To ensure proper scaling, I utilized StandardScaler from the sklearn library, which normalized the feature values. After fitting the model, I identified distinct customer clusters and analyzed their characteristics, focusing on variables like total volume, transaction frequency, and promotional purchases.

#To deepen the analysis, I implemented logistic regression to predict high-value customer segments. I trained the model on 80% of the dataset and used the remaining 20% to evaluate performance. Using accuracy score, confusion matrix, and a classification report, I assessed the model’s predictions. Additionally, I calculated cumulative lift and gain curves to visualize how well the model distinguished value segments.

#Throughout this project, I demonstrated proficiency in Python, data manipulation using Pandas, and visualization with Matplotlib and Seaborn. By combining machine learning techniques with business-oriented insights, I effectively differentiated value and non-value customer segments.


#OUTCOME

#The clustering analysis revealed two distinct customer segments: high-value customers and low-value customers. The high-value segment exhibited higher transaction volumes, more frequent purchases, and a greater tendency to buy products on promotion. By identifying these clusters, we gained valuable insights into customer behavior, allowing the business to tailor marketing strategies and promotions more effectively toward the high-value group.

#The cumulative lift and gain curves demonstrated the model's ability to rank customers based on their likelihood of being high-value, providing a basis for future targeted marketing campaigns. This project ultimately led to actionable insights, which could help the company optimize its promotional spending and enhance customer retention strategies.
