🏏 IPL Match Analysis

An exploratory data analysis (EDA) project on Indian Premier League (IPL) match data using Python, Pandas, and Seaborn/Matplotlib. The notebook uncovers trends in team performance, toss impact, player achievements, and venue statistics across IPL seasons.

## 📊 Overview

This project analyzes a dataset of IPL matches (`ipl.csv`) to answer key cricketing questions such as:

- Which team has won the most matches?
- Does winning the toss increase the chances of winning the match?
- Do teams prefer batting or bowling first?
- How do teams typically win — by runs or by wickets?
- Who are the top performers (Player of the Match, top scorers, best bowlers)?
- Which venues host the most matches?
- What are the record-breaking individual performances (highest score, best bowling figures, biggest win margin)?

## 🔍 Key Analyses

| # | Analysis | Description |
|---|----------|-------------|
| 1 | Dataset Overview | Shape, structure, and null-value check |
| 2 | Most Match Wins | Team with the highest number of match wins |
| 3 | Toss Decision Trends | Bat vs. field decision after winning the toss |
| 4 | Toss Winner vs. Match Winner | Percentage of matches where the toss winner also won the match |
| 5 | Win Type | Distribution of wins by runs vs. wickets |
| 6 | Player of the Match | Top 10 players with the most Player of the Match awards |
| 7 | Top Scorers | Players with the highest cumulative top-scores |
| 8 | Best Bowling Figures | Top 10 bowling performances by wickets taken |
| 9 | Venue Analysis | Venues that hosted the most matches |
| 10 | Record Performances | Highest win margin (by runs), highest individual score, and best bowling figures |

## 🛠️ Tech Stack

- **Python 3**
- **Pandas** – data manipulation and analysis
- **NumPy** – numerical operations
- **Matplotlib** – data visualization
- **Seaborn** – statistical data visualization

## 📁 Project Structure

```
├── IPL_PROJECT.ipynb   # Main Jupyter notebook with the full analysis
├── ipl.csv             # IPL match dataset (not included — add your own)
└── README.md           # Project documentation
```

## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3 installed, then install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Running the Notebook

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   cd <your-repo-name>
   ```

2. Place your `ipl.csv` dataset file in the project root directory.

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook IPL_PROJECT.ipynb
   ```

4. Run the cells sequentially to reproduce the analysis and visualizations.

## 📌 Dataset

The analysis expects a CSV file (`ipl.csv`) with columns including (but not limited to):

`match_id`, `match_winner`, `toss_winner`, `toss_decision`, `won_by`, `margin`, `player_of_the_match`, `top_scorer`, `highscore`, `best_bowling`, `best_bowling_figure`, `venue`

> **Note:** The dataset itself is not included in this repository. Add your own IPL dataset with matching column names to run the notebook.

## 📈 Sample Insights

- Identifies the most successful IPL franchise by total match wins
- Quantifies how much of an advantage winning the toss provides
- Highlights standout individual performances (highest scores and best bowling spells)
- Reveals venue popularity across IPL seasons

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](../../issues) or open a pull request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## ✍️ Author

Created as a data analysis project exploring IPL cricket statistics.

---

⭐ If you found this project useful, consider giving it a star!
