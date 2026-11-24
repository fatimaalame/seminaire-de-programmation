# Ticket 2 Ride
We want to explore the Swiss Railway Passenger Data. The context is within the seminar in programming at the UNIGE (autumn 2026).

## About the project
It's a python data analysis project that explores the passenger traffic across Switzerland and we used the publicly available railway data (see references below). Our goal is to actually use this data to turn it into an analysis. 
We use Python, Pandas, Matplotlib and Jupyter Notebook to explore the datasets, analyse the results as well as creating visualisations. 

## Data sources
We used two main datasets. The first one is the SBB Passenger Frequency (called 'passagierfrequenz.csv'). It contains infos about passenger frequency at SBB. We mainly used the average daily number of boardings and getting off. By the way, not all the years are available. We only have 2018, 2022, 2023, 2024 and 2025. 
The second one is the Swiss Public Transport Timetable (GTFS). This one provides informations about stations, routes, timetables, scheculed services. We used it to compare between PF and the railway service activity. We couldnt put it on github because certain files are too big (>100mB), but we'll send it through the moodle. 

## Our 5 scénarios

### 1. The busiest station
    We looked for the 10 busiest stations in Switzerland by examing the evolution of PF from 2018 to 2025, calculated the percentage changes, showed the graph and discussed the results
   
### 2. Cornavin's story
    How did the traffic at Cornavin change over time ? We also showed the evolution of PF (2018-2025), and analysed it. 
   
### 3. Swiss rail map
    Where are Switzerland's busiest railway stations located? We used the coordinates to visualise the stations and we explored their distribution and PF. 
    
### 4. Your station, please?
    What if we want to explore a specific station? To do that, we created a function (analyser_gare()) that allows users to enter a station name and display its available passenger statiscits (+ its graph) 
    
### 5.  Passenger power
    Does a station with more passengers also have more scheduled train departures? We're answering by comparing the PF data with the SBB timetable informations we found on GTFS. 

## How to run the notebook?
1. Download or clone the repo
2. Open the folder (CW2_Ticket2Ride)
3. Make sure you got Pyhton, Pandas, Matplotlib and Jupyterlab installed
4. Write "Jupyter lab" in the terminal (it should open a tab with a local server)
5. Run the notebook cells in order

For info, the csv files should remain inside the data/folder and also (again) some large files are not included in the github repo but we sent it through the moodle. 

## Limitations 
Our passenger frequency data set doesnt have infos on the years 2019 to 2021 so we couldnt analyse the changes during those years (it creates a gap). And also, the PF represents the average daily boardings and alightings not the count of unique passengers (although we understand that would be quite difficult to do so). 

## Acknowledgements 
We would like to thank SBB Open Data and Open Transport Data Switzerland for making these datasets publicly available. And, this project was developed for an academic assignment at the UNIGE. It's not an official SBB project! 

## IA notice 
We used ChatGPT (OpenAI) as a supporting tool throughout this project. It helped us understand some concepts, troubleshoot coding issues, find (rather fast) the bugs, gave us feedbacks and reviews some of our written explanations. 
The code, the interpretation of the data, final decisions and the submitted work remain our responsibility. 

## References: 
- https://data.sbb.ch/pages/home/ (21.11.26)
- https://data.sbb.ch/explore/dataset/passagierfrequenz/export/ (21.11.26) 
- https://data.sbb.ch/explore/dataset/passagierfrequenz/information/ (21.11.26)
- Horaire 2026 (GTFS2020) https://data.opentransportdata.swiss/fr/dataset/timetable-2026-gtfs2020 (21.11.26)
- https://gist.github.com/pb111/a6bdc9fd610344973e06da478604716f (24.11.26)
- https://medium.com/@monicanogueras/10-graph-examples-using-matplotlib-b08e6c7bebcf (24.11.26)
