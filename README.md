# College Basketball Playstyle Clustering

This project analyzes college basketball teams by grouping them into playstyle clusters using advanced statistical metrics. It also evaluates which playstyles have historically been most successful in the NCAA Tournament and compares current teams to those profiles.

## Objective
The goal of this project is to identify different team playstyles and understand how those styles impact tournament success. By analyzing historical results, we can determine which types of teams are more likely to make deep tournament runs.

## Data
- Historical college basketball data from 2013–2024 sourced from Bart Torvik
- 2026 team data from Bart Torvik
- 
## Methods
- Selected key metrics such as shooting efficiency, turnovers, rebounding, and tempo
- Standardized features using `StandardScaler`
- Applied KMeans clustering to group teams into playstyles
- Used PCA to reduce dimensions and visualize clusters
- Analyzed tournament outcomes by cluster
- Compared 2026 teams to historical champion profiles

## Key Outputs
- Playstyle clustering map of historical teams
- 2026 teams overlaid on the playstyle map
- Cluster profile comparisons
- Tournament success rates by cluster
- Identification of teams with champion-like profiles

## Tools Used
- Python
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## How to Run
1. Download the repository files
2. Open the notebook in Jupyter
3. Make sure the data files are in the same directory as the notebook
4. Run all cells from top to bottom

## Summary
This project shows how data clustering can be used to better understand team styles and their impact on success in March Madness. It highlights how certain statistical profiles are more likely to produce championship-level teams.
