# getting-and-cleaning-data

## Plot the 30-day mortality rates for heart attack (outcome.R)
  1.installing packages
  
  2.Reading in data using variable outcome
## Finding the best hospital in a state (best.R)
  1.Read outcome data using variable out_dt
  
  2.Column name is same as variable so changing it to chosen_state
  
  3.Check that state and outcome are valid
 
  4.Renaming Columns to be less verbose and lowercase
  
  5.Columns indices to keep
  
  6.Filtering out unnessecary data 
  
  7.Find out what class each column is
  
  8.Removing Missing Values for numerical datatype (outcome column)
  
  9.Order Column to Top 
## Ranking hospitals by outcome in a state (rankhospital.R)
  1.Read outcome data
  
  2.Column name is same as variable so changing it 
  
  3.Check that state and outcome are valid
  
  4.Renaming Columns to be less verbose and lowercase
 
  5.Filter by state
   
  6.Columns indices to keep
  
  7.Filtering out unnessecary data 
  
  8.Find out what class each column is 
  
  9.sapply(out_dt,class)
  
  10.Removing Missing Values for numerical datatype (outcome column)
 
  11.Order Column to Top 

## Ranking hospitals in all states (rankall.R)  
  1.Read outcome data
  
  2.Renaming Columns to be less verbose and lowercase
  
  3.Columns indices to keep
  
  4.Filtering out unnessecary data 
  
  5.Find out what class each column is 
  
  6.sapply(out_dt,class)
  
  7.Change outcome column class
 
