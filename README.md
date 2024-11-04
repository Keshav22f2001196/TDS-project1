
# GitHub Data Analysis Report

## Data Extraction Process
- **GitHub API** was used to collect comprehensive data on **Dublin-based developers with over 50 followers**.
- Dataset comprises:
  - **476 users** with personal details in **11 columns** in **users.csv** (fields like **login, name, company, location, followers**).
  - **29,184 repositories** across **9 columns** in **repositories.csv** (fields like **login, full name, creation date, language, license**).
- **Missing Data** includes:
  - **Name (7)**, **company (162)**, and **email (241)** for users.
  - **Language (7,225)** and **license_name (14,012)** for repositories.
- **Data Types**:
  - **users.csv**: Primarily **object types** with numerical fields for **public repositories, followers, following**.
  - **repositories.csv**: Mixed types, including **int64 for stargazers_count, watchers_count**, and **Boolean fields** like **has_projects, has_wiki** to indicate enabled features.
- This **detailed data structure** enabled deep analysis of **developer activity and engagement patterns**.

## Interesting Finding
- **JavaScript** emerged as the **most common language** among developers.
- However, **MDX** had the **highest average star rating per repository**, indicating a **high level of community engagement** despite its niche status.
- This finding reveals a strong **interest in content-centric projects** within a code-driven community, highlighting **MDX’s appeal for documentation and functional code integration**.

## Actionable Recommendation
- Developers aiming to **increase visibility and engagement** should consider using **MDX**.
- **MDX’s high engagement** compared to its lower usage makes it a **unique opportunity to stand out** in content-driven projects.
- By creating **content-focused repositories with MDX**, developers can **tap into a niche community interest**, fostering **deeper audience engagement**.
- This strategy offers a way to **differentiate projects**, **attract followers**, and **enhance visibility** in the GitHub community.
