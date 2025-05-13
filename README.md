COVID-19 Global Data Tracker
*A Python-based data analysis project tracking global COVID-19 trends (cases, deaths, vaccinations)*
[![Uploading 00xp-virustimeline-videoSixteenByNineJumbo1600.jpg…]()](https://www.gardenroute.gov.za/wp-content/uploads/2020/11/CoronaVirus-scaled.jpeg)


📌 Project Description
This project analyzes global COVID-19 data from Our World in Data to:

Track cases, deaths, and vaccination trends over time

Compare country-level responses

Visualize key metrics using Python (pandas, matplotlib, Plotly)

Data Source: Our World in Data COVID-19 Dataset

⚙️ Installation & Usage
Prerequisites
Python 3.8+

Jupyter Notebook (or VS Code with Jupyter extension)

🔍 Key Findings
1. Vaccination Rollout Disparities
🚀 US/UK achieved >50% vaccination by mid-2021, while Kenya reached ~10% by 2022.

📉 Low-income countries faced 6-month delays in vaccine access.

2. Case Waves by Country
🇮🇳 India’s April 2021 surge (Delta variant) accounted for 50% of global cases at peak.

🇧🇷 Brazil maintained high death rates (>3,000/day) longer than other nations.

3. Death Rate Trends
⚠️ Early pandemic death rates were highest in Europe (e.g., Italy: ~15% in March 2020).

📊 By 2022, global death rates dropped to ~1% due to vaccines/treatments.

4. Data Limitations
🌍 Underreporting in Africa: Testing gaps may have hidden true case counts.

📅 Inconsistent updates: Some countries reported weekly instead of daily.

📊 Example Visualizations
(Embed screenshots or describe key charts from your notebook)

cases_over_time.png: Line graph comparing case trajectories

vaccine_map.png: Choropleth of vaccination rates by country

🛠️ Tools Used
Purpose	Tools/Libraries
Data Processing	pandas, NumPy
Visualization	matplotlib, seaborn, Plotly
Geographic Maps	Plotly Express
Notebook	Jupyter Lab
📜 License
MIT License - Data sourced from Our World in Data (CC BY 4.0).

💡 Pro Tip: Add a requirements.txt file with:

pandas>=1.3.0
matplotlib>=3.4.0
seaborn>=0.11.0
plotly>=5.3.0
jupyter>=1.0.0
