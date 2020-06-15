# Post-to-Gamebus-API-USE-CC-SugarVita-

This repository contains the code written in python, by group A2-4 of the SugarVita case, to post data from the given test data set to the GameBus API. In this program we create a json file that has the timstamps corresponding to the data( glucose measurements ) that have been posted. The program only posts the data that has not been posted before by checking the timestamp of the current data that is to be posted with those in the json file. If timestamp is present in the json file then, the corresponding glucose measurements are not posted. Otherwise the data is posted to the API and the corresponding timestamp is added to the json file. In this way we can avoid posting the same data multiple times.

Although this program works, it is not completely user friendly and some parts of it are still hardcoded.
