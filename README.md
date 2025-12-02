# Case Study — NYC Vision Zero Motor Vehicle Collision Forecasting

## Documentation Map
The hierarchy of folders and files contained in this project are as follows:

```text
DS-4002-CS3
├── DATA
│   ├── collisions_cleaned.csv.zip
│   └── collisions_raw.csv.zip
├── SCRIPTS
|   ├── Daily_Borough_Forecasting.py
|   ├── Hourly_Borough_Forecasting.py
│   └── preprocessing.py
├── SUPPLEMENTAL MATERIALS
├── LICENSE.md
└── README.md
```

## Instructions
  1. **Start with the hook document!**
  2. **Set up Python and install required add-on packages**
     - Clone this repository: https://github.com/evelynmaxwell/DS-4002-CS3/
     - Ensure you have Python 3 installed on your system.
     - Install required packages using `pip install -r requirements.txt`
  3. **Prepare the data**
     - Download `collisions_raw.csv.zip` from `DATA` folder.
     - Unzip the file and place `collisions_raw.csv` into the `DATA` directory.
     - Run the `preprocessing.py` (from `SCRIPTS` folder). This script will clean the raw data and save the processed dataset as `DATA/collisions_cleaned.csv`.
  4. **Identify the Highest Risk Borough**
     - Open and run `Daily_Borough_Forecasting.py` in the `SCRIPTS` folder.
         - Be sure to set the appropriate forecasting date (January 1, 2026).
     - Record the borough with the highest predicted number of collisions — you will use this for the next step.
  5. **Run the Hourly Forecasting Model**
     - Open and run `Hourly_Borough_Forecasting.py` in the `SCRIPTS` folder.
         - Be sure to input the borough identified in Step 4.
     - Save a screenshot or table of your hourly results.
  6. **Interpret and Document Your Findings**
     - Be curious! Generate any additional plots or graphs that may be useful.
  
     
 
