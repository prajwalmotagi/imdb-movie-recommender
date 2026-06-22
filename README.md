# IMDb Movie Recommender

A weighted rating recommender system built on the IMDb Top 5000 dataset.

## What it does
Fixes vote-count bias in IMDb ratings using Bayesian-style weighted scoring.
Ranks 5,000 real movies fairly — a film needs both a high rating AND enough 
votes to rank at the top.

## Built with
- Python
- Pandas
- Google Colab

## Key concept
A 9.6 rating from 45 votes is less trustworthy than a 9.3 from 2.8 million votes.
This system corrects that automatically.
