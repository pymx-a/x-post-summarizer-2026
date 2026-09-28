# x-post-summarizer-2026

AI-generated summary of a public figure's 2026 X posts, built with LangGraph, MCP tools, and the X API.

## Project Description
This repository summarizes the 2026 X posts of a public figure using AI. The analyzed account handle is @llm_wizard. The project leverages a LangGraph agent combined with GitHub MCP tools for repository operations and the X API v2 for retrieving posts.

## How It Works
- Uses the X API v2 to fetch recent posts from the specified X account.
- Summarizes the posts into key themes, notable posts, and statistics using AI.
- Stores the summary and metadata in the repository.

## Replicating the Process
To replicate this project, follow these steps:

1. **Set up your X API Bearer Token:**
   - Obtain your Bearer Token from the X developer portal.
   - Set it as an environment variable in your system:
     ```bash
     export X_BEARER_TOKEN="your_bearer_token_here"
     ```

2. **Install Python dependencies:**
   - This project requires the `requests` library.
   - Install it using pip:
     ```bash
     pip install requests
     ```

3. **Run the search script:**
   - Use the provided `x_search.py` script to fetch recent posts:
     ```bash
     python x_search.py <x_account_handle>
     ```
   - If no handle is provided, it defaults to `llM_wizard`.

4. **Analyze and summarize:**
   - Use AI tools or manual methods to analyze the fetched posts and update the repository with summaries and metadata.

---

*This project demonstrates combining AI with API and repository management tools to automate social media content analysis.*
