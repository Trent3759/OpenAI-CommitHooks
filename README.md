# Commit Hooks

A repo for commit hooks developed in Python that utilize OpenAI. 

## Prerequisites

Before using these scripts, ensure you have the following:

- Python installed on your system.
- OpenAI API key set up and configured in the environment variable `OPENAIAPIKEY`.
- Git installed on your system.

## Installation

1. Clone this repository to your local machine.

   ```bash
   git clone https://github.com/Trent3759/OpenAI-CommitHooks.git
   ```
2. Move the desired file to your project's .git/hooks/ directory.
   ```bash
   mv <commit-hook-file> /path/to/your/project/.git/hooks/
   ```
3. Make the script executable.
   ```bash
   chmod +x /path/to/your/project/.git/hooks/<commit-hook-file>
   ```
## Hooks
### prepare-commit-msg
This generates commit messages for your commits for you. If text is already entered, it will append the generated text on the end. Each time you commit you will be asked if you would like to generate a message. For each generated message, the user must confirm the    message before it is used. 

## License
This project is licensed under the MIT License - see the LICENSE file for details.


