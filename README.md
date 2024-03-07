### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE: 
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
EMPLOYEE DATA
![image](https://github.com/Ashwinkumar26/WDM_EXP1/assets/145831269/f2b559e3-a705-4fe9-a2d9-f4879e003c46)
WEATHER DATA
![image](https://github.com/Ashwinkumar26/WDM_EXP1/assets/145831269/69dd0e1c-4587-4b63-a4d6-28b97bb463ce)


PREPROCESSING
Procedure:
1) Add -> Pre-Processing Technique:
Start -> Programs -> Weka-3-4 -> Weka-3-4
Click on explorer.
Click on open file.
Select Weather.arff file and click on open.
Click on Choose button and select the Filters option.
In Filters, we have Supervised and Unsupervised data.
Click on Unsupervised data.
Select the attribute Add.
A new window is opened.
In that we enter attribute index, type, data format, nominal label values for Climate.
Click on OK.
Press the Apply button, then a new attribute is added to the Weather Table.
Save the file.
Click on the Edit button, it shows a new Weather Table on Weka.
### OUTPUT:
![image](https://github.com/Ashwinkumar26/WDM_EXP1/assets/145831269/2606761f-685b-41a3-92a6-3deec88381e4)


2) Remove -> Pre-Processing Technique:
Start -> Programs -> Weka-3-4 -> Weka-3-4
Click on explorer.
Click on open file.
Select Weather.arff file and click on open.
Click on Choose button and select the Filters option.
In Filters, we have Supervised and Unsupervised data.
Click on Unsupervised data.
Select the attribute Remove.
Select the attributes windy, play to Remove.
Click Remove button and then Save.
Click on the Edit button, it shows a new Weather Table on Weka.
### OUTPUT:
![image](https://github.com/Ashwinkumar26/WDM_EXP1/assets/145831269/656f8d8e-6880-4e20-be59-bfb33d14b992)


Normalize -> Pre-Processing Technique:
Start -> Programs -> Weka-3-4 -> Weka-3-4
Click on explorer.
Click on open file.
Select Weather.arff file and click on open.
Click on Choose button and select the Filters option.
In Filters, we have Supervised and Unsupervised data.
Click on Unsupervised data.
Select the attribute Normalize.
Select the attributes temparature, humidity to Normalize.
Click on Apply button and then Save.
Click on the Edit button, it shows a new Weather Table with normalized values on Weka.
### OUTPUT:
![image](https://github.com/Ashwinkumar26/WDM_EXP1/assets/145831269/8ab2c752-42b0-4236-9c67-d6c5e80578ab)


RESULT:
Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
