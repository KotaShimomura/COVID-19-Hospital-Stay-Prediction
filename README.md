# COVID-19-Hospital-Stay-Prediction

# [ゼミコンペ](https://www.kaggle.com/c/1056lab-covid19-hospital-stay-prediction/data?select=train.csv)のbaseline,多クラス分類で使用
## 実行環境
ubuntu : 20.04  
Docker version 20.10.8  


# Data Description
train.csv - training set that contains `Stay_Days` that is classified into 11 categories.  
test.csv - test set that does not contain `Stay_Days`.  
simple_submission.csv - a sample submission file in the correct format.  

# Data Fields  
`case_id`  
`Hospital`  
`Hospital_type`  
`Hospital_city`  
`Hospital_region`  
`Available_Extra_Rooms_in_Hospital` - Number of extra rooms available in the hospital  
`Department` - Department overlooking the case: `radiotherapy`, `anesthesia`, `gynecology`, `TB & Chest disease` or `surgery`  
`Ward_Type` - `R`, `S`, `Q`, `P`, `T` or `U`  
`Ward_Facility` - `F`, `E`, `D`, `B`, `A` or `C`  
`Bed_Grade` - Condition of bed in the ward  
`patientid`  
`City_Code_Patient` - City Code for the patient  
`Type of Admission` - Admission type registered by the hospital: `Emergency`, `Trauma` or `Urgent`  
`Illness_Severity` - Severity of the illness recorded at the time of admission: `Extreme`, `Moderate` or `Minor`  
`Patient_Visitors` -  
`Age` - `0-10`, `11-20`, `21-30`, `31-40`, `41-50`, `51-60`, `61-70`, `71-80`, `81-90` or `91-100`  
`Admission_Deposit` - Deposit at the admission time  
`Stay_Days` - Stay days by the patient: `0-10`, `11-20`, `21-30`, `31-40`, `41-50`, `51-60`, `61-70`, `71-80`, `81-90`, `91-100`, `101-`  
