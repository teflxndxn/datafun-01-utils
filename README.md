# datafun-01-utils

### Project Setup Summary


- Created a new repository: `datafun-01-utils`
- Cloned the repository to my local machine
- Added the following standard files:
  - `.gitignore`
  - `requirements.txt`
  - `README.md` (initialized via GitHub for smoother setup)
- Configured Git with my `user.name` and `user.email`
- Made an initial commit and pushed the changes to GitHub
- Created and activated a local Python virtual environment

---

### Virtual Environment Setup

This project uses a local Python virtual environment to manage dependencies.

To create and activate the environment:

```bash
# Create the virtual environment
python3 -m venv .venv

# Activate the virtual environment (macOS/Linux)
source .venv/bin/activate

# For Windows (use this instead)
.venv\Scripts\activate

# Blessing Analytics - Company Byline

## Project Overview
This Python module showcases my (hypothetical) analytics consulting company, Blessing Analytics. It demonstrates how I can use Python variables, f-strings, and basic statistics to generate useful bylines for analytics projects. This code is reusable across various projects.

## Purpose
The purpose of this project is to:
- Create a reusable byline showcasing the core values of the analytics company
- Practice Python syntax, including variables, data types, and f-strings
- Perform basic statistical calculations like mean, standard deviation, and range

## Features
- Customizable company byline with variables for international clients, years in operation, skills offered, and client satisfaction scores
- Utilizes Python’s `statistics` library to calculate minimum, maximum, mean, and standard deviation of client satisfaction scores
- Prints a professional company byline to the console

## Project Files
1. **utils_bless.py** - Contains the code for generating the company byline, defining variables, and calculating statistics.
2. **main.py** - A script that calls the functions from `utils_bless.py` to print the byline.
3. **README.md** - This file that explains the project details.

## How to Run
1. Clone the repository to your local machine.
2. Set up and activate a virtual environment.
3. Install any necessary dependencies using `pip install -r requirements.txt`.
4. Run the main script:
   ```bash
   python main.py

