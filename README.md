# CBB_Up3FoulStudy


## Acknowledgments

How do you create a model that can be used at the highest of competitive levels but that is so simple that any fan or college coach can understand? How do you even go about making such a simple idea statistically rigorous? The answer is with a lot of work and a lot of help. None of what you see in this repository or the attached links could be possible without any of the people below. Thank you to these great people for making this project possible:

- Bob Walsh (college coach, St John’s Red Storm)
- Chris Murphy (college coach, Union College Garnet Chargers)
- Dr. Roger Hoerl (statistician, Union College)
- Dr. Sebastian Kurtek (statistician, The Ohio State University)
- Dr. Wayne Winston (statistician, Indiana University)
- Ken Pomeroy (statistician, kenpom.com)
- Kevin Weckworth (college coach, Hartford Hawks)
- Matthew Droney (college coach, Babson Beavers)
- Patrick Doherty (college coach, Haverford Fords)
- Phil Martelli Jr. (college coach, Bryant Bulldogs)
- Steve Merfeld (college coach, Creighton Bluejays)

## Table of Contents

- [Overview](#overview)
- [Key Findings](#key-findings)
- [Methodology](#methodology)
- [Data Sources](#data-sources)
- [Average Win Percentage Gain](#average-win-percentage-gain)
- [Repository Structure](#repository-structure)
- [Future Applications](#future-applications)
- [Research Project License](#research-project-license)
- [Image License](#image-licence)


## Overview

The **CBB_Up3FoulStudy** repository is dedicated to an in-depth analysis of the "Foul Up 3" dilemma in college basketball. This research project explores the pivotal decision of whether to foul or not when a team holds a 3-point lead, a choice that can profoundly influence game outcomes and even entire seasons. Unlike previous studies that primarily consider time as a blocking factor, this research seeks to create a coachable strategy that outlines the optimal fouling decision for each specific moment in time.

## Key Findings

This research project has unveiled two pivotal findings:

1. **Regular Fouling Unsupported**: When leading by 3 points, the leading team should generally avoid fouling unless there's an opportunity to perform an additional lane violation. This challenges conventional wisdom regarding late-game fouling decisions.

2. **Lane Violation Approach**: The additional lane violation approach is only beneficial if employed by the team with the possession arrow in their favor. The recommended fouling approach for a team up by 3 is as follows:
   - If the possession arrow points toward the trailing team, the leading team should avoid fouling.
   - If the possession arrow points toward the leading team, they should only foul and perform a lane violation with 5 to 8 seconds remaining on the game clock and at most a 2-second difference between the shot clock and game clock.

## Methodology

To arrive at these conclusions, the analysis used a frequentist approach. It calculated win percentages for three possible fouling decisions: regular foul, regular foul with a lane violation, and no foul, for each time interval. A minimum threshold of 50 fouls committed in a given interval was required to conduct statistical analysis. In intervals with substantial sample sizes, the fouling decision with the highest win percentage became the recommended strategy. For intervals with smaller sample sizes, recommendations were influenced by coach survey responses and based on a blend of statistical viability and coachability.

## Data Sources

The research drew from the following sources:

- **Coach Surveys**: More than 3,100 surveys were sent to men's college basketball coaches to gain insights into their fouling considerations. The data from this survey is available in this repository, but any identifying information has been removed to ensure the anonymity of the coaches whom responded.
- **Play-by-play Data**: Data from the 2010 to 2022 seasons of NCAA Division 1 Men's Basketball were collected from the NCAA website to inform the study.

## Average Win Percentage Gain

The research found that the average win percentage gain associated with using the recommended approach assigned to each interval is 2.1%. This suggests that implementing the proposed strategy could significantly impact a team's chances of winning.

## Repository Structure

For those interested in delving into the details of the analysis, all the code and comprehensive instructions related to data collection, analysis, and findings have been meticulously documented in this GitHub repository to ensure reproducibility. This includes the addition of a special empty folder for the purpose of storing reproduced calculation results as the user advances through the notebook calculations.

## Future Applications

This research not only provides actionable fouling strategies for all NCAA coaching staffs but also introduces innovative methodology that can be adapted to generate an NBA fouling strategy. Furthermore, it can be extended to address strategic problems in other sports, such as the fourth-down and two-point conversion dilemmas in the NFL, thereby enhancing strategy in multiple sports.

## Research Project License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Image Licence

Adam Sonnett, Marcus Johnson foul line, CC BY-SA 2.0

---

*Note: While the findings presented in this repository are specific to NCAA Men's Basketball as of the study period, the methodology can be applied and extended to other sports and leagues.*