## These notebooks used data provided by SAWS for the CivTechSA Datathon held in June 2019.  For this event, I worked with two others from Codeup to offer insights and create proof of concept models.  Our focus was on sanitation sewer overflows (SSO's).  Findings included trends in grease caused SSO's during colder months, high gallon leak locations to be targeted first for most impact, and the importance of monitoring recently cleaned pipes due to grease clogs occuring sooner than expected.

## Our presentation was awarded 'Most Solvable'.

## The proof of concept notebook is included.  There was not a lot of data to try and predict SSO's, so we used the idea that monitoring flow can help predict when a pipe will reach 80% clogged in order to be cleaned prior to an SSO occuring.

## The proof of concept helper functions are functions to create a mock pipeline and flow data that can be used in a polynomial regression model.  Discussions with SAWS informed them that other features can be used if data was available.