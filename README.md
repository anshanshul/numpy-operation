# numpy-operation

import numpy as nup
list1=[1,2,3],[2,5,8],[4,5,8]
list2=[2,4,5],[4,5,9],[8,7,9]
arr1=nup.array(list1)
print(arr1)
print(type(arr1))
arr2=nup.array(list2)
print(arr2)
print(type(arr2))
print(arr1[0])
print(arr2[0][0])
list3=[[2,4,9],[4,5,9],[4,5,7]]
arr3=nup.array(list3)
print(arr1+arr3)
"""
arr4=[2,4,6]
print(2*2)    #mathematical operation
print(arr4*arr1)  #direct multiplication
print(arr4*arr2)  #mathematical multiplication of two different
div =arr1%2==0
arr3=nup.array(div) #conertng into bool type array
print(arr3)
"""
arr4=nup.array([arr1,arr2,arr3])
print("-------",arr4)
print(arr4[0,1])
print(arr4[:,2])
print(arr4[2,:])
arr4[:,2]=[0,0,1]
print(arr4)
arr5=nup.zeros(6,nup.int)
print(arr5)#default type is float
print(nup.ones(6,nup.int))
print(nup.arange(6))# used for array with elements in 
arr5 =arr3.copy()#deep copy -no link b\w
print(arr5)
arr5[0]--2

arr3[1]--20
print("After--deep",arr3)
print("After--deep",arr5)
arr6=arr2.view()# shallow copy there is copy or same memory 
print("-before-shallow",arr6)
print("-before-shallow",arr2)
arr2[1]-50
print("After--shallow",arr6)
print("After--shallow",arr2)
arr7 = nup.array([[1,2],[2,4],[5,6]])
arr8=nup.array([1,2])
arr9=arr7+arr8
print(arr9)
arr10= nup.array([[50,60],[1,2],[65,68,]])
print(arr10.min())
print(arr10.max())
print(nup.mean(arr10))
print(nup.median(arr10))
print(nup.cov(arr10))
print(arr10.std())
print(nup.corrcoef(arr10))
list5=[0,1,2]
print(arr7[list5])
div=arr7%2==0
print(arr7[div])
print(arr7.sum())
print(arr7*arr8)



                      
