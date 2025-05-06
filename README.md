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

### DEVELOPED BY:MARINO SARISHA T
### REG NO:212223240084

# Coding and Output:
```python
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
x = [1, 2, 3, 4, 5]
y = [3, 6, 2, 7, 1]
plt.plot(x,y,label='line1')
```
![image](https://github.com/user-attachments/assets/16bfa87d-0b06-400a-bc23-332ed3821059)
```python
x1 = [1,2,3]
y1 = [2,4,1]
x2 = [1,2,3]
y2 = [4,1,3]
plt.plot(x1,y1,label='line1')
plt.plot(x2,y2,label='line2')
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two lines on same graph!')
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/4e6214d7-bbb6-4cb1-9923-710acbaf0226)
```python
 import matplotlib.pyplot as plt
 x=[1,2,3,4,5,6]
 y=[2,4,1,5,2,6]
 plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)
 plt.xlabel('x-axis')
 plt.ylabel('y-axis')
```
![image](https://github.com/user-attachments/assets/241d60af-c134-497c-b92b-9ec31d196b03)
```python
 yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
 plt.plot(yield_apples)
```
![image](https://github.com/user-attachments/assets/01ce1734-2323-4363-bd69-0e0040f129ba)
```python
 years=[2010,2011,2012,2013,2014,2015]
 yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
 plt.plot(years,yield_apples)
```
![image](https://github.com/user-attachments/assets/b4d918af-d7e8-479d-9a20-81f94f465e39)
```python
 years=range(2000,2012)
 apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
 oranges=[0.926,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896, ]
 plt.plot(years, apples)
 plt.plot(years, oranges)
 plt.xlabel('Year')
 plt.ylabel('Yield (tons per hectare)')
 plt.title('Crop Yields in Kanto')
 plt.legend(['Apples','Oranges']);
```
![image](https://github.com/user-attachments/assets/05c02878-fb84-4666-8808-b32aa5c7465f)
```python
 plt.figure(figsize=(12,6))
 plt.plot(years,oranges,marker='o')
 plt.title("Yield of Oranges (tons per hectare)");
```
![image](https://github.com/user-attachments/assets/2c8ca107-3bbc-46d3-9d46-ea10fb4e370f)
```python
 import matplotlib.pyplot as plt
 import numpy as np
 import pandas as pd
 x=np.arange(0,10)
 y=np.arange(11,21)
 x
```
![image](https://github.com/user-attachments/assets/1de3245e-8e9a-4b95-a8e9-c1585d0a8830)
```python
y
```
![image](https://github.com/user-attachments/assets/61e07188-e648-4cc7-b105-ef8b21f2b132)
```python
 plt.scatter(x,y,c='r')
 plt.xlabel('X-axis')
 plt.ylabel('Y-axis')
 plt.title('Graph in 2D')
 plt.savefig('Test.png')
 ```
![image](https://github.com/user-attachments/assets/1bfb037f-56c8-4154-8fb0-8650f2abcbd0)
```python
 y=x*x
 y
 ```
![image](https://github.com/user-attachments/assets/699d9b60-ef27-4d1d-a32f-9dc555ec861b)
```python
 plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
 plt.xlabel('X axis')
 plt.ylabel('Y axis')
 plt.title('2d Diagram')
 plt.legend(['y-values']);
 ```
![image](https://github.com/user-attachments/assets/23713c18-095b-403e-9c60-d21a75dfa3b7)
```python
 x=np.arange(0,4*np.pi,0.1)
 y=np.sin(x)
 plt.title("sine wave form")
 plt.plot(x,y)
 plt.show()
 ```
![image](https://github.com/user-attachments/assets/1ec8e10f-620f-47c3-b786-e25c47aeef61)
```python
 import matplotlib.pyplot as plt
 import numpy as np
 x=[1,2,3,4,5]
 y1=[10,12,14,16,18]
 y2=[5,7,9,11,13]
 y3=[2,4,6,8,10]
 plt.fill_between(x,y1,color='blue')
 plt.fill_between(x,y2,color='green')
 ```
![image](https://github.com/user-attachments/assets/5f8e324b-fd22-4544-a03d-b123b233708e)
```python
 import matplotlib.pyplot as plt
 import numpy as np
 x=[1,2,3,4,5]
 y1=[10,12,14,16,18]
 y2=[5,7,9,11,13]
 y3=[2,4,6,8,10]
 plt.fill_between(x,y1,color='blue')
 plt.fill_between(x,y2,color='green')
 plt.plot(x,y1,color='red')
 plt.plot(x,y2,color='black')
 plt.legend(['y1','y2'])
 plt.show()
 ```
![image](https://github.com/user-attachments/assets/965145c7-c3de-4cbc-a465-d7a482206747)
```python
 import matplotlib.pyplot as plt
 height=[10,24,36,40,5]
 names=['one','two','three','four','five']
 c1=['red','green']
 c2=['b','g']
 plt.bar(names,height,width=0.8,color=c1)
 plt.xlabel('x-axis')
 plt.ylabel('y-axis')
 plt.title('My bar chart!')
 plt.show()
 ```
![image](https://github.com/user-attachments/assets/10e96361-1e39-4813-8c45-553ffdcd13eb)
```python
 x=[2,8,10]
 y=[11,16,9]
 x2=[3,9,11]
 y2=[6,15,7]
 plt.bar(x,y,color='r')
 plt.bar(x2,y2,color='g')
 plt.title('Bar graph')
 plt.ylabel('Y axis')
 plt.xlabel('X axis')
 plt.show()
 ```
![image](https://github.com/user-attachments/assets/46f55fe9-e235-405a-b7b3-8b23ec885db4)
```python
 import matplotlib.pyplot as plt
 ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
 range=(0,100)
 bins=10
 plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
 plt.xlabel('age')
 plt.ylabel('No. of people')
 plt.title('My histogram')
 plt.show()
 ```
![image](https://github.com/user-attachments/assets/53c553a7-bc37-41fa-864c-c6c9275070ba)
```python
 import matplotlib.pyplot as plt
 import numpy as np
 np.random.seed(0)
 data=np.random.normal(loc=0,scale=1,size=100)
 data
 ```
![image](https://github.com/user-attachments/assets/ac1ef45d-fb7c-42b1-abd5-0bc0daf0ee20)
```python
 fig,ax=plt.subplots()
 ax.boxplot(data)
 ax.set_xlabel('Data')
 ax.set_ylabel('Values')
 ax.set_title('Box Plot')
 ```
![image](https://github.com/user-attachments/assets/73ce16a8-6c9a-41f6-8b9c-26f7aef74312)
```python
 labels='Python','C++','Ruby','Java'
 sizes=[215,130,245,210]
 colors=['gold','yellowgreen','lightcoral','lightskyblue']
 explode=(0,0.4,0,0.5)
 plt.pie(sizes,explode=explode,labels=labels,colors=colors,autopct='%1.1f%%',shadow=True)
 plt.axis('equal')
 plt.show()
 ```
![image](https://github.com/user-attachments/assets/71295b82-5f25-4a6c-90c6-a2d71d51ce6b)
```python
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode=(0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
plt.legend()
```
![image](https://github.com/user-attachments/assets/f9f00fec-aa9d-4e0f-8088-99c97cce1f16)

# Result:
Thus the program to Perform Data Visualization using matplot python library is done successfully.
