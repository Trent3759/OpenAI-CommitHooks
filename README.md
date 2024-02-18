# Git Commit Message Generator

This Python script, developed by Trenton Scott, is a pre-commit hook for Git. It utilizes OpenAI's GPT-3.5-turbo model to generate commit messages based on the changes made in the staged files.

## Prerequisites

Before using this script, ensure you have the following:

- Python installed on your system.
- OpenAI API key set up and configured in the environment variable `OPENAIAPIKEY`.
- Git installed on your system.

## Installation

1. Clone this repository to your local machine.

   ```bash
   git clone https://github.com/Trent3759/OpenAI-CommitHooks.git
   ```
2. Move the pre-commit file to your project's .git/hooks/ directory.
   ```bash
   mv prepare-commit-msg /path/to/your/project/.git/hooks/
   ```
3. Make the script executable.
   ```bash
   chmod +x /path/to/your/project/.git/hooks/prepare-commit-msg
   ```
## Usage
After installing the pre-commit hook, every time you commit changes, this script will prompt you to generate a commit message using OpenAI's GPT-3.5-turbo model. It will show you the diff of the staged files and suggest a commit message based on the changes. You can either confirm the suggested message or opt to use a previous message.

## License
This project is licensed under the MIT License - see the LICENSE file for details.


