# AFCON 2023 Final - Passing Analysis

Python project analyzing how Côte d'Ivoire moved the ball in the AFCON 2023 Final, using StatsBomb's open event data.

**Match:** Nigeria vs Côte d'Ivoire, AFCON 2023 Final (11 February 2024)

The project looks at the game from two angles: how one player (Jean Michaël Seri) distributed the ball, and how the team as a whole built up play through its passing network.

## What's Included

**Player Pass Map**: every pass Seri attempted, plotted on a pitch and split into completed and incomplete, to see his volume, accuracy and the areas he influenced most.

**Team Passing Network**: passes between Côte d'Ivoire's starting XI turned into a network, where:

* Node size shows how involved a player was in passing
* Edge thickness shows how often two players connected

## Output

**Player Pass Map** (Jean Michaël Seri, Côte d'Ivoire)

![Pass Map](images/pass_map.png)

**Team Passing Network** (Côte d'Ivoire)

![Passing Network](images/passing_network.png)

## Key Findings

* Seri completed 61 of 66 passes (about 92%), operating as a deep lying playmaker linking defence to attack
* The team's build up leaned heavily on the left side and centre, through Konan, Ndicka, Kossonou and Seri
* The strongest single passing connection was Konan to Adingra
* The right flank (Aurier, Gradel) was comparatively underused

## Project Structure

```
afcon-2023-final-passing-analysis/
│
├── pass_map.ipynb                    # Player pass map (Jean Michaël Seri)
├── passing_network.ipynb             # Team passing network (Côte d'Ivoire)
├── requirements.txt
├── README.md
│
├── images/
│   ├── pass_map.png
│   └── passing_network.png
│
└── report/
    └── Passing_Analysis_Report.pdf   # Full written report
```

## Tech Stack

Python, pandas, numpy, mplsoccer, statsbombpy, matplotlib

## Data Source

[StatsBomb Open Data](https://github.com/statsbomb/open-data), free event level football data for research and education.

## Report

Full methodology and interpretation: [Passing Analysis Report](report/Passing_Analysis_Report.pdf)

## Author

Oseko Ashpe

Football Data Analyst

LinkedIn: https://www.linkedin.com/in/ashpe-ayubu
GitHub: https://github.com/ashpe-osk
