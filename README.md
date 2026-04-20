### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE: 20/04/2026
### AIM: 
  To Create Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform preprocessing
### PROCEDURE: 
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Employee Table.

```
--------------
Employee Data
---------------
@relation employee
@attribute name {x,y,z,a,b}
@attribute id numeric
@attribute salary {low,medium,high}
@attribute exp numeric
@attribute gender {male,female}
@attribute phone numeric
@data
x,101,low,2,male,250311
y,102,high,3,female,251665
z,103,medium,1,male,240238
a,104,low,5,female,200200
b,105,high,2,male,240240

--------------
Weather Data
---------------
@relation weather
@attribute outlook {sunny,rainy,overcast}
@attribute temparature numeric
@attribute humidity numeric
@attribute windy {true,false}
@attribute play {yes,no}
@data
sunny,85.0,85.0,false,no
overcast,80.0,90.0,true,no
sunny,83.0,86.0,false,yes
rainy,70.0,86.0,false,yes
rainy,68.0,80.0,false,yes
rainy,65.0,70.0,true,no
overcast,64.0,65.0,false,yes
sunny,72.0,95.0,true,no
sunny,69.0,70.0,false,yes
rainy,75.0,80.0,false,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows employee table on weka.

### OUTPUT:
# Employee Data
<img width="1234" height="742" alt="356801394-ac0d28dc-ce93-4024-8fb5-e62eb710fe1a" src="https://github.com/user-attachments/assets/4c5b228f-d5ec-4fcc-a14f-a45eac4daef8" />


# Weather Data
<img width="1220" height="733" alt="356801336-a25e2658-78db-4cf6-a4c0-d2cb30582909" src="https://github.com/user-attachments/assets/d45423d5-b768-4df6-b327-e6a5e5d02495" />




### PREPROCESSING
### Procedure:
#### 1) Add -> Pre-Processing Technique:
1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Add.
9) A new window is opened.
10) In that we enter attribute index, type, data format, nominal label values for Climate.
11) Click on OK.
12) Press the Apply button, then a new attribute is added to the Weather Table.
13) Save the file.
14) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:

# Employee Data
<img width="1233" height="746" alt="356801462-fc09e7cd-4310-4765-9096-e859df116b5e" src="https://github.com/user-attachments/assets/128d545f-5a19-4325-888e-544b92cd859a" />

# Weather Data
<img width="1230" height="749" alt="356801484-43fac1bb-cc62-4570-8b26-e89d0fa04f58" src="https://github.com/user-attachments/assets/fb0079bf-6533-4321-a092-e05305d1a958" />



### 2) Remove -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Remove.
9) Select the attributes windy, play to Remove.
10) Click Remove button and then Save.
11) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
# Employee Data
<img width="1234" height="742" alt="356801554-8374cb22-3889-4577-86fe-734cebe87dc8" src="https://github.com/user-attachments/assets/8ce3eb52-af77-4ac5-a35f-76cab25547fd" />

# Weather Data
<img width="1234" height="742" alt="356801582-1cf9813b-e34f-4324-a146-db876ebd622f" src="https://github.com/user-attachments/assets/4888e507-d917-457f-b3e9-776306b45418" />


### Normalize -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Normalize.
9) Select the attributes temparature, humidity to Normalize.
10) Click on Apply button and then Save.
11) Click on the Edit button, it shows a new Weather Table with normalized values on Weka.

### OUTPUT:

# Employee Data
<img width="1234" height="742" alt="356801641-00b4faf0-2851-4813-9e00-5cdc8f86da40" src="https://github.com/user-attachments/assets/ed18c158-d36d-4f1a-af84-4d5a038606c4" />

# Weather Data
<img width="1234" height="742" alt="356801691-c6f76358-a79d-4772-9db5-9e4d10f626d7" src="https://github.com/user-attachments/assets/d7144bbf-75e8-47ff-8115-a74e8e469f77" />



### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
