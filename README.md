# Olympic Games Data Analysis

This project explores patterns and insights from historical Olympic Games data, focusing on athletes, medal distribution, countries, events, and more. The analysis is done using Python with Pandas, Seaborn, and Matplotlib.

---

## Dataset

The data comes from [Kaggle - The Olympic History Dataset](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results). It includes:
- Athlete events (`athlete_events.csv`)
- Country and region codes (`noc_regions.csv`)

---

## Content

- Unique athlete participation over the years
- Medal and Eventsdistribution by country
- Medals per event ratio (to distinguish team vs individual dominance)
- Age distribution of medal winners
- Evolution of athlete participation (Summer/Winter)

---

## Visualizations

This project includes visualizations using Seaborn and Matplotlib, such as:
- Bar plots of medal counts
- Histograms of age distributions
- Line plots for participation trends

---

## Tools Used

- Python 3.10+
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook or VS Code

---

## How to Run

1. Clone the repo
2. Create a conda environment:
   ```bash
   conda create -n olympics python=3.11
   conda activate olympics
   pip install -r requirements.txt
