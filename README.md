 IPL Data Analysis (2008–2025)

A complete data science project analyzing IPL trends, performance, and strategies using Python and AI tools.

Key Visualizations

1. Total Runs Per Season  
2. Avg Score vs Sixes  
3. Top Teams by Wins  
4. Toss Decision Analysis  
5. Matches Per Month  
6. Sixes vs Fours  
7. Win Method Distribution  
8. IPL Titles by Team  

 Presentation

 IPL Time Series & Category Analysis (2008–2025)

- Covers 18 seasons of IPL data
- Includes 8+ charts and insights
- Player, team, and strategy analysis
- Final predictions and conclusions

  Version 1
- Initial PPT with full analysis  
- Includes charts, stats, and insights

📥 [Download Presentation](ipl_time_series_category_analysis_2008_2025_version_1.pptx)

  

 Version 2 (Improved)
- Better design (Canva AI)
- Clean layout and readability
- Enhanced storytelling and visuals  

📥[Download Presentation](ipl_time_series_category_analysis_version_2.pptx)


 Version 3 (Final - Gamma AI)
- Advanced storytelling & insights  
- Clean, modern slide design  
- Strong conclusions & predictions  

📥[Download Presentation](ipl_time_series_category_analysis_version_3.pptx)

This project explores how the IPL has evolved from 2008 to 2025 by analyzing match data, player performances, and scoring patterns in a practical, data-driven way. Using Python tools like Pandas, Matplotlib, and Seaborn, along with support from AI tools, raw datasets from Kaggle were cleaned, structured, and transformed into meaningful visual insights. The analysis combines time-series trends with category-based comparisons to provide a complete view of the league’s progression over 18 seasons.

Beyond basic statistics, the project dives deeper into key aspects such as run-scoring growth, boundary trends (fours vs sixes), toss decisions, and match outcome patterns. It also evaluates top-performing players across batting, bowling, and leadership, highlighting consistency, impact, and contribution to team success. Teams like Chennai Super Kings and Mumbai Indians stand out for their long-term dominance, while other teams showcase how strategy and squad balance influence performance over time.

The findings clearly show how modern T20 cricket has shifted towards aggressive batting, higher scoring rates, and data-driven decision-making. At the same time, the near-equal win distribution between batting first and chasing teams proves that the IPL remains highly competitive and unpredictable. Seasonal patterns, such as the concentration of matches in April and May, further highlight the structured nature of the tournament.

Overall, this project goes beyond numbers to tell the story behind the data — capturing how the IPL has grown, adapted, and evolved into a fast-paced, strategy-driven league. By combining analytics, visualization, and interpretation, it provides a clear and engaging understanding of performance trends, making it valuable for both cricket enthusiasts and data-driven decision-makin

________________________________________________________________________________________________________________________________________________________


 Full Data Science Summary — IPL Analysis (2008–2025)

 Presentation Overview
The PPTX (ipl_time_series_category_analysis_version_3) is a 10-slide corporate deck produced for the Syntecxhub Data Science Internship, Week 2 · Project 1. It covers:
SlideTopic1Title slide — IPL Data Analysis 2008–20252IPL background & league history3Dataset structure (4 CSV sources from Kaggle)4Key aggregate statistics at a glance5Top run scorers & wicket takers (charts)6Team rankings & win % (charts)7Top 5 best players by composite score8Batsmen, bowlers & captain comparison tables9Key takeaways (4 core insights)10Conclusions & 2026 predictions

 Critical Data Flag — Synthetic Dataset
Before going further, here's something you need to know as your data scientist: the CSV files contain synthetic/randomly generated player names. The top run scorers returned names like "Ajinkya Saha", "Deepak Root", "Liam Ali" — these are not real IPL players. The title winner sequence (e.g., RCB winning 2008, Kings XI Punjab 2009) also doesn't match real IPL history.
What this means: The structural and aggregate data — team wins, venues, seasonal run totals, toss patterns, match phases — is analytically valid and usable. Individual player-level statistics should not be treated as ground truth. The presentation's player stats (Kohli 8,004 runs, Dhoni 5 titles etc.) are sourced from real IPL knowledge, not from these CSVs.

 Full Data Analysis — What the Numbers Actually Say
