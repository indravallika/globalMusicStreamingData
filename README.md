# Data Visualization and Analysis of Global Music Streaming Data

## Overview
This project analyzes global music streaming trends and listener preferences using Python. It utilizes a dataset from Kaggle and performs exploratory data analysis (EDA) to extract insights into user behavior, popular genres, and streaming trends.

## Dataset
- **Source:** Kaggle
- **File Name:** Global_Music_Streaming_Listener_Preferences.csv
- **Description:** The dataset contains information about listener demographics, preferred music genres, streaming frequency, and other relevant factors.

## Features Used
The dataset includes features such as:
- **Listener ID**: Unique identifier for each listener
- **Age Group**: Age category of the listener
- **Country**: Listener's location
- **Preferred Genre**: The genre of music most frequently listened to
- **Streaming Hours**: Total hours spent streaming music
- **Platform Used**: Streaming service preferred by the listener

## Project Structure
```
├── globalMusicStreamingData.ipynb  # Jupyter Notebook containing the analysis
├── README.md                        # Project documentation
└── data/                            # Dataset directory (not uploaded here)
```

## Dependencies
The following Python libraries are used in this project:
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Matplotlib**: Data visualization
- **Seaborn**: Statistical data visualization

## How to Use
1. Install the required libraries if you haven't already:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook globalMusicStreamingData.ipynb
   ```
3. Run each cell sequentially to load the dataset, clean the data, and visualize the insights.

## Key Insights
- Popular music genres vary across different age groups and countries.
- Certain streaming platforms dominate specific regions.
- Listener engagement (hours streamed) is influenced by demographics and genre preferences.

## Future Enhancements
- Implement machine learning models to predict user preferences.
- Add more visualizations to explore correlations between different variables.
- Extend analysis with more recent datasets.
