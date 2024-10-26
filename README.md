# GitHub Beijing User and Repository Analysis

## 1)Data Collection
- Data was collected via the GitHub REST API v3. Users were filtered by location ("Beijing") and follower count (>500). For each qualifying user, we
- Extracted essential profile details and a subset of their public repositories, ensuring all collected data matched fields in the `users.csv` and `repositories.csv` formats.
  
## 2) Intresting facts 
- A notable finding revealed that a significant proportion of popular repositories are written in languages like JavaScript  which may indicate trends in Beijing's tech ecosystem.

## 3)Findings and Recommendations
- **Trending Languages**: JavaScript are dominant in popular repositories, signaling a strong demand and presence in these languages.
- **User Engagement**: Many top users contribute significantly to open-source projects, which could provide useful connections for developers in similar domains.
- **Developer Recommendation**: Focus on projects in popular languages, as contributing to high-engagement repositories in these languages can boost visibility and potential collaborations.
- **Scrapping Automation** : Code is setup in such way that once ther response is parsed from api it automatically writes to `users.csv` and to `repositories.csv` in the git repo via token in code
- **usage of PySpark** : Instead running pandas Pyspark can be utilied in ease to process the code pretty faster

