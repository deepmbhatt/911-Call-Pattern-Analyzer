# 911 Call Pattern Analyzer
## Overview
This project analyzes 911 call data from 2015 to 2020. The analysis covers trends, response times, and incident types, providing insights into public safety patterns. The project includes data cleaning, visualization, and exploratory data analysis.

## Data
Link to data set: https://www.kaggle.com/datasets/deepmbhatt/911-calls-dataset/data

Date and Time: Timestamp of the call (timeStamp)
Location: Latitude, longitude, and address of the incident (lat, lng)
Incident Type: Nature of the emergency (e.g., fire, medical, police) (title)
Town and zip: Name of town and zip code for call (twp, zip)

## Prerequisites
To run the code, you will need:

Python 3.8+
Jupyter Notebook
Required Python packages (see requirements.txt)

## Installation
Clone the repository:
    
    git clone https://github.com/deepmbhatt/911-Calls-Data-Analysis.git
Navigate to the project directory:

    cd 911-Calls-Data-Analysis

Install the required packages:

    pip install -r requirements.txt
    
## Usage
Open the Jupyter notebooks to explore the data and visualizations:
Navigate to the notebooks directory and open the desired notebook.


# Results
Conclusions of Data Analysis:
1. Traffic and Fire calls are most frequent during 5 PM.
EMS calls are most frequent at 10 AM.

![image](https://github.com/user-attachments/assets/d03f1ad9-b3e8-449d-99bc-2f4730c37e2b)

2. January Sees the most amount of calls.

![image](https://github.com/user-attachments/assets/cc0da057-e67e-4cc6-9007-2303448df4d9)

![image](https://github.com/user-attachments/assets/0f6e7f28-98bd-4245-b3a4-763bac9f3a86)

3. Highest Calls are about EMS followed by traffic and then fire.

![image](https://github.com/user-attachments/assets/a0a75e4f-3f92-4266-9a2d-b655790dc63a)

4. Most Calls are observed on Friday

![image](https://github.com/user-attachments/assets/f08f714f-c123-4c5b-a676-decfe32e6f93)

![image](https://github.com/user-attachments/assets/b8fc9b7c-01c4-4051-9b28-872a3129f206)

5. Emergency for week days have a peak rate in between 10 pm to 6 am where as  for week ends it is in between 12 pm to 8 am
![image](https://github.com/user-attachments/assets/041327c2-204d-47a9-a43b-81333f58e151)

6. Top 5 reasons for 911 calls were:

    | Reason                     | Count   |
    |----------------------------|---------|
    | Traffic: VEHICLE ACCIDENT  | 148,372 |
    | Traffic: DISABLED VEHICLE  |  47,909 |
    | Fire: FIRE ALARM           |  38,336 |
    | EMS: FALL VICTIM           |  34,676 |
    | EMS: RESPIRATORY EMERGENCY |  34,248 |
   
![image](https://github.com/user-attachments/assets/c2a94def-911e-4457-8eba-31bcc3f88281)


7.The data for 911 calls is focused for regions near philadelpia only with some scattered datapoints around the country.

![image](https://github.com/user-attachments/assets/058f0559-c0b1-48ba-9084-36143b43caf8)


8. Most calls for EMS were of:

  |Reason                      | Count |
  |----------------------------|-------|
  |EMS: FALL VICTIM            |  34676|
  |EMS: RESPIRATORY EMERGENCY  |  34248|
  |EMS: CARDIAC EMERGENCY      |  32332|
  |EMS: VEHICLE ACCIDENT       |  25513|
  |EMS: SUBJECT IN PAIN        |  19646|

![image](https://github.com/user-attachments/assets/82580296-bde8-4b52-b0bc-f591eff1fdef)


Health issues are majority for Respiratory emergency and Cardiac emergency.

9. Most calls for fire were of:

  | Reason: Fire                  | Count |
  |-------------------------------|-------|
  | FIRE ALARM                    | 38,336|
  | VEHICLE ACCIDENT              | 10,864|
  | FIRE INVESTIGATION            | 9,444 |
  | GAS-ODOR/LEAK                 | 6,740 |
  | ELECTRICAL FIRE OUTSIDE       | 5,111 |

![image](https://github.com/user-attachments/assets/59ee66c2-f543-4c8f-8b20-1ffc7e9a59db)



Fire issues are majority of Fire alarm going of followed by fire by Vehicle accidents.

10. Most calls for Traffic were of:

  | Reason: Traffic                      | Count  |
  |--------------------------------------|--------|
  | VEHICLE ACCIDENT                     | 148,372|
  | DISABLED VEHICLE                     | 47,909 |
  | ROAD OBSTRUCTION                     | 23,235 |
  | HAZARDOUS ROAD CONDITIONS            | 6,833  |
  | VEHICLE FIRE                         | 3,366  |

![image](https://github.com/user-attachments/assets/77e3cce9-87d5-4bc5-90a0-6d4587a55689)



Traffic issues majority include problems with Vehicle accidents with about 1.5 lakh calls followed by disabled vehicles.

11. Most calls count as per towns are:

    | Town         | Count  |
    |--------------|--------|
    | LOWER MERION | 55,490 |
    | ABINGTON     | 39,947 |
    | NORRISTOWN   | 37,633 |
    | UPPER MERION | 36,010 |
    | CHELTENHAM   | 30,574 |
    
![image](https://github.com/user-attachments/assets/65e59e1d-0d7f-4969-b90d-005cdd0db93c)


12. Lower Merion has most calls for:

    | Reason  | Count  |
    |---------|--------|
    | Traffic | 23,758 |
    | EMS     | 21,578 |
    | Fire    | 10,154 |
    
![image](https://github.com/user-attachments/assets/29149b6e-89f7-4e17-9b7c-3fd25ff39500)


14. Year: 2018 had the highest calls

![image](https://github.com/user-attachments/assets/b8e700e9-096f-4f3c-869c-7e53d8a3bc10)

