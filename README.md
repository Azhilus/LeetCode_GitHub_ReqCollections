## GitHub API Collection

### Overview

The GitHub API Collection includes requests to fetch various data from GitHub, such as user details, repositories, contributions, followers, issues, and pull requests.

### Importing Collection

To import the GitHub API Collection, follow these steps:

1. Clone or download this repository to your local machine.
2. Import the `Github_User_GraphQL.json` file into your API client (e.g., Postman).
3. Update the variables in the requests with the appropriate values:
   - Replace `{username}` with the GitHub username for requests requiring it.
   - For requests to the GraphQL endpoint, generate a token from your GitHub profile by visiting [GitHub Settings Tokens](https://github.com/settings/tokens). Use this token as a Bearer token in the request's authentication headers.

## LeetCode API Collection

### Overview

The LeetCode API Collection provides queries to retrieve various data from the LeetCode platform, including user profile, language statistics, skill stats, contests, problems solved, badges, calendar, recent submissions, current timestamp, and the daily coding challenge question.

### Importing Collection

To import the LeetCode API Collection, follow these steps:

1. Clone or download this repository to your local machine.
2. Import the `Leetcode_Profile_GraphQL.json` file into your API client (e.g., Postman).
3. Update the variables in the requests with the appropriate values:
   - Ensure to pass the LeetCode username as variable in the requests requiring it.

## GitHub API Usage Notes

- For requests accessing GitHub data, you need to generate a token from your GitHub profile by visiting [GitHub Settings Tokens](https://github.com/settings/tokens). Use this token as a Bearer token in the request's authentication headers.

## Support

If you encounter any issues or have questions about using these collections, feel free to open an issue in this repository.

