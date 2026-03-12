# NBA Shot Analytics & The 3-Point Revolution

A data analysis project built with Python that explores NBA shooting data. This repository features an interactive tool to analyze individual player shot statistics and a comprehensive Jupyter Notebook detailing the historical evolution of the 3-point shot in the league, using mainly Pandas, Matplotlib, Numpy

## Features

* **Automated Data Gathering:** A dedicated script (`datadownload.py`) to easily fetch and prepare the NBA shot dataset.
* **Player Shot Profiler:** An interactive menu-driven script (`main.py`) to explore specific players. You can analyze their shot locations, efficiency, and filter their shooting performance by specific seasons.
* **The 3-Point Evolution Study:** A Jupyter Notebook that takes a deep dive into the "Analytics Era" of basketball, analyzing how the volume and average distance of 3-point shots have changed over the years.

## How to Use
After cloning the repo and having activated an environment with the dependencies in requirements.txt

### Download the Data
Before running the analysis, you need to download the dataset. Run the data downloader script "datadownload.py"
This will fetch the raw shot data and save it in the project directory, ready to be processed.

### Analyze Individual Players
To use the interactive player menu, run the main script "main.py"
Follow the on-screen prompts to search for a player, select a season, and visualize their shot charts and statistics.

### Explore the 3-Point Evolution
To view the historical analysis of the 3-point shot, launch the Jupyter Notebook file "3ptevolution.ipynb"
