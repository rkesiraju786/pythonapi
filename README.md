Overview

This Python script allows you to interact with the GitHub API to query user information and fetch details of the top 20 star users. It provides a straightforward way to retrieve valuable insights from the GitHub platform.

Features

User Query: Fetch detailed information about a specific GitHub user by providing their username.
Top 20 Star Users: Retrieve information about the top 20 users with the most stars on their repositories.
Prerequisites

Python 3.x
GitHub account
GitHub API token (optional but recommended for increased rate limits)

Setup

Clone the repository:
git clone https://github.com/your-username/github-user-query.git
cd github-user-query

Install dependencies:
pip install -r requirements.txt

Obtain a GitHub API token (optional but recommended):
Generate a token in your GitHub account settings.
Export the token as an environment variable:
export GITHUB_TOKEN=your-token


Usage

User Query:
python query_user.py --username <username>

Top 20 Star Users:
python top_star_users.py

Tips

GitHub Token: For increased rate limits and better authentication, consider using a GitHub API token.
Environment Variables: Store your GitHub token as an environment variable for security.
Explore Options: Check additional options and customization available in the script files.
Contribute: Feel free to contribute by forking the repository and submitting pull requests.
Happy querying! 🚀
