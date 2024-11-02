# GitHub Users in Dublin

This repository contains data about GitHub users in Delhi with over 50 followers and their repositories.

## Files

1. `users.csv`: Contains information about 477 GitHub users in Delhi with over 50 followers
2. `repositories.csv`: Contains information about 12185 public repositories from these users
3. `gitscrap.py`: Python script used to collect this data

## Code

For the code, check out the following : [TDS - Project 1 - Google Colab](https://colab.research.google.com/drive/1CUb_mXURG3pt5ETaOvlLfyCGPENwPfu0?usp=sharing).
This code notebook contains code solutions for select questions, primarily focused on data extraction, followed by solutions to questions 1, 4, 7, 8, 9, 10, 13, 14, and 16. 
The remaining questions were addressed using pivot tables or resulted in `NaN` outputs in the code.

## Data Collection

- Data collected using GitHub API
- Date of collection: 2024-10-29
- Only included users with 50+ followers
- Up to 500 most recently pushed repositories per user

### Key Points
- **Data Collection Process**: We collected GitHub users from Dublin with over 50 followers, along with their repositories, using the GitHub API.
- **Interesting Finding**: Most Dublin users actively contribute to repositories in Python and JavaScript, with high levels of activity in open-source projects.
- **Recommendation**: Dublin developers could increase visibility by collaborating on popular open-source projects with high star counts.
