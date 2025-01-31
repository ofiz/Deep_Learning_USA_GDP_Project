# 🚀 Deep Learning Course Project  
## 📈 GDP Growth Rate Prediction Using Deep Learning Architectures  

![Deep Learning](https://upload.wikimedia.org/wikipedia/commons/thumb/2/28/Deep_Learning.svg/512px-Deep_Learning.svg.png)  

---

## 📌 Overview  
This notebook demonstrates the application of **deep learning architectures** for **time-series forecasting**, specifically predicting **GDP growth rates**. Leveraging **advanced neural network (NN) models**, the project explores their ability to capture **temporal patterns in macroeconomic data**.  

The focus is on the practical implementation of **sequence models**, including:  
💚 **Transformer**  
💚 **Temporal Convolutional Network (TCN)**  
💚 **WaveNet**  

🛠️ **Goal:** Predict GDP trends using state-of-the-art deep learning techniques for **financial forecasting**.  

---

## 🎯 Objectives  
✔️ **Feature Learning**: Extract meaningful **temporal features** from sequential GDP data.  
✔️ **Model Comparison**: Evaluate performance of **CNN-based** and **attention-based** architectures.  
✔️ **Actionable Insights**: Provide robust predictions for **economic decision-making**.  

📈 **Example Prediction Output:**  
![Prediction Chart](https://upload.wikimedia.org/wikipedia/commons/9/91/Graph_of_economic_growth_in_Japan.png)  

---

## 📂 Dataset  
The dataset consists of historical **GDP growth rates** and **macro indicators**, structured as a **time series**.  
✔️ Data **preprocessed & normalized** for optimal deep learning performance.  

---

## 🏢 Deep Learning Architectures  
### 🧠 1. Transformer  
![Transformer Model](https://upload.wikimedia.org/wikipedia/commons/thumb/3/3f/Transformer_Model_Architecture.png/800px-Transformer_Model_Architecture.png)  
- **Attention-based model** that captures long-term dependencies.  
- **Key components**: Multi-Head Attention & Positional Encoding.  
- **Advantage**: Ideal for financial time-series forecasting.  

### 🏗️ 2. Temporal Convolutional Network (TCN)  
- A **CNN-based architecture** using **dilated convolutions** to model time-dependent relationships.  
- **Strength**: Fast training & hierarchical temporal feature extraction.  

### 🔊 3. WaveNet  
- Originally designed for **audio synthesis**, this **causal CNN** learns fine-grained **temporal dynamics**.  
- **Best for**: Capturing local patterns & trend reversals in GDP data.  

---

## 📊 Results and Analysis  

### 🔹 Transformer  
- **Prediction**: GDP growth rate for the next period: **0.7282%**  
- **Performance**: Strong in long-term trend alignment.  

### 🔹 Temporal Convolutional Network (TCN)  
- **Prediction**: GDP growth rate for the next period: **1.2485%**  
- **Performance**: Optimistic outlook, leveraging temporal feature hierarchies.  

### 🔹 WaveNet  
- **Prediction**: GDP growth rate for the next period: **0.3866%**  
- **Performance**: Conservative forecast, ideal for risk-averse strategies.  

📈 **Comparison Chart:**  
| Model       | Predicted GDP Growth (%) | Interpretation |
|------------|------------------------|---------------|
| Transformer | 0.7282 | Balanced trend estimation |
| TCN         | 1.2485 | Optimistic economic forecast |
| WaveNet     | 0.3866 | Conservative prediction |

---

## 🔑 Key Takeaways  
✅ **Transformers** are excellent for long-term economic trend analysis.  
✅ **TCNs** excel at modeling economic shifts using convolutional feature hierarchies.  
✅ **WaveNet** provides a conservative estimate, useful for **risk-averse financial planning**.  

---

## ⚙️ How to Use  

### 1️⃣ Environment Setup  
```bash
pip install torch tensorflow numpy pandas matplotlib
```
- Ensure the dataset is formatted for **time-series forecasting**.  

### 2️⃣ Run the Notebook  
- Train models by adjusting **hyperparameters** like learning rate, depth, and sequence length.  
- Compare results using **MSE (Mean Squared Error)** and **MAE (Mean Absolute Error)**.  

### 3️⃣ Visualize Predictions  
- Use **plots & metrics** to evaluate GDP trend alignment.  

📈 **Example Model Performance Chart:**  
![Loss Chart](https://upload.wikimedia.org/wikipedia/commons/4/4f/Loss_Function.png)  

---

## 📩 Contact  
📌 **Name**: Ofir cohen  
📌 **Email**: ofircohen599@gmail.com  

---

🔥 **This project bridges Deep Learning & Financial Forecasting, bringing AI-powered insights into economic decision-making!** 🚀
