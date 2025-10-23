# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
 Name: V Rishon Anand
 
 Reg no: 212224240135
 ```
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
```
 # Line Plot:
```
marks=[13,45,63,78]
student=['ABC','QOR','EFB','TOB']
plt.plot(marks,student)
plt.xlabel('Marks')
plt.ylabel('Student name')
plt.show()
```
## Output
<img width="872" height="730" alt="image" src="https://github.com/user-attachments/assets/2cc0ddb2-2cad-4df4-9c15-cef71e66fa70" /> 
```
student=['A','B','C','D']
attendence=[90,85,73,88]
plt.plot(attendence,student)
plt.xlabel('Attendence')
plt.ylabel('Student name')
plt.show()
```
## Output
<img width="887" height="727" alt="image" src="https://github.com/user-attachments/assets/22891235-2dc0-4c1e-ba84-678b7dfd8f3d" />

# Scatter Plot:
```
x=[10,20,30,40,50]
y=[100,200,300,400,500]
plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
plt.show()
```
## Output
<img width="804" height="654" alt="image" src="https://github.com/user-attachments/assets/dcc85fbb-902f-45c4-8e8e-afd1b769ed96" />

```
x=np.arange(0,15)
y=np.arange(0,15)
x
y
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('y axis')
plt.title('Scatter plot')
plt.show()
```
## Output
<img width="807" height="824" alt="image" src="https://github.com/user-attachments/assets/e8bff068-6c3c-42f0-a93b-283c07a466d3" />

# Pie Chart:
```
act=['eat','sleep','work','play']
slices=[3,7,8,6]
color=['r','y','g','b']
plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```
## Output
![Uploading image.png…]()


```
feedback=['Good','excellent','Perfect','Ok']
slices=[4,10,3,8]
color=['y','r','b','g']
plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```
## Output
<img width="1299" height="686" alt="image" src="https://github.com/user-attachments/assets/c7aca915-7c56-4873-a91f-d682813357af" />

# Area Chart:
```
x = [1, 2, 3, 4, 5]
y1 = [10, 12, 14, 16, 18]
y2 = [5, 7, 9, 11, 13]
y3 = [2, 4, 6, 8, 10]
plt.fill_between(x, y1, color='blue')
plt.fill_between(x, y2, color='green')
plt.plot(x, y1, color='red')
plt.plot(x, y2, color='black')
plt.legend(['y1','y2'])
plt.show()
```
## Output
<img width="846" height="793" alt="image" src="https://github.com/user-attachments/assets/41b6a2c7-bfba-4398-8aa3-06aa8fc03334" />

# Bar Chart:
```
height = [10, 24, 36, 40, 5]
names = ['one', 'two', 'three', 'four', 'five']
c1=['red', 'green']
c2=['b', 'g']
plt.bar (names, height, width=0.8, color=c1)
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('My bar chart!')
plt.show()
```
## Output
<img width="804" height="830" alt="image" src="https://github.com/user-attachments/assets/33bfbf9c-8c2a-426f-bb7e-9abe6ee10fd1" />

# Histogram:
```
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins = 10, color='blue', alpha=0.5)
plt.show()
```
## Output
<img width="838" height="625" alt="image" src="https://github.com/user-attachments/assets/53a0597e-e632-4ac5-a3a5-32bfef43c748" />

# Box Plot:
```
np.random.seed(0)
data=np.random.normal(loc=0, scale=1, size=100)
data
```
## Output
<img width="933" height="551" alt="image" src="https://github.com/user-attachments/assets/60e322b1-58b5-4db0-9fd5-8465a8eddc50" />

```
fig, ax= plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```
## Output
<img width="846" height="758" alt="image" src="https://github.com/user-attachments/assets/449c7c26-5d50-4e1f-a873-420a1609d15a" />


# Result:
Thus the program is executed successfully.
