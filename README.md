

# Integrate all types of data from the Neuromodulation Research Center

## Documentation

Read here: https://datastorageanalysisarchitecture.readthedocs.io/en/latest/


## To do list
Add  deep lab cut videos to NWB.

Add  eye-tracking data to the NWB structure

Eye tracking/ Utah Array/DBS Lead/Gray Matter manufacturer

Change example to Barb

## Discussion on March 8 2022

1. All tdt names use upper case, e.g. GRMT, UMCX

2. In tdt system, using the first character to discriminate different device

- U represents utah array, e.g. UMCX, UPMC, and UDLP represent utah array in MC, PMC and DLP areas invidually

- GRMT represents gray matter

- D represent DBS lead, e.g. DBSS and DBSG reprent DBS leads in STN and GP individually

3. How to store eye tracking data, two alternatives (Need discussion with C)

- Send a link to the original txt file

- Store as the time series data and the particular time stamp for eye movement detected

4. In tdt system, no need to store snip field

5. DLC data

- Store the link to the recorded videos

- Store the dlc processed x, y trajectory data 

6. MA data

- Store the link to the recorded raw MA data

- Store the cleaned MA data as time series data 

