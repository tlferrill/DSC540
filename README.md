DSC540, Data Preparation - Term Project
Bellevue University
May 29, 2020

This project is about Merging and Storing Data in a Database from Multiple Sources then Visualizing that Data

Using a SQLite database, three datasets will be imported and systematically prepared and loaded into a database.  
While loaded individually, these database tables will be merged together to support analysis.     

The datasets contain information on how many people have been killed and injured from gun violence.  Analysis steps include:         

- Prepare Datasets: the datasets will be imported, cleaned, and transformed for use in this notebook    
--- Obtaining datasets within this notebook ensures most current data has been applied to the analysis

- Establish the SQLite Database: each dataset will be imported into a database as individual tables    
--- Analysis will drive the combination and creation of additional tables that combine data from these three tables   
--- Initially, the database had four tables, at conclusion of analysis there are nine tables
--- As a precaution, if any tables currently exist in the database, they will be deleted

- Create Visualizations: multiple graphs will be prepared that represent analysis based on years, states, and those killed and injured    

Through analysis, a series of visualizations were generated leveraging Matplotlib and NumPy.  The visualizations include:    
- Two sets of bar graphs identifying those Killed and Injured as a result of Gun Violence over 
  a period of years using two different datasets    
- Line graph comparing number of deaths due to gun violence throughout the year across multiple years     
- Multi-bar graph with Number Killed and Injured by Gun Violence From 2013 to 2018 by State, uses CSV and WEB datasets    
- Stacked bar graph of the IL cities with the top counts of killed and injured (excluding Chicago), 
  uses CSV, WEB, and API datasets
- Two pie charts with total number of those killed and injured by year for years 2014 to 2018, 
  uses CSV, WEB, and API datasets
  
 
 Note: 
 - When running this notebook file, the kaggle.json file has to be placed in a folder titled .kaggle loaded at the 
 working directory in order to be accessed from within the notebook.
 
 - One file referenced, gun-violence-data_01-2013_03-2018.csv, is too large to be placed within this repository.  
 This file is available from Kaggle: https://www.kaggle.com/jameslko/gun-violence-data 
 
