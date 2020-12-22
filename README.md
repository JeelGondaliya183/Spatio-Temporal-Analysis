# Spatio-Temporal-Analysis
Analysis and Visualization of the AIS data by using Geopandas and Matplotlib, also clustering the ports based on AIS message density.

## About the AIS Database:

The Automatic Identification System (AIS) database is PostGIS database acquired by the VOLPE National Transportation Systems Center from the U.S. Coast Guard’s
Nationwide Automatic Identification System (NAIS) network.

| Field                  | Description                                                               |
| -----------------------|:-------------------------------------------------------------------------:| 
| event_time             | UTC time when the data were generated (text).                             | 
| location.coordinates.0 | Latitude coordinate (decimal degrees) of the vessel’s position (text).    |  
| location.coordinates.1 | Longitude coordinate (decimal degrees) of the vessel’s position (text).   |   
| mmsi                   | Maritime Mobile Service Identity number of the vessel (text)              |
| sog                    | Vessel’s speed over ground (text).                                        |
| cog                    | Vessel’s course over ground (text).                                       |

event_time:                
location.coordinates.0
location.coordinates.1
position_accuracy
mmsi
sog
cog

## Motivation:
## Data Analysis:


## Instruction to execute the Application:

*** Download the zip file in order to see the code and output, not visible in github because of the file size (> 25 MB) ***

1.	Extract the .zip file and Install the required packages.
	-	pip install -U Shapely -user
	-	pip install -U geopandas –user
	-	pip install -U numpy –user
	-	pip install -U pandas –user
	- pip install -U scikit-learn --user
  - pip install -U seaborn --user
	
2. Extract .zip file and keep all the files into one folder.
	
3. Run the file ‘SpatioTemporalAnalysis.py’ in google Colaboratory / Jupyter Notebook.
   If using Jupyter Notebook,
   (1) Install Anaconda
   (2) From Anaconda Command Line, Go to the folder where all the files are stored.
   (3) Next, Run Command "Jupyter Notebook"
   (4) Open SpatioTemporalAnalysis.ipynb (If want to see the animation, Run all the cells).
   
   If google Colaboratory(Recommeneded if you want to take a quick look),
   (1) Go to https://colab.research.google.com/notebooks/intro.ipynb -> Tab GitHub
   (2) Add URL https://github.com/JeelGondaliya183/Spatio-Temporal-Analysis and select SpatioTemporalAnalysis.ipynb (If want to see the animation, Run all the cells).
   
   Please provide feedback. 
   Thank you:)
