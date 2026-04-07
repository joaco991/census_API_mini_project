# census_API_mini_project
Census API Data Acquisition (Python)

Small data acquisition project that pulls U.S. Census/ACS data via a public API endpoint and loads the result into a pandas DataFrame for basic validation and export.

Goal
  Practice working with a real API (requests) and converting JSON responses into structured tabular data (pandas).

What it does
  Sends an API request to the Census endpoint
  Parses the JSON response
  Builds a pandas DataFrame
  Performs basic checks (headers/types/missing values as applicable)
  Exports the cleaned dataset to CSV for further analysis

Tech stack
  Python
  requests
  pandas

How to run
  Create and activate a virtual environment (optional but recommended).
  Install dependencies: pip install -r requirements.txt
  Run the notebook or script in this folder.
