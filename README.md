# Netflix Movies & TV Shows: Data-Driven Content Strategy Analysis

**GitHub**: github.com/mayurkarthikk/netflix-data-analysis  

## Project Overview
Analyzed Netflix's 8,807-title dataset to uncover content trends and provide actionable recommendations for content acquisition, regional investment, and release strategy—directly informing business decisions for streaming platform growth.

## Key Insights & Business Impact

**🎯 Content Strategy Optimization**
- Identified **TV-MA content as dominant** (3,207 titles, 42.7% of library) while maintaining significant family-friendly offerings (TV-PG: 863, TV-Y7: 334)
- Determined **optimal content duration**: 87–114 minute range contains 50% of titles; mean runtime 99.58 minutes aligns with peak viewer engagement
- Found **genre preferences**: International Movies (2,752) and Dramas (2,427) lead catalog, signaling opportunity for continued investment in these categories

**🌍 Geographic Expansion Guidance**
- Mapped content production: **United States leads** (2,818 titles), with **strong growth in India** (972 titles) and **United Kingdom** (419 titles)
- Identified **831 titles with missing country data**—represents opportunity for improved metadata tagging to enhance regional recommendation algorithms
- Recommended **South America market investment** despite large subscriber base, due to currently limited local content availability

**📅 Temporal & Release Strategy**
- Documented **content surge 2015–2020** (peak: 1,030 releases in 2019) correlating with Netflix's global expansion phase
- Noticed **holiday season concentration** (Nov–Dec releases) suggesting optimal timing for new content launches
- Observed **post-2020 dip** (592 releases in 2021) likely impacted by COVID-19 production delays

**👥 Talent & Content Relationships**
- Top director: **Rajiv Chilaka** (22 titles, animated/family focus)
- Top performer: **David Attenborough** (19 titles, documentary/nature content)
- **7,692 unique cast combinations** demonstrate diverse collaboration patterns valuable for content recommendation systems

## Technical Execution

**Tools**: Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook  
**Methods**: Exploratory Data Analysis (EDA), univariate/bivariate analysis, time-series trend analysis, geographic distribution analysis, missing value analysis  
**Key Techniques**: 
- datetime conversion & time-based grouping
- categorical variable encoding & frequency analysis  
- multi-value column processing (`.explode()` for genres/cast/country)
- correlation analysis between numerical attributes
- data quality assessment & missing value pattern identification

## Deliverables

- **netflix.csv**: Cleaned dataset (8,807 rows × 12 attributes) with date_added parsed as datetime
- **netflix_data_analysis.ipynb**: Complete, well-documented analysis showing code, visualizations, and insights
- **graphs.pdf**: Visualizations from the analysis (distribution plots, genre breakdowns, geographic maps, temporal trends)
- **README.md**: This file—concise overview for technical and non-technical stakeholders

## How to Run
```bash
# Clone repository
git clone https://github.com/mayurkarthikk/netflix-data-analysis.git
cd netflix-data-analysis

# Install requirements
pip install pandas numpy matplotlib seaborn

# Launch analysis
jupyter notebook netflix_data_analysis.ipynb
```

## Why This Matters for Business
This analysis transforms raw viewing data into strategic levers:
1. **Content Buying**: Focus spend on proven high-performers (International Movies, Dramas) while testing emerging genres (LGBTQ+, Comedy)
2. **Regional Strategy**: Prioritize metadata completeness in high-growth markets (India, UK) and explore underserved regions (South America)
3. **Release Planning**: Target Q4 launches and maintain 90–120 minute runtime sweet spot
4. **Recommendation Improvement**: Leverage cast/director networks and genre associations for better personalization

---

**Mayur Karthikk** | Aspiring Data Analyst  
[github.com/mayurkarthikk](https://github.com/mayurkarthikk)  
*Turning data into decisions—one insight at a time.*
