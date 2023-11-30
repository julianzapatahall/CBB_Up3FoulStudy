# CBB_Up3FoulStudy


## Acknowledgments

How do you create a model that can be used at the highest of competitive levels but that is so simple that any fan or college coach can understand? How do you even go about making such a simple idea statistically rigorous? The answer is with a lot of work and a lot of help. None of what you see in this repository or the attached links could be possible without any of the people below. Thank you to these great people for making this project possible:

-	Bob Walsh (college coach, St John’s University Red Storm)
-	Chris Murphy (college coach, Union College Garnet Chargers)
-	Dr. Laurie Shaw (data scientist, Manchester City)
-	Dr. Roger Hoerl (statistician, Union College)
-	Dr. Sebastian Kurtek (statistician, The Ohio State University)
-	Dr. Wayne Winston (statistician, Indiana University)
-	Ken Pomeroy (statistician, kenpom.com)
-	Kevin Weckworth (college coach, Hartford Hawks)
-	Sudarshan Gopaladesikan (data scientist, Atalanta BC)
-	163 NCAA Men’s Basketball Coaches / Anonymous Survey Responses.


## Table of Contents

- [Overview](#overview)
- [Methodology](#methodology)
- [Data Sources](#data-sources)
- [Average Win Percentage Gain](#average-win-percentage-gain)
- [Repository Structure](#repository-structure)
- [Future Applications](#future-applications)
- [Research Project License](#research-project-license)

## Overview

The **CBB_Up3FoulStudy** repository is dedicated to an in-depth analysis of the "Foul Up 3" dilemma in college basketball. This research project explores the pivotal decision of whether to foul or not when a team holds a 3-point lead, a choice that can profoundly influence game outcomes and even entire seasons. Unlike previous studies that primarily consider time as a blocking factor, this research seeks to create a coachable strategy that outlines the optimal fouling decision for each specific moment in time. I divided the final 21 seconds of a game into 34 time cells when performing analyses. 

## Methodology

To arrive at these conclusions, I calculated overtime-adjusted win percentages for two possible fouling decisions: commit a foul and avoid fouling, for each time cell. The fouling decision with the highest overtime-adjusted win percentage became the recommended strategy.

## Data Sources

The research drew from the following sources:

- **Coach Surveys**: More than 3,100 surveys were sent to men's college basketball coaches to gain insights into their fouling considerations. The data from this survey is available in this repository, but any identifying information has been removed to ensure the anonymity of the coaches whom responded.
- **Play-by-play Data**: Data from the 2010 to 2022 seasons of NCAA Division 1 Men's Basketball were collected from the NCAA website to inform the study.

## Average Overtime-Adjusted Win Percentage Gain

To measure the impact of my recommended strategy, I calculated the overtime-adjusted win percentage point gain from following my recommended decision in each cell. For each cell, I subtracted the average overtime-adjusted win percentage across both decisions from the overtime-adjusted win percentage of my recommended decision. By averaging gain across cells, I find that if a coach follows my recommended decision in each cell, he or she gains 1.63 overtime-adjusted win percentage points on average. 

## Repository Structure

For those interested in delving into the details of the analysis, all the code and comprehensive instructions related to data collection, analysis, and findings have been meticulously documented in this GitHub repository to ensure reproducibility. This includes the addition of a special empty folder for the purpose of storing reproduced calculation results as the user advances through the notebook calculations.

## Future Applications

This research not only provides actionable fouling strategies for all NCAA coaching staffs but also introduces innovative methodology that can be adapted to generate an NBA fouling strategy. Furthermore, it can be extended to address strategic problems in other sports, such as the fourth-down and two-point conversion dilemmas in the NFL, thereby enhancing strategy in multiple sports.

## Research Project License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

*Note: While the findings presented in this repository are specific to NCAA Men's Basketball as of the study period, the methodology can be applied and extended to other sports and leagues.*