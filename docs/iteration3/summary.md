# Iteration 3

## Updates
The only comments we have received after Iteration 2 were concerned with our presentation style. Therefore, we were not able to reflect these comments in the repository. We did not perform any major updates to existing code from part 2, except that we finalized getting distance and test score data, as we planned on doing from part 2. This was because there were no changes

## Implementation Summary

- [/preprocessing.ipynb](/preprocessing.ipynb) contains all the same initial preprocessing stuff for the GPA and count data. (All three of us) 
- [/distances.ipynb](/distances.ipynb) uses Google Maps to find distances for each campus to each school, and appends this to previous data. (Nick)
- [/TestScores.ipynb](/TestScores.ipynb) merges all the test score data into two data frames and resaves them. (Michal)
- [/MergingTestScores.ipynb](/MergingTestScores.ipynb) merges the two test score frames into one and resaves them (Michal)
- [/FindingCdsNumbers.ipynb](/FindingCdsNumbers.ipynb) takes the test dataset from the previous notebook and matches school names to ID numbers, so that we can combine the test score data with the GPA, count, and distance data. Do that, and save the result (Michal)
- [/DataExploration.ipynb](/DataExploration.ipynb) gives some visualizations for the initial GPA and count data. (Nelson and Nick)
- [/Modelling.ipynb](/Modelling.ipynb) does all the splitting, normalizing, and then actual fitting with our linear and baseline models (All three of us contributed to this)

All the data can be found in the /data catalog.
Additional documentation about the project can be found in the /docs catalog.
To see the latest progress we have made, see /experiments.