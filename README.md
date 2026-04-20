# ⚡ Building Energy Anomaly Detector

An automated energy monitoring pipeline that detects unusual energy consumption patterns in buildings and sends real-time email alerts to the facilities manager.

## 🔍 What it does
- Generates and loads building energy consumption data
- Detects anomalies automatically using Isolation Forest ML model
- Flags unusual spikes and drops in energy consumption
- Automatically sends email alerts to the facilities manager
- Visualizes energy consumption with anomalies highlighted in red

## 🛠️ Tech Stack
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn (Isolation Forest)
- SMTP (automated email alerts)
- python-dotenv (secure credentials)

## 💡 Real World Use Case
Instead of manually monitoring energy dashboards, this pipeline automatically detects anomalies and alerts the right person instantly — preventing equipment damage and energy waste.

## 🚀 How to Run
1. Clone the repo
2. Install dependencies: `pip install pandas numpy matplotlib seaborn scikit-learn python-dotenv`
3. Create a `.env` file with your credentials:
EMAIL=youremail@gmail.com
EMAIL_PASSWORD=your_app_password
4. Open `EnergyAnomalyDetector.ipynb` in Jupyter Notebook
5. Run all cells: `Kernel → Restart & Run All`
