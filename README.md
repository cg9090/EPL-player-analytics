# EPL Player Analytics

## Overview

This Jupyter Notebook project utilizes data from the Fantasy Premier League Website (https://fantasy.premierleague.com) to perform player analytics. The data is organised by player positions, normalised against other players in their respective positions, and used to calculate a weighted score for various attributes. The notebook ranks players based on these attributes and identifies the top 10 players in each position. The ranked data for each position is saved as JSON files in the 'Ranked_Player_Data' folder.

## Features

- Data gathering from the Fantasy Premier League website.
- Position-based data organiasation.
- Normalisation of player statistics.
- Calculation of weighted scores for key attributes.
- Ranking of players in each position.
- Identification of the top 10 players in each position.
- Saving of ranked position data as JSON files.

## Usage

1. Download the Jupyter Notebook file (`epl_player_analytics.ipynb`).

2. Open the notebook using Jupyter Notebook or JupyterLab.

3. Run each cell in the notebook sequentially.

4. View the results and rankings in the notebook output and the created files.

## Saved Position Data

The ranked data for each player position is saved as JSON files in the 'Ranked Player Data' folder. The JSON files include:
- `ranked_attacker_data.json`
- `ranked_midfielder_data.json`
- `ranked_defender_data.json`
- `ranked_goalkeeper_data.json`

## How to Contribute

Contributions to enhance this Jupyter Notebook are welcome! If you have ideas for improvement or find any issues, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE) - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Special thanks to the Fantasy Premier League for providing the data.
