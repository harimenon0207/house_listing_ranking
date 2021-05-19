# house_listing_ranking
Project to scan through open house listings for sale on redfin and create a weighted score and match percentage against preferences and filters.

## Problem Statement
As part of the house buying search, one of the time consuming tasks is to scan and identify property listings that match with the preferences set and also rank them in the order of preferences so that we identify the ones of interest and follow up with viewing the property and actions thereafter.


## Objective
New listings mostly come in every week on Wednesdays and Thursdays every week and offers are reviewed early next week giving buyers a small time wondow to identify properties of interest, view them and decide on putting an offer. Moreover timeslots for viewings fill up within a few hours so its all the more important to decide which properties need viewing.

The goal of this analysis to upload all the property listings on Thursdays, apply a weighted scoring model based on preferences and output a ranked listing of properties to then be further looked into.

## Data Source

The data for listings are obtained from Redfin, where search results can be downloaded based on applied filters.

## Expected Output

Ranked list of Properties with unique ID with:
- Weighted Score 
- Match Percentage against preferences
