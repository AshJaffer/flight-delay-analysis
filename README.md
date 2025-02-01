# US Flight Delay Analysis (2015)

## Project Overview
This project analyzes flight delay patterns and airline performance across four major US airports (BOS, JFK, SFO, and LAX) using the Department of Transportation's 2015 dataset. The analysis demonstrates data manipulation techniques using Python's data science libraries to extract meaningful insights about flight operations and delays.

## Analysis Components

### 1. Data Preprocessing and Cleaning
- Filtering specific airports (BOS, JFK, SFO, LAX)
- Handling missing values and outliers
- Converting timestamps and standardizing data types
- Creating delay indicators (flights delayed ≥ 15 minutes)

### 2. Airport Flight Volume Analysis
- Calculation of total flights per airport
- Integration with airport metadata
- Comparative analysis across locations

### 3. Airline Performance Metrics
- Identification of top three airlines by flight volume
- Calculation of delay percentages
- Performance ranking incorporating both volume and reliability

### 4. Monthly Delay Patterns
- Calculation of monthly delay percentages by airport
- Temporal trend analysis
- Seasonal pattern identification

## Technologies Used
- Python 3.x
- pandas: Data manipulation and analysis
- numpy: Numerical computations
- Jupyter Notebook: Development environment

## Dataset Description
The analysis uses three primary datasets:
- `flights.csv`: Flight operations data for 2015
- `airports.csv`: Airport metadata and information
- `airlines.csv`: Airline carrier information

## Project Structure
```
flight-delay-analysis/
├── data/
│   ├── flights.csv
│   ├── airports.csv
│   └── airlines.csv
├── flight_analysis.ipynb
└── README.md
```

## Setup Instructions

1. Clone the Repository:
```bash
git clone https://github.com/[your-username]/flight-delay-analysis.git
cd flight-delay-analysis
```

2. Install Required Libraries:
```bash
pip install pandas numpy jupyter
```

3. Data Requirements:
- Place the three CSV files in the `data` directory
- Ensure file names match the expected format

4. Run the Analysis:
```bash
jupyter notebook flight_analysis.ipynb
```

## Key Findings

### Airport Operations
- Comparative flight volumes across major airports
- Operational differences between locations
- Peak period identification

### Airline Performance
- Top three airlines by flight volume identified
- Delay percentage variations among carriers
- Performance metrics across different routes

### Delay Patterns
- Monthly delay percentage variations
- Airport-specific delay characteristics
- Seasonal trend identification

## Future Enhancements
- Integration of weather data
- Additional airport analysis
- Route-specific performance metrics
- Historical trend comparison

## Contact Information
Ashhad Jaffer
Ajaffer@umich.edu
University of Michigan-School of Information
https://www.linkedin.com/in/ash0707/
