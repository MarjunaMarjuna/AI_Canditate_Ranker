# AI Candidate Ranker

## Overview

This project was developed for the Redrob AI Intelligent Candidate Discovery & Ranking Challenge.

The system ranks candidates based on AI skills, career history, professional experience, and recruiter engagement signals to recommend the most suitable candidates for an AI Engineer role.

## Features

* AI skill matching
* Career history analysis
* Experience-based scoring
* Recruiter signal scoring
* Intelligent candidate ranking
* Automatic reasoning generation

## Scoring Strategy

* Skill Score – 40%
* Career History Score – 35%
* Experience Score – 15%
* Redrob Signals – 10%

## Technologies Used

* Python
* JSON
* Pandas
* OpenPyXL

## Project Structure


AI_Candidate_Ranker/
├── src/
│   └── ranker.py
├── output/
│   └── submission.xlsx
├── README.md
├── requirements.txt
└── .gitignore

## Run

bash
python src/ranker.py


The script reads the candidate dataset, ranks candidates based on the defined scoring strategy, generates candidate-specific reasoning, and exports the final ranked results as "submission.xlsx".
