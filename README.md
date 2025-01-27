# Cancer-Growth-Simulation

This project simulates the growth and spread of cancerous cells in a tissue using Python. The simulation visualizes the process and provides insights into how cancerous cells grow and spread over time.

# Features
Simulates cancer cell growth and spread in a circular tissue.
Visualizes cell states over time (Healthy vs Cancerous).
Tracks the number of healthy and cancerous cells at each time step.

# Setup
Install the required dependencies using:
     pip install -r requirements.txt
     
Run the script with:
     python cancer_growth.py

# How It Works
Initialization:
   The tissue is represented as a circular area containing cells. Some cells are randomly set as cancerous at the start.
Simulation:
    Cancerous cells can spread to healthy neighbors within a certain radius, with a probability of spread.
Visualization:
    Healthy cells are displayed in green.
    Cancerous cells are displayed in red.
    A time-series graph shows how the number of healthy and cancerous cells changes over time.
