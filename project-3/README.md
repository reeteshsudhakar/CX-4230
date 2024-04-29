# CX-4230-Project-3
Our files for CX 4230 (Computer Simulation) Mini Project 3: NYC Bike Share, in the Spring 2024 semester with Dr. Vuduc!

## Team Members
- [Reetesh Sudhakar](mailto:rsudhakar9@gatech.edu)
- [Roshan Shreyas Desai](mailto:rdesai88@gatech.edu)

## PDF Report
Link to the PDF report: [Report](./report/report.pdf)

## Code/Repository Organization

[/data](./data) contains the project data [provided by the instructional team](https://github.gatech.edu/cx4230/citibike-data), scraped from the [Citi Bike NYC system data page](https://citibikenyc.com/system-data).

LaTeX project files can be found at [/report](./report). 

[/resources](./resources) just contains the PDF of the provided project instructions. 

[BikeShare.ipynb](./BikeShare.ipynb) contains the code for the assignment. The Jupyter notebook contains implementations broken up by task (labeled with markdown cells) and includes some notes, documentation in the form of markdown cells and code comments. There are also some initial experiments and previous simulations that we wrote, and we opted to leave them in to show the improvements made in the `BikeShareSimulation` class (see Task 1 in the notebook). 

Below is the tree structure for the report, as well as some brief notes on the file structure of this repository. 

```bash
├── BikeShare.ipynb - main notebook containing simulations
├── README.md - this file
├── data - directory containing provided data used with simulations
│   ├── raw_trips.csv
│   ├── start_station_probs.csv
│   └── trip_stats.csv
├── report - directory containing LaTeX report
│   ├── assets
│   │   ├── 3.png
│   │   └── 4.png
│   ├── main.tex - LaTeX document report
│   └── report.pdf - compiled PDF report
└── resources
    └── project-instructions.pdf
```
