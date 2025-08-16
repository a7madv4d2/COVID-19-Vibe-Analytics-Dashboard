# COVID-19 Vaccination Analytics Dashboard with Vibe Analytics

![Cumulative Vaccination Progress](images/cumulative-progress.png)

## 📖 Overview
This project builds upon my [COVID-19 Vaccination Data Analysis](https://github.com/a7madv4d2/COVID-19-Vaccination-Progress) by developing an advanced interactive dashboard using **Vibe Analytics** integrated with **Plotly**. It provides in-depth visualizations of global COVID-19 vaccination trends, inequalities, progress metrics, and more, drawing from datasets like Our World in Data. The dashboard enables users to explore cumulative progress, distribution disparities, rollout speeds, and vaccine efficiencies through dynamic charts, maps, and heatmaps.

Due to a known bug in Plotly Studio preventing full app publication, this repository showcases the dashboard via high-quality screenshots. These capture the interactive elements, such as filters, hover details, and range selectors, to demonstrate functionality.

## 🎯 Objectives
- Visualize global vaccination rollout trends, including cumulative doses, daily paces, and geographic coverage.
- Highlight inequalities in vaccine distribution using metrics like Gini coefficients and Lorenz curves.
- Analyze efficiency factors, such as dose conversion rates and time to threshold achievements.
- Examine vaccine portfolio popularity, peak timing, and immunity gaps across countries.
- Provide actionable insights for public health stakeholders on disparities and progress bands over time.

## 🛠️ Key Achievements
- **Data Processing**: Preprocessed extensive vaccination datasets using Python (Pandas, NumPy), aggregating metrics like fully vaccinated percentages, daily doses per million, and cohort progress.
- **Visualizations**: Created over 15 interactive charts, including line charts, box plots, choropleth maps, Lorenz curves, bar charts, heatmaps, scatter plots, stacked areas, lollipop charts, and treemaps.
- **Insights Derived**:
  - Global cumulative vaccinations reached over 30B for at least one dose by early 2022, with fully vaccinated lagging at around 20B.
  - Median fully vaccinated rate across countries is approximately 60%, with significant outliers in distribution.
  - Fastest countries to 50% fully vaccinated (e.g., Bhutan, Nauru) achieved it in under 25 days.
  - Gini coefficient for vaccination inequality peaked around 0.8 in March 2022, indicating high disparities.
  - Top conversion rates (doses to fully vaccinated) in countries like Ireland (>90%), while bottom performers like Mauritania (<20%).
  - Popular vaccine combinations include Johnson & Johnson + Moderna + Oxford/AstraZeneca, used in 15+ countries.
  - Peak global daily vaccinations averaged ~400k (7-day rolling) in mid-2021, with seasonal patterns visible in heatmaps.
  - Top 20 countries by fully vaccinated % include Pitcairn (100%) and UAE (~99%).
  - Immunity gaps show many countries with high first-dose rates but lower full vaccination, clustered near the diagonal line.
  - Cohort analysis reveals faster progress in early starters (e.g., Jan 2021 cohorts reaching 80% median).
  - Progress bands shifted over time, with most countries moving to 60-80% bands by 2022.
  - Country-specific trends, e.g., Norway's daily per million peaked at ~8k, vs. Russia's lower pace.
- **Tools Used**: Vibe Analytics for dashboarding, Plotly for interactive visuals, Python for data wrangling.

## 📂 Repository Structure
- `src/`: Python scripts for data preprocessing, aggregation, and Plotly figure generation.
- `images/`: Screenshots of dashboard visualizations (e.g., cumulative-progress.png, distribution-boxplot.png).
- `data/`: Sample vaccination dataset excerpts or schemas (CSV format, sourced from Our World in Data).

## 📬 Contact
I'm Ahmed Elsayed, an IBM-certified Data Analyst specializing in healthcare data visualization. Open to feedback, collaborations, or data science opportunities!  
📧 [a7madv4d2@gmail.com](mailto:a7madv4d2@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/your-linkedin-username) | [GitHub Profile](https://github.com/a7madv4d2)  

⭐ Star this repo if you find it useful!

## 🏷️ Topics
#data-analysis #data-visualization #covid-19 #plotly #vibe-analytics #healthcare-analytics #python #public-health #vaccination-trends
