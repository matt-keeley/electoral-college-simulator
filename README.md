# 2024 U.S. Presidential Election Simulator

**Tech Stack:** Python, Pandas, NumPy

## Project Overview
This project simulates the outcome of the 2024 U.S. Presidential election by combining state-level polling data with Monte Carlo noise modeling. By running thousands of iterations, it estimates the probability of each candidate winning individual states and, ultimately, the Electoral College.

The simulator provides insights into the uncertainty and variability of election outcomes, illustrating how small shifts in state-level polls can affect overall results.

## Features
- Web-scrapes polling data from multiple sources for up-to-date state-level information  
- Adds Monte Carlo noise to model polling uncertainty  
- Aggregates results across thousands of simulations to compute win probabilities  
- Visualizes state-level and nationwide election forecasts  

## Output
- Probabilities of each candidate winning each state  
- Simulated Electoral College distributions across iterations  
- Election map highlighting influence of state-level outcomes in overall result

## Requirements
- Need geometry path for map of US states, with borders
