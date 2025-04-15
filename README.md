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
 import matplotlib.pyplot as plt

x_val = [0,1,2,3,4,5]

y_val = [0,1,4,9,16,25]

plt.plot(x_val,y_val)

plt.show()

![Screenshot 2025-04-15 111621](https://github.com/user-attachments/assets/74d85fbc-2de5-44e5-84b1-645f2eb6dd0f)

import matplotlib.pyplot as plt

x = [1,2,3]

y = [2,4,1]

plt.plot(x,y)

plt.xlabel('x-axis')

plt.ylabel('y-axis')

plt.title('My first graph')

plt.show()

![Screenshot 2025-04-15 111732](https://github.com/user-attachments/assets/8b875a4c-c0d8-46d3-acf4-ea74673a5e5f)

import matplotlib.pyplot as plt

x1 = [1,2,3]

y1 = [2,5,3]

plt.plot(x1,y1,label = 'line 1')

x2 = [1,2,3]

y2 = [3,1,6]

plt.plot(x2,y2,label = 'line 2')

plt.xlabel('x-axis')

plt.ylabel('y-axis')

plt.title("Two lines on the same graph")

plt.legend()

plt.show()

![Screenshot 2025-04-15 111814](https://github.com/user-attachments/assets/03dc6777-57bf-4c73-8e62-c8faee0a3620)

import matplotlib.pyplot as plt

import numpy as np

x = [1,2,3,4,5]

y1 = [10,12,14,16,18]

y2 = [5,7,9,11,13]

y3 = [2,4,6,8,10]

plt.fill_between(x,y1,color = 'blue')

plt.fill_between(x,y2,color = 'orange')

![Screenshot 2025-04-15 111847](https://github.com/user-attachments/assets/7a0e9bac-3684-4507-a7bd-752f8524a650)

plt.stackplot(x,y1,y2,y3,labels = ['line1','line2','line3'])

plt.legend(loc = 'upper left')

plt.title('Stacked line charts')

plt.xlabel('x-axis')

plt.ylabel('y-axis')

plt.show()

![Screenshot 2025-04-15 111926](https://github.com/user-attachments/assets/0c7a1b21-f2e1-476d-ba3f-48edf4b97642)

import numpy as np

import matplotlib.pyplot as plt

val = [2,4,7,3]

names = ['A','B','C','D']

plt.bar(names, val,color = 'purple')

plt.show()

![Screenshot 2025-04-15 112002](https://github.com/user-attachments/assets/08485b7c-72eb-498a-b3df-c1aad92d3048)

import matplotlib.pyplot as plt

import numpy as np

ages = [2,6,4,12,13,12,16,18,18,19,26,24,39,34,45,42,54,56,90,56,86,79]

range = (0,100)

bins = 10

plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)

plt.xlabel('age')

plt.ylabel('no of people')

plt.title('histogram')

plt.show()

![Screenshot 2025-04-15 112057](https://github.com/user-attachments/assets/faf564ba-e56a-43f2-8ca6-e1ada4193447)

import matplotlib.pyplot as plt

import numpy as np

np.random.seed(0)

data=np.random.normal(loc=0,scale=1,size=100)

data

![image](https://github.com/user-attachments/assets/b10129cd-f32a-4827-802e-9a876e868824)

fig,ax=plt.subplots()

ax.boxplot(data)

ax.set_xlabel("data")

ax.set_ylabel("values")

ax.set_title("box plot")

![Screenshot 2025-04-15 112203](https://github.com/user-attachments/assets/1879d721-51b9-4684-b451-fa6776d6f28e)

import matplotlib.pyplot as plt

activities=['eat','sleep','work','play']

slices=[3,7,8,6]

colors=['r','y','g','b']

plt.pie(slices,labels = slices,colors=colors,startangle=90,shadow = True,explode = (0,0,0.1,0),radius=1.2,autopct='%1.1f%%')

plt.legend()

plt.show()

![Screenshot 2025-04-15 112302](https://github.com/user-attachments/assets/ec992aad-37f4-4244-bf46-6553c76b13f2)

# Result:
 Thus the program is executed successfully.
