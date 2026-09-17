# Hockey Player Roster Analysis

## Project Overview

This project investigates the Relative Age Effect (RAE) among Canadian hockey players.

The main question is whether players born earlier in the calendar year are more likely to reach the NHL after accounting for the seasonal birth pattern in the Canadian population.

An additional analysis examines whether birth quarter is associated with player height.

---

## Research Questions

1. Is the NHL birth-month distribution different from the Canadian population birth distribution?

2. Does the result remain after matching players with the birth distribution of their own birth year?

3. Are players born earlier in the year generally taller than players born later in the year?

---

## Data

- `nhl_player_births.csv`
- `nhl_rosters.csv`
- `canada_births_1991_2022.csv`

Canadian players only were included in the analysis.

---

## Statistical Methods

- Chi-square goodness-of-fit test
- Year-matched expected birth distribution
- Standardized residual analysis
- Chi-square trend test
- Linear regression

---

## Main Findings

- NHL birth-month distribution differs significantly from the Canadian population.

- The overrepresentation of early-born players remains after adjusting for yearly birth distributions.

- Players born earlier in the year are overrepresented in the NHL.

- Birth quarter shows only a very small association with height.

---

## Software

- R
- dplyr
- tidyr
- ggplot2
