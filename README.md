# 🌍 Satellite-Based GHG Monitoring using Deep Learning (Synthetic Data)

This project demonstrates how deep learning can be used to monitor greenhouse gas (GHG) concentrations, such as CO₂, using synthetic satellite-like image data. It simulates a real-world application where satellite spectral data is processed by a convolutional neural network (CNN) to estimate atmospheric GHG levels.

---

## 📦 Features

- Synthetic 64x64 RGB image generation to simulate satellite data
- CO₂ prediction model using a simple CNN architecture (PyTorch)
- Evaluation using R² score and MSE
- Visualization of predictions on synthetic image data

---

## 🛠️ Requirements

Install dependencies with:

```bash
pip install torch torchvision scikit-learn matplotlib numpy
🚀 Usage
Run the Script
Execute the Python script:

bash


python satellite_ghg_monitoring.py
Output

Trains the CNN on synthetic data

Prints validation loss and R² score per epoch

Displays a prediction vs actual GHG concentration for a sample image

🧪 Sample Output
yaml


Epoch 20/20, Val Loss: 19.4532, R²: 0.9767
Sample Prediction: 405.23 ppm, Actual: 407.21 ppm

📁 Files
satellite_ghg_monitoring.py — main Python script

Satellite_GHG_Monitoring_DL_Code.xlsx — Excel version of the source code

README.md — this documentation file

📌 Notes
This is a synthetic prototype. Real applications should use actual satellite data from sources like:

Sentinel-5P

NASA OCO-2

Google Earth Engine



👨‍💻 Author
Tarinabo williamtarinabo@gmail.com

