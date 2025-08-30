
# Freedom House Data Visualization 🌍

![Freedom Maps](https://raw.githubusercontent.com/zafariabbas68/Freedom-House-Map/main/images/freedom-maps.png)



## Overview

This project is an interactive data visualization dashboard that displays global freedom scores based on data from Freedom House. The application provides an intuitive way to explore freedom trends across countries and over time, featuring interactive maps, time series charts, and detailed country information.

## Features

### 🌍 Interactive World Map
- Color-coded choropleth map showing freedom scores for all countries
- Multiple color schemes (Red-Yellow-Green, Blue Scale, Viridis, Plasma)
- Zoom and pan functionality for detailed exploration
- Hover tooltips displaying country name, score, and freedom status

### 📊 Time Series Analysis
- Interactive line charts showing freedom score trends over time
- Multi-country comparison capabilities
- Year markers highlighting selected time periods

### 🔍 Detailed Country Information
- Click on any country to view detailed information
- Display of official country names, ISO codes, and freedom status
- Historical data visualization for selected countries

### 📈 Change Tracking
- Year-over-year change analysis
- Categorization of countries as Improved, Declined, or No Change
- Percentage calculations for change categories

### 🎨 Customizable Visualization
- Multiple color schemes to suit different preferences
- Responsive design that works on various screen sizes
- Interactive controls for data exploration

## Data Sources

The application uses data from Freedom House's annual reports:
- Freedom in the World (FIW) 2013-2024
- Freedom on the Net (FOTN)
- Nations in Transit (NIT)

## Installation

### Prerequisites
- Python 3.7+
- pip (Python package manager)

### Step-by-Step Installation

1. Clone the repository:

```bash
git clone https://github.com/zafariabbas68/Freedom-House-Data-Visualisation.git
cd Freedom-House-Data-Visualisation
```

2. Create a virtual environment (recommended):

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required packages:

```bash
pip install -r requirements.txt
```

4. Download the data files from Freedom House and place them in the `data/` directory:

- `All_data_FIW_2013-2024.xlsx`
- `FOTN24_Country_Score_Data.xlsx`
- `All_Data_Nations_in_Transit_NIT_2005-2024_For_website.xlsx`

5. Run the application:

```bash
python app.py
```

6. Open your web browser and navigate to `http://localhost:8050`

## Usage

### Exploring the Map

1. Use the year slider to select a specific year
2. Choose a color scheme from the dropdown menu
3. Hover over countries to see basic information
4. Click on a country to view detailed information in the side panel

### Analyzing Trends

1. Select countries from the dropdown or click on the map
2. View historical trends in the time series chart
3. Use the year slider to see how scores have changed over time

### Understanding Changes

1. The change table automatically updates based on the selected year
2. View how many countries improved, declined, or had no change
3. See percentages of countries in each category

## Project Structure

```
Freedom-House-Data-Visualisation/
│
├── app.py                 # Main application file
├── requirements.txt       # Python dependencies
├── README.md              # Project documentation
├── data/                  # Directory for data files (not included in repo)
├── images/                # Directory for visualization screenshots
│   └── freedom-maps.png   # Main map visualization
└── assets/                # Directory for CSS and other assets
```

## Technical Details

### Technologies Used

- **Python**: Data processing and backend
- **Pandas**: Data manipulation and analysis
- **Plotly**: Interactive visualizations
- **Dash**: Web application framework
- **PyCountry**: Country code mapping

### Data Processing

The application includes robust data processing capabilities that:

- Automatically detect data structures in Excel files
- Handle various country naming conventions
- Map country names to ISO codes for visualization
- Clean and validate data entries

### Visualization Features

- Responsive design that works on desktop and mobile devices
- Interactive elements with hover and click functionality
- Multiple color schemes for different visual preferences
- Zoom and pan capabilities for detailed exploration

## Contributing

We welcome contributions to improve this visualization tool! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Areas for Improvement

- Additional data sources integration
- Enhanced mobile responsiveness
- More visualization types (bar charts, scatter plots)
- Export functionality for charts and data
- User authentication for saving preferences

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- Data provided by [Freedom House](https://freedomhouse.org/)
- Built with [Plotly](https://plotly.com/) and [Dash](https://plotly.com/dash/)
- Country data from [PyCountry](https://pypi.org/project/pycountry/)

## Contact

For questions or suggestions about this project, please contact:

Ghulam Abbas Zafari
GitHub: [@zafariabbas68](https://github.com/zafariabbas68)
Email: [Your Email Address]

## Future Developments

Planned enhancements for future versions:

- Real-time data updates from Freedom House API
- Social sharing functionality for visualizations
- Comparative analysis tools between countries
- Regional aggregation and analysis
- Predictive modeling of freedom trends

