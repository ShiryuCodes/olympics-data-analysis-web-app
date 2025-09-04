[Live Demo](https://huggingface.co/spaces/Shiryuxu/olympic-data-analysis)

# 🏅 Olympics Data Analysis Web App

A comprehensive data analysis web application built with Streamlit that provides interactive insights into Olympic Games data from 1896 to 2016. This project transforms raw Olympic data into meaningful visualizations and statistics through an intuitive web interface.

# Dataset Used

Dataset used was [120 years of Olympic history: athletes and results](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results)

## 🌟 Features

### Medal Tally Analysis
- View overall medal tallies or filter by specific years and countries
- Interactive country and year selection
- Comprehensive medal statistics (Gold, Silver, Bronze, Total)

### Overall Analysis
- Key Olympic statistics dashboard (Editions, Host Cities, Sports, Events, Athletes, Nations)
- Trend analysis of participating nations over time
- Evolution of Olympic events and athlete participation
- Sport-wise event heatmap visualization
- Most successful athletes analysis with sport filtering

### Country-wise Analysis
- Individual country performance over time
- Country-specific sport excellence heatmaps
- Top 10 athletes by country
- Medal tally trends for selected nations

### 👥 Athlete-wise Analysis
- Age distribution analysis for all athletes and medalists
- Sport-specific age distribution for gold medalists
- Height vs Weight scatter plots with medal and gender insights
- Men vs Women participation trends over the years

## 🛠️ Tech Stack

- **Frontend**: Streamlit
- **Data Analysis**: Pandas, NumPy
- **Visualizations**: 
  - Plotly Express (Interactive charts)
  - Matplotlib (Static plots)
  - Seaborn (Statistical visualizations)
  - Plotly Figure Factory (Distribution plots)
- **Data Processing**: Custom preprocessing and helper functions

## 📁 Project Structure

```
olympics-data-analysis-web-app/
├── app.py                # Main Streamlit application
├── helper.py             # Data processing and analysis functions
├── preprocessor.py       # Data preprocessing utilities
├── requrements.txt       # libraries required
├── Notebook/
│   └── Olympics-analysis.ipynb  # Jupyter notebook with complete analysis
└── README.md
```

## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3.7+ installed on your system.

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/ShiryuCodes/olympics-data-analysis-web-app.git
   cd olympics-data-analysis-web-app
   ```

2. **Install required dependencies**
   ```bash
   pip install streamlit pandas plotly matplotlib seaborn numpy
   ```

3. **Run the application**
   ```bash
   streamlit run app.py
   ```

4. **Access the web app**
   Open your browser and navigate to `http://localhost:8501`

## 📊 Data Sources

The application uses two main datasets:
- `athlete_events.csv`: Contains detailed information about Olympic athletes, events, and medal winners
- `noc_regions.csv`: Maps National Olympic Committee codes to regions/countries

## 💡 How It Works

### Data Processing Pipeline
1. **Preprocessing**: Raw data is cleaned and processed using `preprocessor.py`
2. **Analysis Functions**: `helper.py` contains specialized functions for different types of analysis
3. **Interactive Interface**: `app.py` creates the Streamlit web interface with sidebar navigation

### Key Analysis Components

- **Medal Tally**: Aggregates medal counts by country and year with flexible filtering
- **Trend Analysis**: Time-series visualizations showing evolution of Olympic participation
- **Statistical Analysis**: Distribution analysis of athlete demographics
- **Comparative Analysis**: Cross-country and cross-sport comparisons

## 🔍 Detailed Analysis

For a comprehensive view of the data analysis process, including exploratory data analysis, visualization techniques, and insights discovery, check out the [complete Jupyter notebook](https://github.com/ShiryuCodes/olympics-data-analysis-web-app/blob/main/Notebook/Olympics-analysis.ipynb).

The notebook contains:
- Step-by-step data exploration
- Data cleaning and preprocessing techniques
- Statistical analysis methods
- Visualization development process
- Key insights and findings

## 🤝 Contributing

Contributions are welcome! Here are some ways you can contribute:

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/AmazingFeature`)
3. **Commit your changes** (`git commit -m 'Add some AmazingFeature'`)
4. **Push to the branch** (`git push origin feature/AmazingFeature`)
5. **Open a Pull Request**

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

## More Info

**Live Demo** - [Demo](https://huggingface.co/spaces/Shiryuxu/olympic-data-analysis)

**Notebook Link** - [Notebook](https://github.com/ShiryuCodes/olympics-data-analysis-web-app/blob/main/Notebook/Olympics-analysis.ipynb)

---

⭐ If you found this project helpful, please give it a star on GitHub!

---

*This project was developed as part of a data analysis learning journey, transforming Jupyter notebook analysis into an interactive web application.*
