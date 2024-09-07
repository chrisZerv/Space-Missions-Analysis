# 🚀 Space Mission Launch Data Analysis

This project visualizes and analyzes historical space mission launch data from 1957 onward, using Python and various visualization libraries. We aim to discover trends and insights in space exploration by organizations and countries.

## 📊 Project Overview

This project uses a dataset that includes:
- 🛰️ The number of space missions per organization per year.
- 🌐 The success rate of launches over time.
- 💰 The cost of space missions.
- 📈 Trends across countries and organizations over decades.

Key features include:
- 📅 Year-on-Year charts of mission launches per organization.
- 📊 Analysis of dominant space organizations over time.
- 🔍 Visualization of failures, costs, and space race trends between countries.

## 🛠️ Setup

### Prerequisites

Make sure you have the following packages installed in your Python environment:

- pandas
- matplotlib
- seaborn
- plotly

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/space-mission-launch-analysis.git
    ```

2. Navigate to the project directory:

    ```bash
    cd space-mission-launch-analysis
    ```

3. Ensure the dataset is available in the correct path (`mission_launches.csv`).

## 🖥️ Usage

### 1. Data Cleaning and Preprocessing

Preprocessing steps include:
- 🧹 Removing missing values from critical columns like dates.
- ✨ Removing duplicates from the dataset to ensure clean data.

### 2. Number of Launches per Organization Over Time

Visualize which organization had the most launches in any given year by grouping the data by year and organization, then identifying the dominant organization for each year.

### 3. Failures Over Time

Analyze the number of failures year-on-year to understand how space missions became more reliable over time.

### 4. Space Race: USA vs USSR

Compare the number of launches between the USA and USSR (including the Russian Federation) to analyze trends during the Cold War period and beyond.

## 🏆 Results

- **Dominant Organizations**: The data reveals that organizations like **RVSN USSR** were dominant in the 1970s and 1980s, whereas **SpaceX** became dominant from 2018 to 2020.
- **Space Race Insights**: The visualizations show how the USSR dominated space launches during the Cold War, with the USA catching up in key moments.
- **Failures Analysis**: The number of mission failures decreased over time as technology improved, and space exploration became more reliable.

## 🤝 Contributing

Feel free to submit pull requests or report issues. We welcome contributions to improve this project!

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.
