# PEC2: Study of Data Visualization Techniques

This repository contains a collection of interactive visualizations exploring Barcelona tourist data. The data was obtained from the <a href="https://www.ine.es/jaxiT3/Tabla.htm?t=52048" target="_blank">Instituto Nacional de Estadística</a> and processed using Jupyter Notebook to create specific datasets for each visualization.

## 📊 Visualizations

### 1. Area Chart
- **Description**: A stacked area chart showing the evolution of monthly tourists visiting Barcelona, broken down by country of origin
- **Interactive Version**: <a href="https://datawrapper.dwcdn.net/hxr40/1/" target="_blank">View on Datawrapper</a>

### 2. Nightingale Rose Chart
- **Description**: A visualization of monthly tourist visits to Barcelona from the top three visiting countries (France, United Kingdom, United States)
- **Implementation**: Custom-built using HTML, CSS, JavaScript, and D3.js library
- **Interactive Version**: <a href="https://tim-thorp.github.io/" target="_blank">View on GitHub Pages</a>
- **Credit**: Forked from <a href="https://github.com/tulsyanp/data-visualization-d3-js-nightingale-rose-chart" target="_blank">tulsyanp/data-visualization-d3-js-nightingale-rose-chart</a>

### 3. Beeswarm Plot
- **Description**: A visualization of the average number of annual tourist visits to Barcelona, broken down by region and country of origin
- **Interactive Version**: <a href="https://public.flourish.studio/visualisation/20216708/" target="_blank">View on Flourish</a>

## 🗂️ Repository Structure

```
├── data_preparation/
│   ├── area_chart.csv          # Processed data for area chart
│   ├── beeswarm.csv            # Processed data for beeswarm plot
│   ├── data_preparation.ipynb  # Data processing notebook
│   ├── nightingale.csv         # Processed data for Nightingale chart
│   └── raw_data.csv            # Original dataset from INE
├── nightingale/
│   ├── index.html              # Main visualization page
│   ├── nightingale.css         # Styling
│   └── nightingale.js          # Visualization logic
```

## 📝 Data Preparation

The data preparation process is documented in `data_preparation.ipynb`. This notebook includes the transformation of the raw INE data into specific CSV files optimized for each visualization type.

## 🔗 Links

- <a href="https://tim-thorp.github.io/" target="_blank">GitHub Pages Site</a>
- <a href="https://datawrapper.dwcdn.net/hxr40/1/" target="_blank">Area Chart (Datawrapper)</a>
- <a href="https://public.flourish.studio/visualisation/20216708/" target="_blank">Beeswarm Plot (Flourish)</a>
- <a href="https://www.ine.es/jaxiT3/Tabla.htm?t=52048" target="_blank">Original Data Source (INE)</a>