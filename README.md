# Healthcare Data Visualization

## Description
Healthcare data is examined with patient health data like blood pressure, sugar level, and weight through plots and visualization. Trends and patterns that improve medical decision and patient care are sought.

## Features
- **Blood Pressure Distribution**: Histogram plot used to examine how the blood pressure levels are distributed.
- **Time Variations of Sugar Levels**: Line graph to represent trends of change in sugar level for various months.
- **Distribution of Weight**: Boxplot to represent weight variation of patients.

## Technologies Used
- **Python**: Data processing and analysis
- **Pandas**: Handling data and structuring data
- **Matplotlib & Seaborn**: Data visualization

## Installation
To execute this project locally, first ensure you have Python installed, then install the dependencies:
```sh
pip install numpy pandas matplotlib seaborn
```

## Usage
Execute the Python script to produce healthcare insights:
```sh
python healthcare_data_exploration.py
```
The script will produce three visualizations of patient health trends.

## Data Generation
The data frame holds randomly created patient records:
- **Date**: Random patient visit dates.
- **Patient_ID**: Unique patient IDs.
- **Blood Pressure**: Random integers in the range 90-180 mmHg.
- **Sugar Level**: Random float values in the range 70-200.
- **Weight**: Random float values in the range 50-120 kg.

## Output
The script generates the following plots:
1. **Histogram of Blood Pressure** - The histogram illustrates the distribution of the blood pressure readings.
2. **Average Sugar Level Trends for Each Month** - Plots average sugar levels by month.
3. **Weight Distribution Boxplot** - Shows weight differences between patients.

## Future Improvements
- Use real-world healthcare data.
- Add other health parameters (e.g., cholesterol, heart rate).
- Create an interactive dashboard for real-time analysis.

## References
- [Pandas Documentation](https://pandas.pydata.org/docs/index.html)
- [Seaborn Library](https://seaborn.pydata.org/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
