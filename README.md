# cricket-player-analysis

# Cricket Player Analysis

This project involves analyzing cricket player performance using Power BI. The analysis leverages various CSV files containing player statistics and utilizes DAX (Data Analysis Expressions) measures for in-depth insights into player performance metrics.

## Project Structure

- `Cricket_Player_Analysis.pbix`: Main Power BI file containing the analysis and visualizations.
- `data/`: Directory containing the CSV files with player statistics.
- `scripts/`: Folder containing any additional scripts used for preprocessing the data.
- `README.md`: Documentation for the project.

## Getting Started

### Prerequisites

- **Power BI Desktop**: Ensure that you have Power BI Desktop installed on your computer. You can download it from [here](https://powerbi.microsoft.com/desktop/).

### Opening the Project

1. Open **Power BI Desktop**.
2. Navigate to the project folder.
3. Open the `Cricket_Player_Analysis.pbix` file.

### Data Sources

This project utilizes the following CSV files for analysis:

- `players_stats.csv`: Contains general statistics for players.
- `matches.csv`: Information about matches played.
- `innings.csv`: Detailed innings data for each player.
- `bowling_stats.csv`: Bowling performance statistics.

### Data Preprocessing

All data preprocessing steps have been performed to clean and prepare the datasets for analysis. Key preprocessing tasks include:

- Handling missing values.
- Normalizing data formats.
- Merging datasets for comprehensive analysis.

### DAX Measures

Several custom DAX measures have been created to enhance the analysis capabilities. These measures include:

- **Total Runs**: Calculates the total runs scored by a player.
- **Average**: Computes the batting average of players.
- **Strike Rate**: Determines the strike rate of players in limited-overs matches.
- **Wickets Taken**: Computes the total wickets taken by bowlers.

### Features

- **Interactive Visualizations**: Explore various visualizations that provide insights into player performance.
- **Comparative Analysis**: Compare players based on different metrics such as runs scored, wickets taken, etc.
- **Player Statistics Dashboard**: A comprehensive dashboard that showcases key player statistics and trends.

### Troubleshooting

- Ensure that all CSV files are in the specified `data/` directory.
- If the DAX measures are not working, double-check the relationships between tables in the Power BI model.

### Contributing

Contributions are welcome! Feel free to open issues or submit pull requests. When contributing, please ensure that your code adheres to the project's standards.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to the sources of cricket statistics and any libraries or tools that aided in this project.
- Thanks to the contributors and community members who provided insights and feedback.

```

### Additional Suggestions:

1. **Add Visual Examples**: Include screenshots or examples of the Power BI dashboard to give users a visual representation of the analysis.
2. **Documentation on DAX Measures**: Consider adding explanations for each DAX measure to help users understand their purpose and how they were created.
3. **Contact Information**: Provide an email or contact method for users to reach out with questions or feedback.

This `README.md` file provides a clear overview of the project and instructions for users to get started with the Cricket Player Analysis in Power BI. Let me know if you'd like to make any changes or additions!
