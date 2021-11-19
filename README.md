# matplotlib
import pandas as pd

import numpy as np

import matplotlib.pyplot as plt

# line plot
# histogram 
# barchart
# pichart subplot

#graph
no_of_classes=np.array([9,3,2,3,4,5,6,6,])
no_of_students=np.array([4,2,4,5,2,4,53,2])
plt.plot(no_of_classes,no_of_students)
#%matplotlib inline
#plt.show()

no_of_classes = np.array([1,2,3,4,5,6,7])
no_of_students = np.array([4,9,6,4,10,8,6])
plt.plot(no_of_classes,no_of_students)

no_of_classes=np.array([9,3,2,3,4,5,6,6,])
no_of_students=np.array([4,2,4,5,2,4,5,2])
plt.plot(no_of_classes,no_of_students,c='b',linestyle='--')
plt.xlabel('no_of_classes')
plt.ylabel('no_of_students')
plt.title('data_sheet')
#%matplotlib inline
#plt.show()


#barchart

subject = ['ml','ai','ds','cs','sql']
m1=[34,43,5,6,3]
m2=[3,4,23,12,4]
m3=[38,43,5,43,2]
m4=[6,32,23,11,3]
plt.bar(subject,m3)
plt.bar(subject,m2)
plt.bar(subject,m1)
plt.bar(subject,m4)

plt.bar(subject,m2)

plt.bar(subject,m4)

#pi_chart
a=np.array([23,32,13,12])
mylabel=['ajay','akash','ashok','akansha']
mycolor=['red','black','blue','orange']
plt.pie(a,labels=mylabel,colors=mycolor)

#histogram
a=np.array([43,23,5,34,53])
plt.hist(a)

x=np.random.normal(22,32,4)
plt.hist(x)

