AI-Enhanced Wildlife Corridor Identification & Movement Prediction

The project was made with the help of AI bots and Synthetic Data is used.

📌 Project Overview
This project leverages advanced Machine Learning and Graph Theory to protect biodiversity. By analyzing environmental resistance and GPS telemetry, the system identifies "Least-Cost Paths" for wildlife and predicts future movement to mitigate human-wildlife conflict.

🛠️ Technical Deep-Dive
Pathfinding: Uses scikit-image and rasterio to calculate optimal corridors through resistance surfaces.

Deep Learning: Includes a Transfer Learning pipeline (ResNet50) for habitat classification and an LSTM network for time-series movement prediction.

Machine Learning: Employs XGBoost for presence/absence modeling and SHAP (SHapley Additive exPlanations) for model interpretability.

Graph Analytics: Uses NetworkX to calculate PageRank scores for National Parks, identifying which habitats are most critical for network connectivity.

Reinforcement Learning: Implements a Q-Learning environment framework to simulate animal decision-making under human disturbance.

📊 Key Results
High Accuracy: Species distribution model achieved a 0.85 ROC-AUC.

Network Mapping: Successfully mapped 45 unique connectivity paths between 10 major Indian National Parks (e.g., Corbett, Gir, Kanha).

Interpretability: Integrated SHAP values to explain how vegetation and water proximity influence animal presence.

🚀 Libraries Used
Python | TensorFlow/Keras | XGBoost | GeoPandas | NetworkX | Folium | Scikit-Learn
