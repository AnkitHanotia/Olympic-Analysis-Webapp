# Olympics Data Analysis Web App

A comprehensive Streamlit web application for analyzing Olympic Games data from 1896 to 2016. This interactive dashboard provides insights into Olympic history, medal tallies, country-wise analysis, and athlete statistics.

## 🏆 Features

### 📊 **Medal Tally Analysis**
- View overall medal counts by country
- Filter by specific years and countries
- Interactive medal tally tables

### 🌍 **Overall Analysis**
- Olympic statistics overview (editions, hosts, sports, events, nations, athletes)
- Participating nations trend over time
- Events and athletes growth analysis
- Sport-wise event heatmap
- Most successful athletes by sport

### 🏅 **Country-wise Analysis**
- Medal performance trends for specific countries
- Country-specific sport excellence heatmaps
- Top 10 athletes from selected countries
- Year-wise medal tally visualization

### 👥 **Athlete Analysis**
- Age distribution analysis for medalists
- Sport-specific age distributions
- Height vs Weight analysis with medal correlation
- Gender participation trends over time

## 📁 Project Structure

```
olympics-data-analysis-web-app/
├── app.py                 # Main Streamlit application
├── helper.py              # Helper functions for data processing
├── preprocessor.py        # Data preprocessing utilities
├── athlete_events.csv     # Olympic events dataset
├── noc_regions.csv        # Country/region mapping
├── requirements.txt       # Python dependencies
├── Procfile              # Heroku deployment configuration
├── setup.sh              # Streamlit configuration script
└── README.md             # Project documentation
```

## 🚀 Installation

### Prerequisites
- Python 3.7 or higher
- pip (Python package installer)

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/AnkitHanotia/olympics-data-analysis-web-app.git
   cd olympics-data-analysis-web-app
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   
   # On Windows
   venv\Scripts\activate
   
   # On macOS/Linux
   source venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application**
   ```bash
   streamlit run app.py
   ```

5. **Open your browser**
   Navigate to `http://localhost:8501` to view the application

## 📊 Dataset

The application uses the **120 Years of Olympic History** dataset from Kaggle, which includes:
- **athlete_events.csv**: Contains information about athletes and their Olympic performances
- **noc_regions.csv**: Maps National Olympic Committee codes to country names

**Dataset Source**: [Kaggle - 120 Years of Olympic History](https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results)

## 🛠️ Technologies Used

- **Streamlit**: Web application framework
- **Pandas**: Data manipulation and analysis
- **Plotly**: Interactive visualizations
- **Matplotlib & Seaborn**: Statistical plotting
- **NumPy**: Numerical computing

## 🌐 Deployment

### Local Development
```bash
streamlit run app.py
```

### Heroku Deployment
The application is configured for Heroku deployment with:
- `Procfile`: Specifies the web process
- `setup.sh`: Configures Streamlit for production
- `requirements.txt`: Lists all dependencies

**Live Demo**: [Olympics Analysis App](https://oda-campusx.herokuapp.com/)

## 📈 Key Insights

This application provides valuable insights into:
- Olympic participation trends over 120 years
- Country performance patterns
- Athlete demographics and characteristics
- Sport evolution and popularity
- Gender participation evolution

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Dataset provided by [Kaggle](https://www.kaggle.com/)
- Olympic data from [Olympics.org](https://www.olympics.org/)
- Built with [Streamlit](https://streamlit.io/)

## 📞 Contact

For questions or suggestions, please open an issue on GitHub or contact the maintainers.

---

**Note**: This application is for educational and analytical purposes. The data covers Olympic Games from 1896 to 2016.
