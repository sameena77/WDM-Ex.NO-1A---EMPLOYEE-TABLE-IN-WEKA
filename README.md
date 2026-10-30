# WDM-Ex.NO-1---EMPLOYEE-TABLE-IN-WEKA
## Name: Sameena J
## Reg.no: 2305002019
Aim:
To Create an Employee Table with the help of Data Mining Tool WEKA.
Description:
We need to create an Employee Table with training data set which includes attributes like name, id, salary, experience, gender, phone number.
Procedure:
Steps:
1)	Open Start  Programs  Accessories  Notepad
2)	Type the following training data set with the help of Notepad for Employee Table.

```
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


```

3)	After that the file is saved with .arff file format.
4)	Minimize the arff file and then open Start  Programs  weka-3-4.
5)	Click on weka-3-4, then Weka dialog box is displayed on the screen.
6)	In that dialog box there are four modes, click on explorer.
7)	Explorer shows many options. In that click on ‘open file’ and select the arff file
8)	Click on edit button which shows employee table on weka.
 
Training Data Set  Employee Table

<img width="1222" height="737" alt="image" src="https://github.com/user-attachments/assets/651db5b8-15da-41dd-8a59-1b8886557aa2" />



 
Output:
<img width="1917" height="1078" alt="image" src="https://github.com/user-attachments/assets/20a92010-9334-4b66-a8bf-b6761b9e05f6" />
































Result:
Thus the employee table has been created successfully using Weka Tool.
