# IPL Cricket Data Analysis

## Overview

This project analyzes Indian Premier League (IPL) cricket match data, providing insights into team performances, match outcomes, and toss decisions. The analysis is presented through various visualizations created with matplotlib.

## Dataset

The analysis uses the `matches.csv` dataset which contains information about IPL matches including:

- Match dates
- Teams
- Venues
- Toss information
- Match winners
- And more

## Features

- Data cleaning and preprocessing
- Analysis of top-performing teams
- Visualization of match statistics
- Toss decision analysis
- Time-based analysis (by day, month, year)

## Visualizations

- Bar charts showing team wins
- Matches played by each team
- Monthly distribution of matches
- Winning percentages by team
- Toss decision preferences

## Requirements

All dependencies are listed in the `requirements.txt` file. Key libraries include:

- pandas
- matplotlib
- numpy
- jupyter
- scikit-learn
- seaborn

## Setup and Usage

### Setting up a Virtual Environment

```bash
# Create a virtual environment
python -m venv .venv

# Activate the environment (Windows)
.venv\Scripts\Activate.ps1

# Activate the environment (Linux/macOS)
# source .venv/bin/activate

# Install dependencies
pip install -r requirements.txt
```

### Running the Analysis

Open and run the Jupyter notebook:

```bash
jupyter notebook main.ipynb
```

## Project Structure

- `main.ipynb` - Jupyter notebook containing all analysis code
- `matches.csv` - Dataset with IPL match information
- `requirements.txt` - Required Python packages
- `README.md` - This documentation file

## Future Enhancements

- Player performance analysis
- Prediction modeling for match outcomes
- Interactive dashboard development
