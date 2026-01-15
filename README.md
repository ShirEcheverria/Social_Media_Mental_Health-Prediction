# Social_Media_Mental_Health-Prediction #

<img width="493" height="493" alt="image" src="https://github.com/user-attachments/assets/49adb3e2-2e4a-400c-902a-c559bd42284c" />






📋 Overview

This project investigates the impact of digital habits on mental well-being. Using a dataset of 5,000 observations, we developed a machine learning pipeline to classify users' mental states into three categories: Healthy, At Risk, or Stressed. The goal is to identify "Digital Biomarkers" that can provide early warnings for mental distress.
Mental Health Prediction via Social Media Patterns

📊 Key Insights (EDA)

The Screen-Stress Link: A high positive correlation (0.84) was identified between daily screen time and stress levels.
Sleep as a Protector: Quality sleep showed a strong negative correlation (0.83) with anxiety, acting as a crucial "mitigating factor" even against high digital usage.

Demographics: Younger users exhibit higher volatility in social interactions, which significantly impacts their mental state classification.

🤖 Machine Learning Modeling

We compared three advanced tree-based models to achieve optimal classification:
Random Forest: Served as the baseline with exceptional accuracy (1.0), identifying screen time and physical activity as top features.
LightGBM: Optimized for high-speed training and efficiency.
CatBoost: Delivered the most robust results for categorical features (Platform, Gender), achieving a Macro F1-score of 0.984.

🛠️ Technical Implementation

Preprocessing: Data cleaning, Label Encoding for targets, and One-Hot Encoding for categorical variables.
Interactive Simulator: A "What-If" tool was developed to allow real-time inference, where users can input habits and receive an immediate mental state prediction.

🚀 Conclusion

The study concludes that while social media usage is a major stressor, lifestyle factors specifically sleep and exercise are the most effective tools for maintaining mental resilience in the digital age.
1.Digital Biomarkers as Predictive Tools: The research confirms that a small set of quantitative metrics, specifically Stress Level and Daily Screen Time, can reliably predict mental resilience.

2.The Mediating Power of Lifestyle: Lifestyle factors like sleep and exercise are not just health indicators but active "buffers". Sufficient sleep can mitigate the negative effects of high screen time, preventing a user from being classified into a risk group.

3.Demographic Sensitivity: Younger populations experience "digital extremes" with high-intensity social interactions. The models successfully integrated age as a factor influencing sensitivity to screen time.

4.Technological Superiority: Tree-based boosting algorithms, particularly CatBoost, are best suited for behavioral data as they handle categorical nuances and non-linear relationships without losing information during encoding.


