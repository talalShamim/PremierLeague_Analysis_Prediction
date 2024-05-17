# PremierLeague_Analysis_Prediction

## Project Structure
- **PremierLeague_Analysis_Prediction.ipynb**: Jupyter notebook containing all the steps from web scraping to machine learning prediction.
- **All matches data.csv**: CSV file containing the scraped and processed EPL data.

## Data Description
The dataset includes the following features:
- `Date`: Match date
- `Time`: Match time
- `Day`: Match day
- `Venue`: Match venue
- `Result`: Match result
- `Opponent`: Opposing team
- `xG`: Expected goals
- `xGA`: Expected goals against
- `Poss`: Possession percentage
- `Attendance`: Number of attendees
- `Captain`: Team captain
- `Formation`: Team formation
- `Total shots`: Number of total shots
- `Shots on target`: Number of shots on target
- `Distance of shots`: Average distance of shots
- `Freekicks`: Number of free kicks
- `Penalties`: Number of penalties

## Installation
To run the notebook, you need to install the required Python libraries. You can do this by running:
```bash
beautifulsoup4==4.9.3
pandas==1.2.3
jupyter==1.0.0
requests==2.25.1
