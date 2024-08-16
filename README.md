# London Transit Data Analysis for Route 10

## Table of Contents
- [Introduction](#introduction)
- [Data Source](#data-source)
- [Installation](#installation)
- [Usage](#usage)
- [Data Generation](#data-generation)
- [Simulations](#simulations)
- [Visualizations](#visualizations)
- [Results and Discussion](#results-and-discussion)
- [Future Work](#future-work)
- [Acknowledgements](#acknowledgements)
- [Requirements File](/requirements.txt)

## Introduction
This project focuses on analyzing London's Route 10 transit data to enhance operational strategies and passenger experience through advanced data analytics and AI integration.

## Data Source
- **GTFS Data**: Utilized bus inventory data for stops (including stop IDs, names, and coordinates).
- **Stop Times File**: Generated from the Google Transit folder which includes bus schedules in TXT format.
- **Trips File**: Derived from stop times and trips data, formatted specifically for weekdays.

## Installation
To set up this project, 
1. Clone the repository:
```bash
git clone https://github.com/kellytang000/Mitacs-2024-ABM.git
```
2. Navigate to the project directory:
```
cd London-Transit-ABM-(Faraz)
```
3. Install the required packages:
```
pip install -r requirements.txt
```

## Usage
Once the installation is complete, you can start exploring the data and running the code for analysis, in this sequence,
1. [Route 10 GTFS Generation](London-Transit-Route_10/code/route_10_gtfs_generation.ipynb)
2. [Route 10 OD Synthetic Generation](code/route_10_10_od_synthetic_generation.ipynb)
3. [Transit Simulation for Route 10](code/transit_sim_route_10.ipynb)
4. [Transit Visualization for Route 10](code/transit_viz_route_10.ipynb)

## Data Generation
- **Demand Data Synthesis**: Synthesized based on an annual passenger count, with rush hours identified and demand multipliers applied.
- **Real-Time Data Integration**: Used real-time stop times data to align with the synthetic OD data for accurate simulations.

## Simulations
Simulated day-to-day operations considering bus capacities (standard and articulated buses) and walking times, with detailed setup for peak and non-peak hours.

## Visualizations
Created detailed visualizations for:
- Departure plots filtered by specific stop characters.
- Bus and traveler trajectories to assess route efficiency.
- Crowdedness and occupancy analysis across Route 10.

## Results and Discussion
Discusses the implications of the filtered visualization approach and the outcomes of the applied crowd analysis techniques. Reviewed the effectiveness of the simulations in capturing the dynamics of Route 10.

## Future Work
- **AI Integration**: Plans to integrate AI to predict and adapt to real-time transit conditions.
- **Code Generalization**: Efforts to make the code adaptable for broader transit network analysis.

## Acknowledgements
Special thanks to Dr. Yili Tang and the research team at the Department of Civil Environmental Engineering, University of Western Ontario.



