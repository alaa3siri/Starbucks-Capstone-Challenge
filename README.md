# Starbucks Dataset
Project in Data Scientist Nanodegree of Udacity


## Overview 

Starbucks data it is a project for Data Scientist Nanodegree in Udacity. The dataset about how people make purchasing decisions and how those decisions are influenced by promotional offers.We will do recommendation engine that recommends Starbucks which offers should be sent to a particular customer.

## Problem Statement
Not all users receive the same offer so we want solve this by answer this tow questions : Which offer should be sent to a particular customer to let the customer buy more? Which demographic groups respond best to which offer type?

## File Descriptions 

The data is contained in three files:
- `portfolio.json` - containing offer ids and meta data about each offer (duration, type, etc.)
- `profile.json` - demographic data for each customer
- `transcript.json` - records for transactions, offers received, offers viewed, and offers completed

 Schema explanation of each variable in the files:

`portfolio.json`
- id (string) - offer id
- offer_type (string) - the type of offer ie BOGO, discount, informational
- difficulty (int) - the minimum required to spend to complete an offer
- reward (int) - the reward is given for completing an offer
- duration (int) - time for the offer to be open, in days
- channels (list of strings)

`profile.json`
- age (int) - age of the customer
- became_member_on (int) - the date when customer created an app account
- gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
- id (str) - customer id
- income (float) - customer's income

`transcript.json`
- event (str) - record description (ie transaction, offer received, offer viewed, etc.)
- person (str) - customer id
- time (int) - time in hours since the start of the test. The data begins at time t=0
- value - (dict of strings) - either an offer id or transaction amount depending on the record


## Results
The Results can be found at the post available [here](https://medium.com/@Alaa_Abdo/starbucks-offer-data-science-63dc134925e9).

