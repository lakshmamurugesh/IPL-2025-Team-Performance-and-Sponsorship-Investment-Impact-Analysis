# IPL 2025: Team Performance and Sponsorship Investment Impact Analysis Using Power BI

## Project Overview
The Indian Premier League (IPL) is not only a premier cricket tournament but also a high-value business ecosystem driven by sponsorships, brand investments, and fan engagement. Franchises invest significant financial resources with the expectation that higher sponsorship spending will lead to better on-field performance, stronger brand value, and improved return on investment (ROI).

This project analyzes IPL 2025 data to evaluate whether higher sponsorship investment actually guarantees better team performance. Using Power BI, multiple datasets related to team performance, player statistics, sponsorship investment, brand value, and popularity metrics are integrated into an interactive analytical solution to support data-driven decision-making in sports business analytics.

---

## Business Problem Statement
IPL teams and sponsors commit substantial financial investments with expectations of improved performance, higher rankings, and increased brand visibility. However, despite high spending, several teams fail to perform consistently across seasons.

This project addresses the following key business questions:
- Does higher sponsorship investment lead to better team performance?
- Are financially strong teams more consistent across matches?
- How much do player performance and team consistency influence outcomes compared to sponsorship spending?
- Are sponsorship investments efficiently converted into wins, rankings, and brand growth?

---

## Objectives of the Study
- Perform Exploratory Data Analysis (EDA) to understand overall IPL 2025 trends  
- Analyze team performance metrics such as wins, losses, win percentage, rankings, and playoff status  
- Evaluate player performance and its contribution to team success  
- Assess team consistency across matches using performance trends and Net Run Rate (NRR)  
- Examine sponsorship investment, sponsor categories, and brand value across teams  
- Analyze ROI by comparing sponsorship investment against performance outcomes  
- Design an efficient Power BI data model for integrated analysis  
- Present insights through interactive dashboards and visual storytelling  

---

## Dataset Description
The analysis is based on a multi-table IPL 2025 dataset designed to support both performance and financial analysis.

### Key Tables Used
- **DIM_TEAM**: Central dimension table containing team names, used to connect all fact tables  
- **Matches**: Match-level details including date, venue, teams involved, and match winner  
- **Performance**: Team-level metrics such as total matches, wins, losses, win percentage, playoff status, and Net Run Rate (NRR)  
- **Player_Performance**: Player statistics including runs, wickets, strike rate, economy rate, and key achievements  
- **Team_Sponsorship**: Sponsorship details such as sponsor name, category, duration, and investment amount  
- **Title_Sponsorship**: High-value title sponsorship information including industry category, contract duration, and value  
- **Brand_Value**: Team brand valuation data (USD millions) and brand rankings  
- **Team_Popularity**: Popularity indicators such as social media followers, Brand Strength Index (BSI), and fair play points  
- **IPL_Popularity**: League-level metrics including digital viewership, TV ratings, stadium attendance, and social media growth  

All tables are linked using team name and year, forming a relational Power BI data model.

---

## Tools & Technologies Used
- **Power BI Desktop** – Data modeling, dashboard creation, and visual analytics  
- **Power Query Editor** – Data cleaning, transformation, and preparation  
- **DAX (Data Analysis Expressions)** – Creation of KPIs and calculated measures  
- **Microsoft Excel** – Initial data validation and formatting  
- **GitHub** – Version control and project documentation  

---

## Data Cleaning & Preparation
- Standardized team names across all datasets  
- Removed duplicate and irrelevant records  
- Handled missing values in sponsorship and performance data  
- Validated and corrected data types for numerical and categorical fields  
- Created one-to-many relationships using `DIM_TEAM` as the central table  
- Developed calculated measures for:
  - Win percentage  
  - Total sponsorship investment per team  
  - Brand value comparisons  
  - Performance vs investment indicators  

---

## Data Modeling Approach
- Implemented a star-schema–like model with `DIM_TEAM` at the center  
- Connected fact tables related to performance, sponsorship, player statistics, and popularity  
- Enabled cross-filtering for seamless interaction across dashboards  
- Optimized relationships to avoid ambiguity and incorrect aggregations  

This approach ensures accuracy, scalability, and strong performance within Power BI.

---

## Dashboard Design in Power BI
The analysis is presented through multiple interactive dashboards:

### Exploratory Data Analysis (EDA)
- Overall match distribution  
- Team participation overview  
- Sponsorship distribution across teams  
- Initial trends in performance and popularity  

### Team Performance Analysis
- Wins, losses, and win percentage by team  
- Team rankings and playoff qualification  
- Comparison of top-performing and low-performing teams  

### Player Performance Analysis
- Top run scorers and wicket takers  
- Player contribution to team success  
- Identification of key match-winning players  

### Team Consistency Analysis
- Match-by-match performance trends  
- Identification of consistent and inconsistent teams  
- Relationship between consistency and final rankings  

### Sponsorship & Investment Analysis
- Sponsorship investment by team  
- Sponsor category and duration analysis  
- Brand value comparison across teams  

### ROI Analysis
- Comparison of sponsorship investment versus team performance  
- Identification of high ROI and low ROI teams  
- Evaluation of sponsorship efficiency and utilization  

---

## Key Insights & Findings
- Higher sponsorship investment does not guarantee higher win percentage  
- Some teams achieved strong performance with moderate sponsorship spending  
- Team consistency had a greater impact on success than financial investment alone  
- Individual player performance significantly influenced match outcomes  
- Certain high-investment teams delivered low ROI, indicating inefficiencies  
- Brand popularity and social media presence did not always translate into on-field success  

---

## Recommendations
- IPL teams should adopt balanced investment strategies combining financial strength with talent development  
- Sponsors should evaluate ROI and performance efficiency rather than focusing only on brand exposure  
- Teams should prioritize consistency and player analytics for sustainable success  
- Data-driven performance monitoring should be embedded into strategic planning  

---

## Conclusion
This project demonstrates that while sponsorship investment plays an important role in IPL 2025, financial strength alone does not ensure success. Teams that combined consistent performance, impactful players, and efficient investment utilization achieved better outcomes.

The project highlights the practical application of Power BI and data analytics in sports business decision-making and showcases strong skills in data modeling, dashboard development, and insight generation.

---

## Author
**Lakshma Murugesh**  
Aspiring Data Analyst  
Skills: Power BI | SQL | Excel | Data Analytics
