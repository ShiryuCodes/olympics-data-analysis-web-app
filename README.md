# 🏅 Olympics Data Analysis Web App

A comprehensive data analysis web application built with Streamlit that provides interactive insights into Olympic Games data from 1896 to 2016. This project transforms raw Olympic data into meaningful visualizations and statistics through an intuitive web interface.

## 🌟 Features

### 📊 Medal Tally Analysis
- View overall medal tallies or filter by specific years and countries
- Interactive country and year selection
- Comprehensive medal statistics (Gold, Silver, Bronze, Total)

### 📈 Overall Analysis
- Key Olympic statistics dashboard (Editions, Host Cities, Sports, Events, Athletes, Nations)
- Trend analysis of participating nations over time
- Evolution of Olympic events and athlete participation
- Sport-wise event heatmap visualization
- Most successful athletes analysis with sport filtering

### 🌍 Country-wise Analysis
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
├── app.py                 # Main Streamlit application
├── helper.py             # Data processing and analysis functions
├── preprocessor.py       # Data preprocessing utilities
├── athlete_events.csv    # Main Olympic dataset
├── noc_regions.csv      # Country/Region mapping data
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

## 📱 Usage Examples

### Medal Tally Analysis
- Select "Overall" for both year and country to see all-time medal rankings
- Choose a specific year (e.g., 2016) to see that Olympics' medal table
- Select a country to see their historical performance

### Country Analysis
- Pick any country from the dropdown to see their Olympic journey
- Analyze which sports they excel in through heatmap visualizations
- Discover their top-performing athletes

### Athlete Demographics
- Explore age distributions across different medal categories
- Compare physical attributes (height/weight) across sports
- Track gender participation trends over Olympic history

## 🤝 Contributing

Contributions are welcome! Here are some ways you can contribute:

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/AmazingFeature`)
3. **Commit your changes** (`git commit -m 'Add some AmazingFeature'`)
4. **Push to the branch** (`git push origin feature/AmazingFeature`)
5. **Open a Pull Request**

### Ideas for Contributions
- Add more visualization types
- Implement additional statistical analyses
- Create export functionality for charts and data
- Add data for more recent Olympics
- Improve UI/UX design
- Add caching for better performance

## 📈 Future Enhancements

- [ ] Integration with real-time Olympic data APIs
- [ ] Additional sports-specific analysis modules
- [ ] Predictive modeling for future Olympic performance
- [ ] Enhanced mobile responsiveness
- [ ] Data export functionality (CSV, PDF reports)
- [ ] Integration with more recent Olympic data (2020, 2024)

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Olympic data sourced from publicly available datasets
- Built with the amazing Streamlit framework
- Visualization libraries: Plotly, Matplotlib, Seaborn
- Special thanks to the open-source community

## 📧 Contact

**Shiryu** - [GitHub Profile](https://github.com/ShiryuCodes)

Project Link: [https://github.com/ShiryuCodes/olympics-data-analysis-web-app](https://github.com/ShiryuCodes/olympics-data-analysis-web-app)

---

⭐ If you found this project helpful, please give it a star on GitHub!

---

*This project was developed as part of a data analysis learning journey, transforming Jupyter notebook analysis into an interactive web application.*
