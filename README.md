# 🌊 Sea Surface Temperature (SST) Analysis for Climate Studies

This project simulates and analyzes synthetic Sea Surface Temperature (SST) data to demonstrate techniques used in climate studies. It includes time-series modeling, trend analysis, seasonal decomposition, and anomaly detection using Python.

---

## 📌 Project Overview

Climate researchers often monitor Sea Surface Temperatures (SSTs) to detect global warming trends, El Niño/La Niña patterns, and marine heatwaves. This project creates **synthetic SST data** over a 10-year period (~120 months) and applies several common techniques for climate time-series analysis.

---

## 📁 Project Structure

```bash
.
├── synthetic_sst_data.csv     # Generated dataset (120 monthly SST samples)
├── sst_analysis.py            # Main Python analysis script
└── README.md                  # This README file
📊 Features
✅ Synthetic SST generation with seasonality, warming trend, and noise

📈 Visualization of raw SST time series

🔁 Seasonal decomposition using statsmodels

📉 Linear regression to detect climate trends

🚨 Anomaly detection for extreme temperature deviations

🧪 Technologies Used
Python 3

Numpy

Pandas

Matplotlib / Seaborn

Scikit-learn

Statsmodels

🚀 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/sst-climate-analysis.git
cd sst-climate-analysis
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the analysis:

bash
Copy
Edit
python sst_analysis.py
📂 Dataset Preview
The dataset includes the following columns:

Date	SST (°C)	Trend (°C)	Anomaly (°C)
2015-01-31	26.05	25.00	+1.05
2015-02-28	25.80	25.02	+0.78
...	...	...	...

📌 Use Case
This is an educational project intended to demonstrate:

Time-series analysis for climate data

Interpreting seasonal patterns and long-term trends

How to simulate and work with realistic environmental datasets

📜 License
This project is licensed under the MIT License.

🙌 Acknowledgements
Inspired by climate data tools used by NOAA, NASA, and IPCC.

Special thanks to the Python open-source community.

📧 Contact
For questions or collaboration opportunities, feel free to reach out:

Author: Agbozu Ebingiye Nelvin
Email: nelvinebingiye@gmail.com
GitHub: @nelvinebi
