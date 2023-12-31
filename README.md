<p align="center">
    <a href=""><img src="https://img.shields.io/pypi/l/ansicolortags.svg" /></a>
    <a href=""><img src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" /></a>
    <a href=""><img src="https://badgen.net/github/commits/jonrosenblum/NFL-Analytics-Dashboard" /></a>
    <br>
    <a href="https://docs.python.org/3/index.html"><img src="https://img.shields.io/badge/python-%2320232a?style=for-the-badge&logo=python&logoColor=ffdd54" /></a>
    <a href="https://dash-bootstrap-components.opensource.faculty.ai/"><img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" /></a>
    <a href="https://plotly.com/dash/"><img src="https://img.shields.io/badge/dash-008DE4?style=for-the-badge&logo=dash&logoColor=white" /></a>
    <br>
    <a href=""><img src="https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter" /></a>

</p>
...
<h1 align="center"><b>NFL Statistics Dashboard</b></h1>
<h4 align="center">A web application built using Dash and Plotly for visualizing NFL player statistics. This dashboard allows users to explore passing, rushing, and receiving statistics for quarterbacks, running backs, and wide receivers. </h4>

<p align="center">
    <img src="./assets/projectbanner.png" alt="Project Banner" width=60% height=60%/>
</p>

## Table of Contents

- [Introduction](#introduction)
- [Technical Requirements](#technical-requirements)
- [Project Structure](#project-structure)
- [Key Functionalities](#key-functionalities)
- [Project Features](#project-features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The NFL Player Statistics Dashboard provides an interactive way to visualize player statistics from 2019 to 2022 for different positions: quarterbacks (QB), running backs (RB), and wide receivers (WR). Users can select specific players and view various statistics, including passing yards, touchdowns, interceptions, rushing yards, rush touchdowns, rushing attempts, receiving yards, receptions, and receiving touchdowns.

## Technical Requirements

To run the NFL Player Statistics Dashboard locally, you need the following:

- Python 3.7 or later
- Dash 1.21.0 or later
- Plotly 5.0.0 or later
- Pandas 1.1.0 or later

## Project Directory Hierarchy

Upon successful setup (see **Getting Started**), you should see the following project directory hierarchy.

```
nfl-player-stats-dashboard/
├── classes/
├── data/
│ └── nfl_offensive_stats.csv
├── notebooks/
│ └── .ipynb_checkpoints/
│ │     └── .eda-checkpoints.ipynb
│ └── nfl-investigative_analysis.ipynb
├── app.py
├── OBJECTIVES.md
├── Pipfile
└── README.md
```

- `classes/`: Directory containing OOP Objectives
- `data/`: Directory containing the dataset `nfl_offensive_stats.csv`.
- `app.py`: Main application file containing the Dash app code and callbacks.
- `OBJECTIVES.md`: Project documentation for future objectives and functionality
- `Pipfile` and `Pipfile.lock`: Files specifying project dependencies when using `pipenv`.
- `README.md`: Project documentation providing an overview, setup instructions, and other details.

## Key Functionalities

The NFL Player Statistics Dashboard offers the following functionalities:

- Choose a player's position: quarterbacks, running backs, or wide receivers.
- Select a specific player from the dropdown menu.
- Choose from various statistics for the selected player using radio items.
- View bar graphs illustrating the selected player's statistics over different game IDs.
- Compare player statistics and visualizations.

## Project Features

- ~~[Create tabs for each player position and display a dropdown to select a player from the chosen position.](./OBJECTIVES.md#objective-position-specific-tabs)~~
- ~~[Enable users to export selected data and visualizations for further analysis or sharing.](./OBJECTIVES.md#objective-export-sharing-tabs)~~
- [Implement dropdown menus or input fields to filter data by season, team, or player attributes.](./OBJECTIVES.md#interactive-data-filters-tabs)
- [Present the NFL game schedule week by week](./OBJECTIVES.md#weekly-schedule-tabs)
- [Advanced Project Objectives](./OBJECTIVES.md#advanced-tabs)

## Getting Started

1. Clone this repository to your local machine:

```bash
git clone https://github.com/jonrosenblum/nfl-player-stats-dashboard.git
```

2. Navigate to the project directory:

```bash
cd nfl-player-stats-dashboard
```

3. Install the required dependencies using pipenv:

```bash
pipenv install
```

4. Run the Dash app:

```bash
pipenv run python app.py
```

## Usage

1. Choose a position (Quarterbacks, Running Backs, or Wide Receivers) from the tabs.
2. Select a player from the dropdown menu.
3. Use the radio items to choose the desired statistic.
4. Observe the corresponding bar graph showing the player's statistics.

## Dependencies

The NFL Player Statistics Dashboard relies on the following libraries:

- Dash: A web application framework for building interactive web applications with Python.
- Plotly: A graphing library for creating interactive, publication-quality graphs.
- Pandas: A data manipulation library for data analysis and manipulation.

## Contributing

Contributions to the NFL Player Statistics Dashboard are welcome! If you encounter any issues, have feature suggestions, or would like to contribute code, please open an issue or pull request on the GitHub repository.

## License

MIT License

Copyright (c) 2023 Jon Rosenblum

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
