# 🏅 Olympics Data Analysis Dashboard

<div align="center">

[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/downloads/)
[![Streamlit](https://img.shields.io/badge/streamlit-latest-FF4B4B?logo=streamlit&logoColor=white)](https://streamlit.io/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/Nayon09/Olympics-Data-Analysis?style=social)](https://github.com/Nayon09/Olympics-Data-Analysis)

An interactive web application for analyzing 120 years of Olympic history with dynamic visualizations and comprehensive insights.

[Live Demo](#) • [Report Bug](https://github.com/Nayon09/Olympics-Data-Analysis/issues) • [Request Feature](https://github.com/Nayon09/Olympics-Data-Analysis/issues)

</div>

---

## ✨ Features

- 📊 **Medal Tally Analysis** - Overall, year-wise, and country-specific medal counts
- 🌍 **Country-wise Insights** - Track countries' performance over time with detailed statistics
- 🏃 **Athlete Analytics** - Age distribution, physical attributes, and performance metrics
- 📈 **Interactive Visualizations** - Dynamic charts, heatmaps, and trend lines using Plotly & Matplotlib
- 🎯 **Advanced Filtering** - Filter data by year, country, sport, and athlete
- 📉 **Historical Trends** - Analyze the evolution of Olympics across 120+ years

## 🚀 Quick Start

### Prerequisites

- Python 3.8 or higher
- pip (Python package installer)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Nayon09/Olympics-Data-Analysis.git
   cd Olympics-Data-Analysis
   ```

2. **Create a virtual environment** (recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application**
   ```bash
   streamlit run app.py
   ```

5. **Open in browser**
   The app will automatically open at `http://localhost:8501`

## 📊 Dashboard Sections

### 🏆 Medal Tally
- View overall medal counts across all Olympic Games
- Filter by specific year or country
- Compare country performance in selected Olympics

### 📈 Overall Analysis
- Key statistics (editions, host cities, sports, events, nations, athletes)
- Participating nations trend over time
- Events evolution across Olympics
- Athlete participation growth
- Sports-wise event distribution heatmap
- Most successful athletes by sport

### 🌐 Country-wise Analysis
- Year-wise medal progression for selected country
- Sports specialization heatmap
- Top 10 athletes by country
- Historical performance trends

### 👥 Athlete-wise Analysis
- Age distribution across medal categories
- Age patterns by sport
- Height vs Weight analysis by sport
- Athlete physical attributes correlation

## 📁 Project Structure

```
Olympics-Data-Analysis/
├── app.py                  # Main Streamlit application
├── helper.py              # Analytics helper functions
├── preprocessor.py        # Data preprocessing utilities
├── requirements.txt       # Python dependencies
├── setup.sh              # Installation script
├── Procfile              # Heroku deployment configuration
├── athlete_events.csv    # Olympic events dataset
├── noc_regions.csv       # Country codes mapping
├── LICENSE               # MIT License
└── README.md            # This file
```

## 📚 Dataset Information

The application uses the [120 Years of Olympic History Dataset](https://www.kaggle.com/code/narminhumbatli/120-years-of-olympic-history-athletes-and-results/input) from Kaggle.

**Dataset Contents:**
- **athlete_events.csv**: 271,116 records of athlete performances with 15 attributes
- **noc_regions.csv**: Country codes and region mappings

## 🛠️ Technologies Used

| Technology | Purpose |
|-----------|---------|
| **Streamlit** | Web app framework |
| **Pandas** | Data manipulation & analysis |
| **Plotly** | Interactive visualizations |
| **Matplotlib** | Statistical plots |
| **Seaborn** | Enhanced data visualization |
| **Python** | Core programming language |

## 💡 Key Functions

### `app.py`
- Main application interface with Streamlit
- Sidebar navigation and data selection
- Layout and visualization rendering

### `helper.py`
Key analytical functions:
- `fetch_medal_tally()` - Medal statistics by year/country
- `most_successful()` - Top athletes by medal count
- `yearwise_medal_tally()` - Country performance timeline
- `country_event_heatmap()` - Sport specialization analysis
- `weight_v_height()` - Physical attributes comparison

### `preprocessor.py`
- Data cleaning and transformation
- Feature engineering
- Data normalization

## 📈 Usage Examples

### Medal Tally
1. Select "Medal Tally" from sidebar
2. Choose year (Overall or specific)
3. Choose country (Overall or specific)
4. View medal distribution table

### Country Analysis
1. Select "Country-wise Analysis"
2. Choose country from dropdown
3. Explore medal trends, sport specializations, and top athletes

### Athlete Insights
1. Select "Athlete wise Analysis"
2. View age distribution by medal category
3. Analyze height vs weight by sport
4. Understand physical requirements for different sports

## 🚀 Deployment

### Heroku Deployment

```bash
# Create Heroku app
heroku create your-app-name

# Deploy
git push heroku main

# View logs
heroku logs --tail
```

### Local Development
```bash
streamlit run app.py
```

## 📊 Data Insights

The dashboard reveals fascinating Olympic trends:
- Evolution of participating nations (1896-2016)
- Growth in number of sports and events
- Athlete participation patterns
- Physical attributes across different sports
- Country-specific performance trends

## 🤝 Contributing

Contributions are welcome! Here's how to get started:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Dataset source: [Kaggle - 120 Years of Olympic History](https://www.kaggle.com/code/narminhumbatli/120-years-of-olympic-history-athletes-and-results/input)
- Built with [Streamlit](https://streamlit.io/)
- Visualizations with [Plotly](https://plotly.com/) and [Matplotlib](https://matplotlib.org/)

## 📧 Contact & Support

- **Author**: [Nayon09](https://github.com/Nayon09)
- **Issues**: [GitHub Issues](https://github.com/Nayon09/Olympics-Data-Analysis/issues)
- **Discussions**: [GitHub Discussions](https://github.com/Nayon09/Olympics-Data-Analysis/discussions)

---

<div align="center">

Made with ❤️ by [Nayon09](https://github.com/Nayon09)

</div>
