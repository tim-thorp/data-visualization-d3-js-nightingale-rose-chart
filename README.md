# PEC2: Study of Data Visualization Techniques

This repository contains a collection of interactive visualizations exploring Barcelona tourist data. The data was obtained from the [Instituto Nacional de Estadística](https://www.ine.es/jaxiT3/Tabla.htm?t=52048) and processed using Jupyter Notebook to create specific datasets for each visualization.

## 📊 Visualizations

### 1. Area Chart
- **Description**: A stacked area chart showing the evolution of monthly tourists visiting Barcelona, broken down by country of origin
- **Interactive Version**: [View on Datawrapper](https://datawrapper.dwcdn.net/hxr40/1/)

### 2. Nightingale Rose Chart
- **Description**: A visualization of monthly tourist visits to Barcelona from the top three visiting countries (France, United Kingdom, United States)
- **Implementation**: Custom-built using HTML, CSS, JavaScript, and D3.js library
- **Interactive Version**: [View on GitHub Pages](https://tim-thorp.github.io/)
- **Credit**: Forked from [tulsyanp/data-visualization-d3-js-nightingale-rose-chart](https://github.com/tulsyanp/data-visualization-d3-js-nightingale-rose-chart)

### 3. Beeswarm Plot
- **Description**: A visualization of the average number of annual tourist visits to Barcelona, broken down by region and country of origin
- **Interactive Version**: [View on Flourish](https://public.flourish.studio/visualisation/20216708/)

## 🗂️ Repository Structure

```
├── data_preparation/
│   ├── area_chart.csv          # Processed data for area chart
│   ├── beeswarm.csv            # Processed data for beeswarm plot
│   ├── data_preparation.html
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

- [GitHub Pages Site](https://tim-thorp.github.io/)
- [Area Chart (Datawrapper)](https://datawrapper.dwcdn.net/hxr40/1/)
- [Beeswarm Plot (Flourish)](https://public.flourish.studio/visualisation/20216708/)
- [Original Data Source (INE)](https://www.ine.es/jaxiT3/Tabla.htm?t=52048)