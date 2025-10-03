# Discovering Disease Outbreaks: A Data Science Approach

A data science project for the World Health Organization (WHO) to identify and map disease outbreaks worldwide using machine learning clustering techniques applied to news headlines.

## 🎯 Project Overview

This project simulates the role of a data scientist at the WHO, analyzing hundreds of daily news headlines to detect patterns indicating disease epidemics around the globe. By extracting geographic information and clustering outbreak locations, this analysis enables efficient resource allocation for epidemic response.

## 🔬 Objective

Analyze 650 curated news headlines to:
- Extract location data (cities and countries) from unstructured text
- Identify geographic coordinates for each headline
- Cluster headlines by geographic proximity
- Detect patterns indicating disease outbreaks
- Visualize findings on interactive maps
- Provide actionable insights for WHO resource deployment

## 📊 Dataset

**Source:** `headlines.txt`
- 650 synthetically created news headlines
- Modeled on real health mentions from early 2016
- Geographic distribution: ~50% United States, ~50% rest of world
- Example headlines:
  - "Zika spreads to Winter Park"
  - "Durango is infested with Hepatitis B"
  - "Mad Cow Disease Hits London"

## 🛠️ Technologies & Libraries

**Programming Language:** Python 3.7+

**Core Libraries:**
- `pandas` - Data manipulation and analysis
- `scikit-learn` - K-means and DBSCAN clustering algorithms
- `matplotlib` - Data visualization
- `basemap` - Geographic map visualization
- `re` - Regular expression text extraction
- `geonamescache` - Geographic coordinate lookup
- `jupyter` - Interactive development environment
- `nbconvert` - Report generation

## 📁 Project Structure
