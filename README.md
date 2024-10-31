
## README.md

- **Data Extraction Process**: We leveraged the GitHub API to gather comprehensive user and repository data from developers in Dublin with over 50 followers. Each user’s personal details and up to 500 repositories were collected, covering essential activity metrics and developer engagement.

- **Interesting Finding**: JavaScript emerged as the dominant language, yet MDX boasted the highest average star rating per repository, indicating a niche yet high-engagement interest in content-focused development within a coding-centric community.

- **Actionable Recommendation**: For developers aiming to increase visibility, MDX offers a unique opportunity to stand out due to its engagement level relative to its usage. Diversifying with content-driven projects could increase audience interest and engagement.

### Dataset Summary

- **users.csv**: Contains 476 rows and 11 columns detailing user information such as `login`, `name`, `company`, `location`, and `followers`.
  - **Missing Data**: `name` (7), `company` (162), `email` (241), `bio` (152).
  
- **repositories.csv**: Contains 29,184 rows and 9 columns with information on each user's repositories, including `login`, `full_name`, `created_at`, `language`, and `license_name`.
  - **Missing Data**: `language` (7,225), `license_name` (14,012).

### Data Types

- **users.csv** columns: Mostly `object` types, with numerical columns for `public_repos`, `followers`, and `following`.
- **repositories.csv** columns: Various types, including `int64` for `stargazers_count`, `watchers_count`, and `object` for strings. Boolean columns like `has_projects` and `has_wiki` indicate features enabled.
