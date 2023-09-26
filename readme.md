# World Port Index Data Visualization

## Overview
This repository contains exploratory data analysis and visualization for the World Port Index dataset, which provides detailed insights into major ports and terminals across the globe. The analysis highlights the significance of interactive geo-spatial data visualization in understanding maritime infrastructure.

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset Description](#dataset-description)
3. [Features](#features)
4. [Installation and Setup](#installation-and-setup)
5. [Usage](#usage)
6. [Acknowledgements](#acknowledgements)
7. [License](#license)

## Introduction
The maritime industry plays a pivotal role in global trade and commerce. This project aims to visualize and understand the nuances of the World Port Index dataset, highlighting the intricacies of major ports and terminals.

## Dataset Description
The dataset, commonly known as Pub 150, is sourced from the National Geospatial-Intelligence Agency (NGA). It underwent a significant revamp in 2020, incorporating traditional maritime knowledge with modern data-enhancing techniques. The dataset features:

- 3,824 unique entries representing individual ports or terminals.
- Comprehensive details across 107 columns, including both quantitative and qualitative data.

For more details on the dataset, please refer to the [data exploration notebook](./EDA.ipynb).

## Features
- Interactive geo-spatial visualization of ports with details such as harbor size and type.
- Detailed analysis of harbor characteristics, including depth, size, and facilities available.
- Reactive visualizations to understand correlations and distributions.

## Installation and Setup
1. Clone the repository:
```bash
git clone https://github.com/mohamadsolouki/Exploratory-Data-Analysis.git
cd Exploratory-Data-Analysis
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

3. Open the notebook using Jupyter:
```bash
jupyter notebook EDA.ipynb
```

## Usage
- Navigate through the notebook for detailed analysis and visualizations.
- Modify or extend the analyses as per requirements.

## Acknowledgements
Special thanks to the National Geospatial-Intelligence Agency (NGA) for providing the World Port Index dataset.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
