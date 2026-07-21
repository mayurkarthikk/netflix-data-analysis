# Netflix Movies and TV Shows Data Analysis

This project analyzes the Netflix movies and TV shows dataset to derive actionable insights for content strategy and business growth.

## Dataset

The dataset contains listings of all movies and TV shows available on Netflix, including details such as:
- Show ID
- Type (Movie/TV Show)
- Title
- Director
- Cast
- Country
- Date added
- Release year
- Rating
- Duration
- Genre (listed_in)
- Description

Source: [Netflix Movies and TV Shows dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows) (Kaggle)

## Project Structure

- `netflix.csv` - The raw dataset (8,807 rows × 12 columns)
- `netflix_data_analysis.ipynb` - Jupyter notebook containing the complete analysis
- `graphs.pdf` - Visualizations from the analysis (available in original download)

## Problem Statement

The primary aim of this analysis is to explore and derive insights from the Netflix dataset. By examining key attributes such as release year, genre, country, actors, and directors, we intend to identify trends and relationships that impact the content available on Netflix. The insights derived will guide recommendations for business decisions.

## Data Overview & Basic Metrics

**Dataset Dimensions:**
- Number of Rows: 8,807
- Number of Columns: 12
- Data Shape: 8807 × 12

**Data Types:**
- `show_id`: object
- `type`: object
- `title`: object
- `director`: object
- `cast`: object
- `country`: object
- `date_added`: datetime64 (converted for efficient analysis)
- `release_year`: int64
- `rating`: object
- `duration`: object
- `listed_in`: object
- `description`: object

**Key Statistics:**
- **Content Type:** Movies: 6,131 | TV Shows: 2,676
- **Unique Genres:** 514
- **Unique Countries:** 748
- **Null Values:** Director (2,634), Cast (825), Country (831), Date Added (10)
- **Release Year Range:** 1925 - 2021 (Mean: 2014.18)
- **Duration Range:** 3 - 312 minutes (Mean: 99.58 minutes)

## Exploratory Data Analysis Findings

### Content Distribution
- **Most Common Rating:** TV-MA (3,207 entries, 36.4%)
- **Top Genre:** International Movies (2,752), followed by Dramas (2,427)
- **Top Producing Countries:** 
  1. United States (2,818 titles)
  2. India (972 titles) 
  3. United Kingdom (419 titles)
  4. Japan (245 titles)
- **Content Over Time:** Significant increase in content releases after 2015, peaking around 2019-2020, with a noticeable dip in 2020 likely due to COVID-19 impact

### Cast & Crew Analysis
- **Top Director:** Rajiv Chilaka (22 appearances, known for animated content)
- **Top Actor:** David Attenborough (19 appearances, primarily documentaries)
- **Unique Cast Combinations:** 7,692 (indicating wide diversity of collaborations)
- **Director Attribution:** Over 30% of entries lack director information

### Duration Insights
- **Optimal Content Length:** Most content falls between 87-114 minutes
- **Average Movie Runtime:** Approximately 100 minutes
- **Duration Trend:** Newer content tends to have shorter durations

### Temporal Trends
- **Release Year Peaks:** 2019 saw 1,030 releases, 2021 had 592 releases
- **Historical Range:** Content spans from 1925 to 2021
- **Recent Growth:** Steady increase in content production since 2010

## Business Insights

### Content Trends
1. **Movies vs TV Shows:** Movies dominate (6,131) compared to TV Shows (2,676)
2. **Popular Genres:** Dramas, comedies, and international movies consistently perform well
3. **Global Expansion:** International content has risen significantly in the past five years
4. **Regional Growth:** While USA remains largest producer, India and UK show strong growth in recent years
5. **Content Strategy Shift:** Move toward contemporary content in genres like dramas and comedies

### Viewer Preferences
- **Rating Distribution:** Strong preference for mature content (TV-MA: 42.7%, TV-14: 29%, TV-PG: 11.5%)
- **Optimal Duration:** 100-120 minutes appears to be the sweet spot for engagement
- **Release Timing:** Holiday seasons (November-December) show higher content releases

### Data Quality Observations
- Significant missing data in director (30%) and country (9.4%) fields
- Cast information also has missing values (9.4%)
- Date added has minimal missing data (0.1%)

## Recommendations

### Content Strategy
1. **Focus Areas:** Produce more TV Dramas, International Dramas, and International TV Shows
2. **Emerging Opportunities:** Expand LGBTQ+ content and Comedy genres showing promise
3. **Duration Optimization:** Maintain content length between 100-120 minutes for optimal engagement
4. **Release Timing:** Target November-December releases to capture holiday viewing audiences

### Regional Investment
1. **South America Opportunity:** Limited current presence despite large market potential
2. **India & UK Growth:** Continue investing in these regions showing strong content growth
3. **Content Localization:** Develop more region-specific content for emerging markets

### Data Improvement
1. **Metadata Enhancement:** Improve director and country data completeness for better analytics
2. **Cast Tracking:** Develop better systems to track actor collaborations and audience preferences
3. **Content Tagging:** Refine genre classification system for more precise recommendations

## Technical Implementation

**Tools & Technologies:**
- Python 3.x
- Pandas for data manipulation
- NumPy for numerical operations
- Matplotlib & Seaborn for data visualization
- Jupyter Notebook for analysis and documentation

**Analysis Techniques:**
- Exploratory Data Analysis (EDA)
- Univariate and Bivariate analysis
- Missing value analysis
- Distribution analysis
- Correlation analysis
- Trend analysis over time

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/mayurkarthikk/netflix-data-analysis.git
   ```
2. Open the Jupyter notebook:
   ```bash
   jupyter notebook netflix_data_analysis.ipynb
   ```
3. Run the cells sequentially to reproduce the analysis and visualizations.

## Requirements

- Python 3.6+
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

Install dependencies with:
```bash
pip install pandas numpy matplotlib seaborn
```

## Files in Repository

- `netflix.csv` - Raw dataset (8,807 movies and TV shows)
- `netflix_data_analysis.ipynb` - Complete analysis with code and visualizations
- `README.md` - This file
- `.gitignore` - Standard ignores for Python/Jupyter projects

## License

This project is for educational and portfolio purposes. The dataset is sourced from Kaggle.

## Connect

**Mayur Karthikk**  
GitHub: [github.com/mayurkarthikk](https://github.com/mayurkarthikk)  
Portfolio Project: Netflix Data Analysis  
[View Live Repository](https://github.com/mayurkarthikk/netflix-data-analysis)

*Let's connect if you're interested in data analytics, content strategy, or business intelligence projects!*
