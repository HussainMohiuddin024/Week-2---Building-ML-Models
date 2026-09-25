Week 2 of Applied AI: Building and Evaluating ML Models 

This week, I worked on a customer churn prediction project using the Telco Customer Churn dataset. I trained and compared Logistic Regression, Decision Tree, and Random Forest models.

One important takeaway was that accuracy alone does not tell the complete story. The baseline model achieved 73.5% accuracy but detected zero churners, while Logistic Regression achieved 80.7% accuracy with 56.7% recall and an AUC of 0.842.

I also explored different classification thresholds and found that a lower threshold can help identify more potential churners when the cost of missing a customer is higher than the cost of an unnecessary retention offer.

Feature engineering with service count, customer tenure, and charging-related features did not improve AUC significantly, which was an interesting result in itself.

The biggest lesson from this lab was that machine learning models should be evaluated using the right combination of metrics, business costs, and practical requirements rather than relying on accuracy alone.
