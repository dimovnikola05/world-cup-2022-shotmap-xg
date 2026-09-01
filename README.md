# world-cup-2022-shotmap-xg
Python shot map visualization and Expected Goals (xG) analysis for the 2022 World Cup Final using StatsBomb open data.
# World Cup Final 2022: Shot Map & Expected Goals (xG) Analysis

A professional data visualization project analyzing all shots, goals, and Expected Goals (xG) values from the 2022 FIFA World Cup Final between Argentina and France (AET).

![Shot Map](wc2022_final_shotmap_layered.png)

## Overview
This script processes event data provided by StatsBomb to evaluate team shot creation, shot location quality, and finishing efficiency over 120 minutes of play.

## Key Insights
* **High-Volume Threat:** Argentina created 20 total shots with an aggregate xG of 5.89, showcasing high-volume chance creation primarily inside the penalty box.
* **France's Efficiency:** France generated 5.41 xG across 11 shots, heavily weighted by two high-probability penalty opportunities (0.78 xG each).
* **Layered Visualization:** Shots are scaled proportionally to their xG value, featuring targeted jittering on identical coordinate penalty points to prevent overplotting.

## Tech Stack & Libraries
* **Python 3.13**
* **mplsoccer** (Pitch visualization)
* **statsbombpy** (StatsBomb Open Data API)
* **pandas** & **matplotlib**

