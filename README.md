# 🧘 Kundalini Activity Dashboard

A professional, visual Streamlit application designed for spiritual seekers to track and analyze their **Kundalini energy** flow across the seven chakras.

---
 You can now view your Streamlit app in your browser.
  Local URL: http://localhost:8501
  Network URL: http://10.17.247.253:8501
  External URL: http://74.220.48.240:8501


## ✨ Features

- 📊 **Dynamic Data Visualization**: Interactive charts (histograms, box plots, violin plots) for energy distribution.
- 🔮 **Chakra Analysis**: Detailed insights into each of the 7 chakras (Root to Crown).
- 📈 **Statistical Summaries**: Automatic calculations of metrics, averages, and numerical distribution.
- 📁 **Multi-Format Export**: Download analyzed data in CSV or JSON format.
- 🌈 **Chakra Color Mapping**: Unique, color-coded themes for each chakra based on traditional spiritual wisdom.

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/kundalini-dashboard.git
cd kundalini-dashboard
```

### 2. Install dependencies
Ensure you have Python 3.8+ installed, then run:
```bash
pip install -r requirements.txt
```

### 3. Launch the dashboard
```bash
streamlit run dashboard.py
```

---

## 📄 Data Format

The dashboard works by uploading a CSV file. For the best experience (including specialized chakra analysis), your CSV should ideally contain a **'Chakra'** column with any of the following values:

- **Root** (Grounding)
- **Sacral** (Creativity)
- **Solar Plexus** (Power)
- **Heart** (Love)
- **Throat** (Expression)
- **Third Eye** (Intuition)
- **Crown** (Wisdom)

### Example CSV Structure:
| Date | Chakra | Energy_Level | Duration_Min | Notes |
| :--- | :--- | :--- | :--- | :--- |
| 2024-01-01 | Root | 7 | 30 | Morning session |
| 2024-01-02 | Heart | 9 | 45 | Deep meditation |
| 2024-01-03 | Crown | 8 | 25 | Evening practice |

---

## 🛠️ Technology Stack

- **[Streamlit](https://streamlit.io/)**: For the interactive web interface.
- **[Pandas](https://pandas.pydata.org/)**: For data manipulation and analysis.
- **[Plotly Express](https://plotly.com/python/plotly-express/)**: For high-quality interactive visualizations.

---

## 🧘 Made for Seekers
Designed with ❤️ for tracking spiritual growth and energy alignment.

