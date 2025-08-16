# Olympic Analysis Dashboard

A comprehensive Streamlit web application for analyzing Olympic Games data with interactive visualizations and insights.

## Required Data Files

This application requires two CSV files to function properly:

1. **athlete_events.csv** - Main Olympic athletes dataset containing:
   - Athlete information (Name, Age, Height, Weight, Sex)
   - Event details (Year, Season, City, Sport, Event)
   - Team and NOC information
   - Medal results (Gold, Silver, Bronze, or NaN)

2. **noc_regions.csv** - NOC (National Olympic Committee) to region mapping containing:
   - NOC codes
   - Region names

## Data Sources

You can download these datasets from:
- [Kaggle Olympic Dataset](https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results)
- Place both CSV files in the root directory of this project

## Installation

1. Install required packages:
```bash
pip install -r requirements.txt
```

2. Download and place the required CSV files in the project directory

3. Run the application:
```bash
streamlit run app.py
```

## Features

- **Medal Tally**: View medal counts by year and country
- **Overall Analysis**: Statistics and trends over time
- **Country-wise Analysis**: Detailed country performance analysis
- **Athlete Analysis**: Age distributions, height vs weight analysis, and gender participation trends

## Fixed Issues

- Added proper error handling for missing data files
- Fixed data aggregation logic in helper functions
- Improved application stability and user feedback
A Streamlit-based interactive data analysis project on Olympic history using Python, Pandas, Matplotlib, Seaborn, and Plotly.
## 📸 Demo Screenshots

### 🖼️ App Preview

![Screenshot 1](Screenshot%20(1287).png)
![Screenshot 2](Screenshot%20(1288).png)
![Screenshot 3](Screenshot%20(1289).png)
![Screenshot 4](Screenshot%20(1290).png)
![Screenshot 5](Screenshot%20(1291).png)
![Screenshot 6](Screenshot%20(1292).png)
![Screenshot 7](Screenshot%20(1293).png)
![Screenshot 8](Screenshot%20(1294).png)
![Screenshot 9](Screenshot%20(1295).png)
![Screenshot 10](Screenshot%20(1296).png)
![Screenshot 11](Screenshot%20(1297).png)
![Screenshot 12](Screenshot%20(1298).png)
![Screenshot 13](Screenshot%20(1299).png)
![Screenshot 14](Screenshot%20(1300).png)
![Screenshot 15](Screenshot%20(1301).png)
![Screenshot 16](Screenshot%20(1302).png)
![Screenshot 17](Screenshot%20(1303).png)
![Screenshot 18](Screenshot%20(1304).png)
![Screenshot 19](Screenshot%20(1305).png)
![Screenshot 20](Screenshot%20(1306).png)
![Screenshot 21](Screenshot%20(1307).png)