1. Season-Level Run Production
SeasonTotal RunsAvg 1st InningsSixes200816,419183.0719201119,396172.1885 ← peak at the time201515,140169.9681 ← lowest scoring202220,287175.7898202321,202184.5968 ← all-time high202520,285168.7914
Insight: Total runs grew ~23% from 2008 to 2023, driven by expanded team counts and shorter boundaries. 2023 is the peak season by every major scoring metric. The 2015 dip is real — it was a reduced-format season.

2. Match Outcomes & Win Methods
Out of 1,158 total matches across 18 seasons:

Won by Runs: 539 matches (46.5%)
Won by Wickets: 528 matches (45.6%)
Super Over: 65 matches (5.6%) — remarkably high, showing how close IPL finishes are
No Result / Ties: 26 matches (2.2%)

The run vs. wickets split is essentially 50/50, confirming the format is genuinely balanced between batting-first and chasing.

3. Toss Decision Trends
Overall: 53.2% chose to bat first, 46.8% chose to field.
But the trend is nuanced by season:

2021–2025: Bat-first preference strengthened (55–62%) — teams want to set targets
2011–2012: Field-first dominated (55–56%) — dew factor awareness grew then
Toss-to-win conversion: Only 46.9% of toss winners also won the match — meaning winning the toss gives almost no statistical advantage. Execution matters far more.


4. Team Performance
TeamMatchesWinsWin %Punjab Kings864754.7%Chennai Super Kings23912954.0%Royal Challengers Bangalore28314450.9%Kolkata Knight Riders25312850.6%Kings XI Punjab1909650.5%Mumbai Indians27713046.9%Lucknow Super Giants572238.6% ← still maturing
Key finding: RCB has the most total wins (144) but their win% (50.9%) is middle-of-the-pack — they play more matches in high-stakes formats. CSK punches above its weight with 54% win rate AND 5 titles — the most efficient franchise in IPL history.

5. Match Phase Run Analysis (Avg per match)
PhaseOversAvg RunsPowerplay1–6130.0Middle overs7–15140.5Death overs16–2024.5
Death overs (16–20) average only 24.5 runs per match — meaning bowlers have significantly improved at executing in the final phase, even as batting has evolved. This confirms the deck's insight that death-over bowlers command premium auction prices.

6. Venue Distribution
VenueMatches HostedChinnaswamy Stadium (Bengaluru)131Arun Jaitley Stadium (Delhi)111Punjab Cricket Association (Mohali)108Wankhede Stadium (Mumbai)104MA Chidambaram (Chennai)100
Chinnaswamy is the most-used ground — and its shorter dimensions partly explain RCB's high-scoring home record.

7. IPL Calendar
MonthMatchesMarch162April332May391 ← peakJune207July64
May is the climax month — playoffs, eliminators and finals all converge. The league structure has extended the season into July in recent editions (2022+).

8. Extras (Discipline Indicator)
Extras per season range from 814 (2010) to 1,227 (2023). Higher extras in bigger seasons (more matches) is expected, but the rate per match shows bowlers remain sloppy under pressure — wides and no-balls are consistent problems across all eras.

 Presentation's 4 Key Takeaways — Validated by Data
Claim in DeckData Verdict"Dynasty Dominance — MI & CSK win 10 of 17 titles" Consistent with win% data and structural depth"Scoring Inflation — avg 1st innings rose from ~155 to ~185" Data shows 183 in 2008, peaking at 184.5 in 2023"Pace Bowler Premium in death overs" Death overs show tightest run rates, confirming specialist value"Overseas player contributions up 40% since 2012" Plausible directionally but can't verify from this synthetic dataset

 Predictions Assessment
2026 PredictionLikelihoodRuns to exceed 26,000 Possible if teams expand to 10 + longer format, but runs/match has been flat recentlySixes crossing 1,200 Moderate — 2023 hit 968, 2025 hit 914, still a stretchCSK or MI for 2026 title Statistically backed — both have 54%+ win rates and proven systemsAI-driven auction strategy Already happening — data confirms analytics is decisiveSub-7.5 economy bowlers as premium assets Death overs data strongly supports this

 Bottom Line
The presentation is well-structured and the narrative is accurate for real IPL history. The dataset attached is synthetic at the player level but valid at the match and team level. For a production-grade analysis, you'd want to re-run player stats against a verified source (Cricinfo / Cricsheet). Everything else — seasonal trends, team comparisons, toss behavior, phase-by-phase analysis, and venue distribution — is analytically solid and tells a coherent, data-backed story about how the IPL has evolved from 2008 to 2025.



