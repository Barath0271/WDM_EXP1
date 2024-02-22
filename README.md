### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE: 08/02/2024
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
#### EMPLOYEE DATA
![Screenshot 2024-02-08 020011](https://github.com/Barath0271/WDM_EXP1/assets/135820464/6375462b-57c1-47e0-8da7-092e3017584e)

#### WEATHER DATA
![Screenshot 2024-02-08 020847](https://github.com/Barath0271/WDM_EXP1/assets/135820464/cb590b74-61c1-42aa-9968-34f084c5282f)




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
#### EMPLOYEE DATA
![Screenshot 2024-02-08 023528](https://github.com/Barath0271/WDM_EXP1/assets/135820464/a0428499-1f5e-41f9-b0ad-734dbf3124f8)


#### WEATHER DATA
![Screenshot 2024-02-08 021752](https://github.com/Barath0271/WDM_EXP1/assets/135820464/1a6f84eb-ab21-4e5f-90c0-dc57b678b044)

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
#### EMPLOYEE DATA
![Screenshot 2024-02-08 023709](https://github.com/Barath0271/WDM_EXP1/assets/135820464/a4386712-ba98-4856-b74d-ede4dd069ed8)


#### WEATHER DATA
![Screenshot 2024-02-22 144614](https://github.com/Barath0271/WDM_EXP1/assets/135820464/1c1e98fa-4836-440a-86f6-0fdaa28b3c40)

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
#### EMPLOYEE DATA
![Screenshot 2024-02-08 023834](https://github.com/Barath0271/WDM_EXP1/assets/135820464/268f75d1-62c2-41a4-a429-23cc02d8af8e)

#### WEATHER DATA
![Screenshot 2024-02-08 022912](https://github.com/Barath0271/WDM_EXP1/assets/135820464/9a3862fe-d091-4e65-82b7-23be8641d729)

### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
