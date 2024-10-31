# GitHub User Analysis

### Data Collection Process

1. I used the GitHub REST API to scrape data on users in Basel with a minimum of 10 followers, handling pagination and rate limits to ensure complete data acquisition.
2. User and repository data were filtered and processed to standardize fields (e.g., company names were uppercased, whitespace removed, boolean values were lowercased etc.,).
3. The scraping and analysis was conducted in the notebook `project.ipynb`, which is included in this repository.
4. All processed data was exported to `users.csv` and `repositories.csv` for seamless data analysis and portability.

### Data Analysis

- I analyzed attributes such as follower count, bio length, and hireability status to identify correlations with popularity.
- Analysis included repository creation trends by weekday, preferred languages, and license types.
  
### Findings

- Developers who joined GitHub recently are more likely to use newer languages like Rust, while experienced users prefer traditional languages like JavaScript and Python.
- Users who enable GitHub project tools and wikis tend to use them together, suggesting a collaborative mindset.

### Recommendations

1. Based on findings, developers should expand their bios to increase visibility.
2. Engaging with GitHub’s project management tools correlates with higher interaction, potentially leading to better project outcomes.
