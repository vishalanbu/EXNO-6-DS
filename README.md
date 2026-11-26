# EXNO-6-DS-DATA VISUALIZATION USING SEABORN LIBRARY

# Aim:
  To Perform Data Visualization using seaborn python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.
# Data Set:
```
import pandas as pd
data = {
    'Order_ID': range(1, 21),
    'Month': [
        'Jan', 'Jan', 'Feb', 'Feb', 'Mar', 'Mar',
        'Apr', 'Apr', 'May', 'May', 'Jun', 'Jun',
        'Jul', 'Jul', 'Aug', 'Aug', 'Sep', 'Oct',
        'Nov', 'Dec'
    ],
    'Product': [
        'Laptop', 'Mobile', 'Laptop', 'Tablet', 'Mobile', 'Laptop',
        'Tablet', 'Accessories', 'Laptop', 'Mobile', 'Tablet', 'Laptop',
        'Mobile', 'Accessories', 'Laptop', 'Tablet', 'Mobile', 'Laptop',
        'Mobile', 'Laptop'
    ],
    'Category': [
        'Electronics', 'Electronics', 'Electronics', 'Electronics',
        'Electronics', 'Electronics', 'Electronics', 'Accessories',
        'Electronics', 'Electronics', 'Electronics', 'Electronics',
        'Electronics', 'Accessories', 'Electronics', 'Electronics',
        'Electronics', 'Electronics', 'Electronics', 'Electronics'
    ],

  'Region': [
        'North', 'South', 'East', 'West', 'North', 'South',
        'East', 'West', 'North', 'South', 'East', 'West',
        'North', 'South', 'East', 'West', 'North', 'South',
        'East', 'West'
    ],
    'Quantity': [
        5, 12, 7, 6, 15, 8, 10, 20, 9, 14,
        7, 11, 18, 25, 10, 8, 16, 12, 20, 15
    ],
    'Unit_Price': [
        60000, 25000, 62000, 30000, 27000, 65000,
        32000, 5000, 68000, 28000, 31000, 70000,
        30000, 4500, 72000, 33000, 29000, 75000,
        31000, 78000
    ],
    'Sales': [
        300000, 300000, 434000, 180000, 405000, 520000,
        320000, 100000, 612000, 392000, 217000, 770000,
        540000, 112500, 720000, 264000, 464000, 900000,
        620000, 1170000
    ],


'Profit': [
        60000, 45000, 85000, 27000, 65000, 90000,
        48000, 20000, 110000, 60000, 35000, 130000,
        85000, 25000, 120000, 40000, 70000, 150000,
        95000, 190000
    ],
    'Advertising': [
        20000, 18000, 25000, 12000, 22000, 28000,
        16000, 8000, 30000, 20000, 14000, 35000,
        26000, 10000, 32000, 15000, 24000, 40000,
        30000, 45000
    ]
}

df = pd.DataFrame(data)
df




```
# Colab Link:
https://colab.research.google.com/drive/1akk2IR-UaG2HQCPmZACV2w2Dp--q5tNj?usp=sharing
# Coding and Output:
<img width="482" height="361" alt="image" src="https://github.com/user-attachments/assets/96f7e8b1-237c-4493-89cf-c1ca5b348982" />

<img width="439" height="334" alt="image" src="https://github.com/user-attachments/assets/ba94095a-6d86-46e8-afcb-596b4568f1ce" />

<img width="410" height="325" alt="image" src="https://github.com/user-attachments/assets/edf0418b-7cad-4acb-bff7-1f8fc78c3b89" />


<img width="446" height="322" alt="image" src="https://github.com/user-attachments/assets/3b81aac7-7e7e-4a72-8dea-ccf466078334" />

<img width="362" height="325" alt="image" src="https://github.com/user-attachments/assets/87f15b48-072b-4dbe-b5fc-b0c579665fc0" />


<img width="397" height="348" alt="image" src="https://github.com/user-attachments/assets/f6ddf5a4-7a9e-4f7c-9181-4906f8b57a3d" />

<img width="372" height="340" alt="image" src="https://github.com/user-attachments/assets/f4b63e09-9e3e-4e97-be2e-912c549a46e9" />

<img width="365" height="316" alt="image" src="https://github.com/user-attachments/assets/21a7799f-5ca7-465f-8c02-e37c1441a294" />

<img width="364" height="334" alt="image" src="https://github.com/user-attachments/assets/9f943970-4ecb-47e4-bb08-b637e90f6cef" />

<img width="362" height="320" alt="image" src="https://github.com/user-attachments/assets/6c29342d-2754-424a-9438-ba08478b2f54" />


<img width="388" height="330" alt="image" src="https://github.com/user-attachments/assets/1c34cd03-d077-4d74-9973-be477cd9020c" />


<img width="341" height="323" alt="image" src="https://github.com/user-attachments/assets/8952d44d-96cf-4813-acca-672e734f16a9" />


<img width="467" height="361" alt="image" src="https://github.com/user-attachments/assets/e003582b-52b4-4e35-a499-3cc33aaede40" />


<img width="464" height="356" alt="image" src="https://github.com/user-attachments/assets/45419d64-7333-4928-8c56-71c06b6df614" />

<img width="478" height="262" alt="image" src="https://github.com/user-attachments/assets/b9d53f7c-5dc8-4231-ba9d-213425b41780" />


<img width="462" height="259" alt="image" src="https://github.com/user-attachments/assets/c75680b0-4a03-4634-b24b-72e013f669d2" />

<img width="520" height="276" alt="image" src="https://github.com/user-attachments/assets/47d1a9ea-16ef-4682-a7f1-2b9b03a9cf74" />

<img width="380" height="335" alt="image" src="https://github.com/user-attachments/assets/f52ad0f0-efc5-47bc-b1f9-18fa04c2ff78" />


<img width="466" height="323" alt="image" src="https://github.com/user-attachments/assets/904413d1-6fa9-4e23-b1e3-25bb4ccd52d4" />


<img width="430" height="319" alt="image" src="https://github.com/user-attachments/assets/d543fa9d-0efe-4718-b100-da1bf0166e69" />


<img width="455" height="283" alt="image" src="https://github.com/user-attachments/assets/750d26fb-e7d7-451d-837d-ec601e9dfd81" />


<img width="484" height="342" alt="image" src="https://github.com/user-attachments/assets/cb06e22a-9489-4658-8b1c-85d665a331cf" />


<img width="591" height="327" alt="image" src="https://github.com/user-attachments/assets/3dcc8d61-d846-49dc-8ceb-097b0970d450" />


<img width="390" height="284" alt="image" src="https://github.com/user-attachments/assets/698af61d-80c9-4b33-921a-4e6f6b34a43b" />


<img width="400" height="261" alt="image" src="https://github.com/user-attachments/assets/a860e987-1942-47ec-ab11-4ae0ee9f8622" />

<img width="330" height="292" alt="image" src="https://github.com/user-attachments/assets/d419e205-9d6e-46e8-b7a4-ea9019c5366a" />


<img width="407" height="347" alt="image" src="https://github.com/user-attachments/assets/a1814b60-5934-41c0-bcc9-115485c5ca03" />

<img width="350" height="353" alt="image" src="https://github.com/user-attachments/assets/17e90dac-b037-4490-b061-2dbd127ae780" />

<img width="758" height="203" alt="image" src="https://github.com/user-attachments/assets/9d0d712c-fef5-4dc2-9a99-d092f0620f27" />






# Result:
we Successful got the output
