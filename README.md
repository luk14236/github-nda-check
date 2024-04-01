# github_nda_check.py

This Python script performs a check on GitHub for files containing a specific keyword and collects information about the associated repositories and contributors.

## Usage

1. **Dependency Installation:**
   - Install the `PyGithub` library by executing the provided command.

2. **Running the Script:**
   - Set up your GitHub API key in the `api-key` variable.
   - Define the desired keyword in the `keyword` variable.
   - The script will search GitHub for files containing the specified keyword.
   - It will collect information about the repositories and contributors associated with these files.
   - The collected information will be saved in a JSON file with a timestamp in the filename.

## Requirements

- Python 3.x
- Libraries:
  - PyGithub

## Overview

This script searches GitHub for files containing a specific keyword and collects information about the associated repositories and contributors.

## How It Works

- The script uses the `PyGithub` library to interact with the GitHub API.
- It performs a search on GitHub for files containing the specified keyword.
- For each found file, it collects information about the repository (name, description, URL, etc.) and the associated contributors (name, email, location, etc.).
- The collected information is formatted into a JSON file and saved locally.
