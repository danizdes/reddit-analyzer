# reddit-analyser
This project aims to utilize PRAW to get the average amount of comments per subreddit and compare subreddits within their own respective niches as well as comparing the average amount of comments between niches.

# Subreddits
While the current amount of niches and subreddits are few, I plan to extend these in my free time

## Technology
- r/programming
- r/machinelearning
- r/technology

## Gaming
- r/gaming
- r/minecraft
- r/leagueoflegends

## Fitness & health
- r/fitness
- r/running
- r/nutrition

# How to run locally

First, clone the github repository and open it in you're terminal.

Install all the requires python libraries:
```bash
pip install -r requirements.txt
```
Next, create a ```.env``` file in the root folder. Copy and paste this:
```
CLIENT_ID=""
CLIENT_SECRET=""
USERNAME=""
```

Now head over [here](https://www.reddit.com/prefs/apps), and create a new app. Make sure you have a reddit account

Copy the client id, client secret and you're reddit username and add it to the .env file

Ensure you have [Jupyter](https://jupyter.org/) installed and launch the ```analysis.ipynb``` file using Jupyter or 
another suitable software

Execute all the code and repeat with the ```data_processing.ipynb`` file.

This should create identical .csv files in the ```data``` folder with updated information.