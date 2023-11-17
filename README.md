# Data Analytics Project from M.V.

About housing market in King county (Seattle region).
Chosen character is Amy Williams, a member of the mafia who wants to sell and buy from the top 10% of houses AND looks for an outskirt residence.

It includes the data-fetching from SQL and includes the join of the two given data tables.
If you run the script, it's self-explaining and shows you all the different and relevant graphs.
There also exists a Google Presentation from the stakeholder-perspective, that is, given a presentation to Amy Williams


## Requirements

- pyenv
- python==3.11.3

## Setup

The setup requirements are shown below, but they require a Linux based operating system.

### Environment

This repo contains a requirements.txt file with a list of all the packages and dependencies you will need. Before you install the virtual environment, make sure to install postgresql if you haven't done it before.

```bash
brew update
brew install postgresql@14
```

In order to install the environment you can use the following commands:

```
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```
