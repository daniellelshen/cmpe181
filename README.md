# CMPE181 Course Work 
CMPE 181 HW Repo For Professor KaiKai's class 
Work completed by Danielle based on Professor Kaikai's class code


## Homework 1: Option1 - Perform IoT data collection
I found myself stuck in Option2 so I also did Option1 

- Option1 files are titled with "my" such as "myCMPE-BigQuery-COVID19"
- I used a different data source from the public BigQuery hosted by Google 
- File that holds the new data source: myCMPE-BigQuery ItalyCOVID.ipynb

### Completed: 
- BigQuery set up 
- Collecting Google Collab and Big Query 
- Connecting a new database (COVID data from Italy [bigquery-public-data:covid19_italy]) 
- ![image](https://user-images.githubusercontent.com/48109463/113222843-b8bcb500-923c-11eb-963e-84185f69ee51.png)
- I was unable to access marketplace so I copied my desired dataset into a dataset in my project 'cmpe181hw1option1'
- ![image](https://user-images.githubusercontent.com/48109463/113222809-a5a9e500-923c-11eb-8095-8f0bde82daa4.png)
- Analyzing data from new database
- Linear Regression model used 

## Homework 1: Option2 - Perform IoT data collection
Homework one files are located in cmpe181/hw1

IoT device (any PC/Mac/Linux/Pi/VM) sending data to Big Query
- Change the IoT data, select your own IoT data
- Get IoT sensor data (e.g., temperature) or dataset from csv/json file

Following instructions from Lecture 10 and Lecture 11 to create Google Cloud Registry and Device and connect the device to recieve data

Comments made in text form in the "181hw1CMPE-GoogleIoTdata.ipynb" file

### Completed: 
- Setting up Google Cloud Console 
- Setting up the Google Client 
- Mount Google Drive 
- Connect Google Cloud storage 
### Uncompleted: 
Unable to complete Option 2 because an error 
"Exceeded maximum backoff time. Giving up."

- error occurs when path is /content/filename
- Unable to figure out how to get the connection to completely pass though

Read comments in "hw1/181hw1CMPE-GoogleIoTdata.ipynb" for further error debugging notes


## Homework 2: Topic 2 - Kaggle Data 
Chose Topic 1, Option 1

### Completed: 
- Setting up Google Colab
- Setting up Kaggle 
- Mount Google Drive 
- access kaggle dataset 
- upzip kaggle dataset 
### Uncompleted: 
- Extracting train.csv 
- testing

The datasets that I chose with kaggle didn't have the train.csv 
