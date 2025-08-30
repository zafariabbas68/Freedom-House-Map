
# Freedom House Data Visualization 🌍

![Freedom Maps](https://raw.githubusercontent.com/zafariabbas68/Freedom-House-Map/main/images/freedom-maps.png)

## Overview

An interactive dashboard visualizing global freedom scores from Freedom House data. This application provides insightful visualizations of freedom trends across countries and over time using interactive maps, charts, and detailed analytics.

## Features

### 🗺️ Interactive World Map
- Choropleth map color-coded by freedom scores
- Multiple color schemes (Red-Yellow-Green, Blue Scale, Viridis, Plasma)
- Zoom and pan functionality
- Hover tooltips with country information

### 📈 Time Series Analysis
- Interactive line charts showing historical trends
- Multi-country comparison tools
- Year selection with dynamic updates

### 🔍 Country Insights
- Detailed country profiles on click
- Historical data visualization
- Freedom status classification

### 📊 Change Analytics
- Year-over-year change tracking
- Categorization of countries (Improved/Declined/No Change)
- Statistical analysis of freedom trends

## Data Sources

- Freedom in the World (FIW) 2013-2024
- Freedom on the Net (FOTN)
- Nations in Transit (NIT) 2005-2024

## Installation

### Prerequisites
- Python 3.7+
- pip package manager

### Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/zafariabbas68/Freedom-House-Map.git
   cd Freedom-House-Map


   Create virtual environment:
bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:
bash
pip install -r requirements.txt
Download data files from Freedom House and place in data/ directory:
All_data_FIW_2013-2024.xlsx
FOTN24_Country_Score_Data.xlsx
All_Data_Nations_in_Transit_NIT_2005-2024_For_website.xlsx
Run the application:
bash
python app.py
Access the dashboard at http://localhost:8050
Project Structure

text
Freedom-House-Map/
├── app.py                 # Main Dash application
├── requirements.txt       # Python dependencies
├── README.md             # Project documentation
├── data/                 # Data directory (gitignored)
├── images/               # Visual assets
│   └── freedom-maps.png  # Main preview image
└── assets/               # CSS and styling
Usage

Map Exploration: Use the year slider and select color schemes
Country Analysis: Click on countries for detailed information
Trend Analysis: Select multiple countries for comparative analysis
Change Tracking: View year-over-year changes in the analytics panel
Technologies Used

Python - Backend processing
Pandas - Data manipulation
Plotly - Interactive visualizations
Dash - Web framework
PyCountry - Country code mapping
Contributing

Contributions are welcome! Please:

Fork the repository
Create a feature branch
Commit your changes
Submit a pull request
License

MIT License - see LICENSE file for details

Contact

Ghulam Abbas Zafari
GitHub: @zafariabbas68
Email: [Your Email]

Acknowledgments

Data provided by Freedom House
Built with Plotly Dash
Visualization inspiration from various open-source projects
text

## 2. Create requirements.txt:

```txt
dash==2.14.2
pandas==2.0.3
plotly==5.18.0
numpy==1.24.3
pycountry==22.3.5
openpyxl==3.1.2
xlrd==2.0.1
gunicorn==21.2.0
3. Create .gitignore file:

gitignore
# Python
__pycache__/
*.py[cod]
*$py.class
*.so
.Python
build/
develop-eggs/
dist/
downloads/
eggs/
.eggs/
lib/
lib64/
parts/
sdist/
var/
wheels/
*.egg-info/
.installed.cfg
*.egg

# Virtual environment
venv/
ENV/
env.bak/
venv.bak/

# IDE
.vscode/
.idea/
*.swp
*.swo

# OS
.DS_Store
.DS_Store?
._*
.Spotlight-V100
.Trashes
ehthumbs.db
Thumbs.db

# Data files
data/
*.xlsx
*.csv
*.json

# Logs
*.log
logs/

# Temporary files
temp/
tmp/
4. Now run these commands to set up your new repository:

bash
# Navigate to your project directory
cd '/Users/ghulamabbaszafari/Downloads/Freedom House Data visualisation'

# Initialize git (if not already done)
git init

# Add remote origin
git remote add origin https://github.com/zafariabbas68/Freedom-House-Map.git

# Create the files
echo "# Freedom House Data Visualization 🌍

![Freedom Maps](https://raw.githubusercontent.com/zafariabbas68/Freedom-House-Map/main/images/freedom-maps.png)

## Overview

An interactive dashboard visualizing global freedom scores from Freedom House data. This application provides insightful visualizations of freedom trends across countries and over time using interactive maps, charts, and detailed analytics.

## Features

### 🗺️ Interactive World Map
- Choropleth map color-coded by freedom scores
- Multiple color schemes (Red-Yellow-Green, Blue Scale, Viridis, Plasma)
- Zoom and pan functionality
- Hover tooltips with country information

### 📈 Time Series Analysis
- Interactive line charts showing historical trends
- Multi-country comparison tools
- Year selection with dynamic updates

### 🔍 Country Insights
- Detailed country profiles on click
- Historical data visualization
- Freedom status classification

### 📊 Change Analytics
- Year-over-year change tracking
- Categorization of countries (Improved/Declined/No Change)
- Statistical analysis of freedom trends

## Data Sources

- Freedom in the World (FIW) 2013-2024
- Freedom on the Net (FOTN)
- Nations in Transit (NIT) 2005-2024

## Installation

### Prerequisites
- Python 3.7+
- pip package manager

### Setup Instructions

1. **Clone the repository:**
   \`\`\`bash
   git clone https://github.com/zafariabbas68/Freedom-House-Map.git
   cd Freedom-House-Map
   \`\`\`

2. **Create virtual environment:**
   \`\`\`bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\\Scripts\\activate
   \`\`\`

3. **Install dependencies:**
   \`\`\`bash
   pip install -r requirements.txt
   \`\`\`

4. **Download data files** from Freedom House and place in \`data/\` directory:
   - \`All_data_FIW_2013-2024.xlsx\`
   - \`FOTN24_Country_Score_Data.xlsx\`
   - \`All_Data_Nations_in_Transit_NIT_2005-2024_For_website.xlsx\`

5. **Run the application:**
   \`\`\`bash
   python app.py
   \`\`\`

6. **Access the dashboard** at \`http://localhost:8050\`

## Project Structure

\`\`\`
Freedom-House-Map/
├── app.py                 # Main Dash application
├── requirements.txt       # Python dependencies
├── README.md             # Project documentation
├── data/                 # Data directory (gitignored)
├── images/               # Visual assets
│   └── freedom-maps.png  # Main preview image
└── assets/               # CSS and styling
\`\`\`

## Usage

1. **Map Exploration**: Use the year slider and select color schemes
2. **Country Analysis**: Click on countries for detailed information
3. **Trend Analysis**: Select multiple countries for comparative analysis
4. **Change Tracking**: View year-over-year changes in the analytics panel

## Technologies Used

- **Python** - Backend processing
- **Pandas** - Data manipulation
- **Plotly** - Interactive visualizations
- **Dash** - Web framework
- **PyCountry** - Country code mapping

## Contributing

Contributions are welcome! Please:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Submit a pull request

## License

MIT License - see LICENSE file for details

## Contact

**Ghulam Abbas Zafari**  
GitHub: [@zafariabbas68](https://github.com/zafariabbas68)  
Email: [Your Email]

## Acknowledgments

- Data provided by [Freedom House](https://freedomhouse.org/)
- Built with [Plotly Dash](https://plotly.com/dash/)
- Visualization inspiration from various open-source projects" > README.md

# Create requirements.txt
echo "dash==2.14.2
pandas==2.0.3
plotly==5.18.0
numpy==1.24.3
pycountry==22.3.5
openpyxl==3.1.2
xlrd==2.0.1
gunicorn==21.2.0" > requirements.txt

# Create .gitignore
echo "# Python
__pycache__/
*.py[cod]
*$py.class
*.so
.Python
build/
develop-eggs/
dist/
downloads/
eggs/
.eggs/
lib/
lib64/
parts/
sdist/
var/
wheels/
*.egg-info/
.installed.cfg
*.egg

# Virtual environment
venv/
ENV/
env.bak/
venv.bak/

# IDE
.vscode/
.idea/
*.swp
*.swo

# OS
.DS_Store
.DS_Store?
._*
.Spotlight-V100
.Trashes
ehthumbs.db
Thumbs.db

# Data files
data/
*.xlsx
*.csv
*.json

# Logs
*.log
logs/

# Temporary files
temp/
tmp/" > .gitignore

# Create assets directory for CSS (optional)
mkdir -p assets

# Create images directory and ensure your image is there
mkdir -p images
# Make sure your freedom-maps.png is in the images directory

# Add all files to git
git add README.md requirements.txt .gitignore

# Add the image (make sure it exists in images/)
git add images/freedom-maps.png

# Commit
git commit -m "Initial commit: Complete project setup with README, requirements, and gitignore"

# Push to main branch (might need to use --force if repository already exists)
git branch -M main
git push -u origin main
5. If you need to force push (since you recreated the repository):

bash
git push -f origin main
This will set up your new repository with a comprehensive README, proper dependency management, and the image will display correctly using the absolute GitHub URL!
