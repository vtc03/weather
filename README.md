# Project Title: Seattle vs. Miami: Defining What It Means to ‘Rain More’

> A brief description of what the project does and its purpose.
Comeparing the amount of rain between Seattle and Miami
---

## Project Overview

Provide a short and concise overview of the project. Mention the problem it solves, the data used, and the key outcomes or findings.

- **Objective:** Determine which city receives more precipitation , Seattle or Miami.
- **Domain:** Climate/Environmental Science
- **Key Techniques:** Data Visualization, Statistical Testing, Descriptive Statistics

---

## Project Structure

```
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks and Python scripts
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## Data

- **Source:** Link to the data source(s)
https://raw.githubusercontent.com/brian-fischer/DATA-5100/refs/heads/main/weather/seattle_rain.csv
https://www.ncei.noaa.gov/orders/cdo/4129141.csv
- **Description:** Brief overview of the dataset features, size, and format
The dataset contains daily weather observations for Seattle and Miami from 2018 to 2023. It includes key features such as date, city, and daily precipitation (in inches). The data is stored in a tabular format. The Seattle dataset has 1658 entries and the Miami dataset has 45210 entries. 
- **License:** (if applicable)

---

## Analysis

The notebook begins by loading the weather dataset and cleaning it to ensure data quality. This includes removing all missing (NaN) precipitation values, filtering out incomplete records, and converting date fields to a proper datetime format for time-based analysis. After cleaning, the notebook calculates daily precipitation values for Seattle and Miami and then summarizes them by month to find mean monthly precipitation. It also computes the proportion of days with measurable precipitation to capture rainfall frequency. Finally, statistical tests are used to determine whether the differences in mean monthly precipitation between the two cities are statistically significant. 

---

## Results

The analysis shows that Miami receives significantly more total rainfall, especially during the summer months, while Seattle experiences lighter rain more frequently throughout the year. Statistical testing confirms that Miami’s mean monthly precipitation is higher, indicating that, by definition, Miami rains more than Seattle.

---

## Authors

- Vincent Chan - [@vtc03](https://github.com/vtc03)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Tools/libraries used: pandas, numpy, matplotlib.pyplot, seaborn
- Tutorials or papers referenced: N/A
- Inspiration or collaborators: Brian Fischer
