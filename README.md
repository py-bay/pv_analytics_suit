# PV Analytics Suite

Machine Learning-based optimization of electric vehicle charging using solar energy surplus and weather forecasts.

## Overview

Predict optimal EV charging windows by analyzing residential PV system data and weather patterns using ML algorithms.

**Research Question:** *Can ML algorithms predict optimal time windows for EV charging with solar surplus?*

## Data

- **PV System:** 3+ years residential solar data (15-min intervals)
- **Weather:** OpenWeather API integration for forecasts
- **Target:** Optimal charging windows classification

## Quick Start

```bash
# Install dependencies
uv sync

# Start analysis
uv run jupyter lab
```

## Notebooks

- `01_pv_data_exploration.ipynb` - Data exploration and patterns
- `02_data_description_analysis.ipynb` - Data quality analysis  
- `03_open_weather_api_samples.ipynb` - Weather API testing

## Setup

Create `.env` file:
```bash
OPENWEATHER_API_KEY=your_key
LAT=LON=13.637528
```

## 🎓 Academic Project

Computer Science research at Provadis Hochschule  
Contact: simon.dietrich@stud-provadis-hochschule.de

---

*Machine Learning for Renewable Energy Optimization*