# Areeb


Areeb
predict traffic volume after Capital project ,T5 Zehame Bootcamp

# Deployment: 
https://huggingface.co/spaces/NuhaFaisal/Final_Areeb

# Introduction
Our project aims to enhance the efficiency of urban planning by addressing the problem of traffic congestion in urban areas before starting to build projects in them, so that it gives an idea of the amount of traffic congestion that the project may cause when it is opened. We have developed a model as a path to real data for existing projects (LSTM). The model is intended for analyzing consecutive time data

# Model
LSTM (Long Short-Term Memory) network,it is well-suited for analyzing sequential data and capturing long-term dependencies. The LSTM model is trained on time-series data to predict traffic volume in specific regions based on past traffic patterns and external factors like holidays and active projects.

# Model Architecture
• LSTM Layer: 64 units to capture long-term patterns in the data.

• Dropout Layers: 30% dropout to reduce overfitting.

• Dense Layers: Two dense layers with ReLU activation.

• Output Layer: Predicts traffic volume.

• Optimizer: Adam with a learning rate of 0.0005.

• Loss Function: Mean Squared Error (MSE).

• Evaluation Metric: Mean Absolute Error (MAE). Screenshot 1446-04-03 at 10 15 47 PM

# Features
• Historical Traffic Data: Includes data such as traffic volume, location, and time.

• External Factors: Incorporates additional data such as holidays and project activity to provide more accurate predictions.

• Visualization: Uses Folium to create interactive maps that visualize the predicted congestion levels, helping decision-makers plan effectively.

# Installation
1-To install and run the project locally, follow these steps:

Clone the repository:

git clone https://github.com/YourUsername/Traffic-Congestion-Prediction.git

2-Navigate to the project directory:

cd Traffic-Congestion-Prediction

3-Install the required dependencies:

pip install -r requirements.txt

# Usage
1-To train the LSTM model and visualize the results:

Train the model: python train.py

2-Visualize the predicted traffic congestion: python visualize.py

# Results
The LSTM model successfully predicts traffic congestion in urban areas with a high degree of accuracy. The interactive map generated by Folium allows users to see the predicted congestion levels, making it easier to adjust project planning and mitigate traffic issues. MAE: 0.0678316205739975

# Key Findings
• Traffic congestion increases during peak project activity times.

• Certain regions are more prone to congestion based on historical data and project activity.

# Dependencies
The project requires the following Python packages:

• TensorFlow

• Keras

• NumPy

• Pandas

• Folium

• Scikit-learn

# Project Members
• Sadeem Abdullah AlMesned

• Nuha Faisal Aloqayli

• Ghadeer Mohammed Nooh

• Lama Mohammed Alqahtani

• Asmaa Ahmed Alzobidi


