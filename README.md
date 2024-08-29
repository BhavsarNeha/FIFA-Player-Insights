# FIFA Data Analysis

## Overview
This project involves analyzing FIFA player data using Python and visualizing various aspects such as skill distribution, preferred foot, weight distribution, and a comparison of overall ratings among professional soccer teams.

## Project Structure
- **`fifa_data.csv`**: The dataset containing detailed information about FIFA players.
- **`fifa_analysis.ipynb`**: The Jupyter Notebook containing all the analysis and visualizations.
- **`README.md`**: This file, providing an overview of the project.

## Analysis Breakdown
1. **Skill Level Distribution**:
   - A histogram that shows the distribution of player skill levels.
   - Uses `Overall` ratings to categorize players into bins ranging from 0 to 100.

2. **Foot Preference**:
   - A pie chart depicting the distribution of players' preferred foot (Left or Right).
   - Highlights the percentage of players who are left-footed versus right-footed.

3. **Weight Distribution**:
   - A pie chart that classifies players into different weight categories.
   - The categories include under 125 lbs, 125-150 lbs, 150-175 lbs, 175-200 lbs, and over 200 lbs.

4. **Team Comparison**:
   - A box plot comparing the overall ratings of players from three soccer teams: FC Barcelona, Real Madrid, and New England Revolution.
   - The plot highlights the distribution of ratings within each team.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/fifa-data-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd fifa-data-analysis
   ```
3. Install the necessary packages:
   ```bash
   pip install pandas numpy matplotlib
   ```
4. Open the Jupyter Notebook and run the cells:
   ```bash
   jupyter notebook fifa_analysis.ipynb
   ```

## Dependencies
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Matplotlib**: For creating static, animated, and interactive visualizations in Python.

## Conclusion
This project provides insights into the FIFA player data through various visualizations. It serves as a useful tool for anyone interested in exploring player statistics and comparing team performances.

