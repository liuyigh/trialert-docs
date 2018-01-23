## Welcome to TriAlert

A Python/Web2py based web app for clinical trial alert.

The project goal is to develop a web-based public service to notify registered user updates of clinical trials selected by the user.

### Data from ClinicalTrials.gov

[Public API](https://clinicaltrials.gov/ct2/resources/download) 

### Features

1. user defined trial #
2. If new, download data, say `new`
3. If in system and same data, say `on track`
4. If in system and new data, say `updated`
5. Daily check, if same, do nothing, if updated, notify, avoid duplicate `updated` tag when user just keyed in.
6. Data analysis: 
    * most tracked
    * by phase I, II, III
    * by public (market cap), private
    * PI?
7. Social function
    * recommend what you might like

8. remove trial if nobody tracks it.
9. it seems trials updates by 7am in the morning. do twice a day?
10. weekly mark, daily mark, user new mark, trial new mark

### Support or Contact

Please go to [BioEquity](http://bioequity.org)

This is the docs.
