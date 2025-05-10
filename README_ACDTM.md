
# ACDTM: Adaptive Centrality-Driven Targeted Marketing

This repository contains the implementation of the ACDTM (Adaptive Centrality-Driven Targeted Marketing) model — an end-to-end framework that integrates social graph analytics and machine learning to optimize influencer targeting and campaign performance in digital marketing.

🎯 **Goal**

To intelligently rank influencers and optimize campaign decisions based on their predicted impact on key marketing outcomes: Click-Through Rate (CTR), Conversion Rate, and Customer Lifetime Value (CLV).

📌 **Key Features**

- Graph-Based User Network Construction using NetworkX  
- Centrality Score Calculation: Degree, PageRank, Closeness, Betweenness  
- Rich Feature Engineering from user activity, content, and edge interactions  
- Frequency Encoding of textual attributes (e.g., user interests)  
- Scalable Data Normalization (StandardScaler)  
- Supervised Learning with XGBoost for predicting:
  - CTR
  - Conversion Rate
  - CLV
- Export of top influencers ranked by performance potential  
- Ad Placement Optimization Simulation  
- Performance Monitoring via Visual Comparisons (Actual vs Predicted)

📈 **Model Architecture**

The flow follows these major stages:

1. Data Preprocessing  
2. Feature Extraction & Engineering  
3. Graph Construction  
4. Centrality Computation  
5. Feature Selection  
6. Model Training & Evaluation  
7. Campaign Simulation  
8. Feedback Analysis & Performance Visualization

📊 **Visualizations**

- Centrality Distributions  
- Top 10 Ranked Influencers by CTR / Conversion / CLV  
- Predicted vs Actual Histograms  
- Scatter Comparisons  
- Network Flow Diagram (ACDTM Pipeline)

📁 **Files in This Repo**

- `ACDTM.ipynb`: Main notebook containing full pipeline from preprocessing to export  
- `top_100_influencers.csv`: Top influencers ranked by predicted CTR  
- `top_100_conversion.csv`: Ranked by Conversion Rate  
- `top_100_clv.csv`: Ranked by Customer Lifetime Value  
- `performance_comparison.csv`: Actual vs predicted metrics for all influencers  
- `simulated_underperforming_influencers.csv`: Users with consistent underperformance

📚 **Data Sources**

This project uses cleaned and transformed datasets derived from multiple publicly available social/information network datasets and marketing behavior datasets (e.g., from SNAP and Kaggle). The input CSV was constructed based on these sources and processed in alignment with our academic project guidelines.

📄 **Report & Paper**

The full academic paper detailing the methodology, evaluation, and results is included in the repository (IEEE format ready). It includes key visualizations, model metrics, and code snippets.

🧠 **Course Focus**

This project is part of an academic submission under the Social and Information Network course, emphasizing the role of graph theory and network centrality in real-world marketing applications.

🔧 **Requirements**

- Python 3.10+  
- pandas  
- numpy  
- networkx  
- matplotlib  
- seaborn  
- scikit-learn  
- xgboost

📬 **Contact**

For any questions or collaborations, reach out to the contributors listed in the project report.
