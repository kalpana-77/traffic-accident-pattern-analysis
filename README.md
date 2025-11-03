text
# Traffic Accident Pattern Analysis

Analyze and visualize the US Traffic Accidents dataset to discover insights about accidents in relation to time, weather, and road conditions. This project uses Python (pandas, matplotlib, seaborn, folium) to reveal trends, draw comparisons, and display accident hotspots on a map.

## Dataset

- **Source**: [US Accidents (2016 - 2023) Kaggle Dataset](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)  
- **File Used**: `US_Accidents_March23.csv`
- Contains >7 million traffic accident records with information on location, time, severity, weather, and more.

## Project Structure

traffic-accident-pattern-analysis/
├── US_Accidents_March23.csv
├── skill.4.py
├── accident_hotspots.html
├── README.md

text

## How to Run

1. Clone/download this repository.  
2. Download `US_Accidents_March23.csv` from Kaggle and place it in the project folder.
3. Make sure you have Python 3.7+.
4. Install required packages:
pip install pandas matplotlib seaborn folium

text
5. Run the script:
python skill.4.py

text
or in Jupyter Notebook for step-by-step output.

6. Check the data visualizations (charts will pop up) and view the generated `accident_hotspots.html` map in your browser.

## Features

- Cleans and parses accident data.
- Plots accident distribution by hour of day, weather condition, and severity.
- Explores accident severity relative to major weather types.
- Creates an interactive map of accident hotspots.

## Example Insights

- Peak accident times occur during morning and evening commute hours.
- Certain weather conditions (like Rain, Snow, Fog) correlate with more severe accidents.
- Accident hotspots are identifiable in urban clusters.

## License

This project is released under the MIT License.

## Acknowledgements

Based on the publicly available US Accidents dataset from Kaggle.

