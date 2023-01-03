# Day1
a=['kurnool','Ananthapur','Chittoor','East Godavari','Guntur','Kadapa','Krishna','Nellore','Prakasam','Srikakulam','Visakhapatnam','West Godavari','Nandyala','Adoni','Ballary','Raichur','Hyderabad','Warangal','Prodduturu','Uyalawada','Kalyanadurgam','Secunderabad','Yemmiganur','Banavasi','Sathanur','Kosigi','Kottala','Salkapuram','Tungabhadra','Mantralayam']
print(a)
#to find the length of the list
print(len(a))
#we can assign value by using indexing
a[0]='GPCET'
#Append to insert element at end position
a.append('Secunderabad')
print(a)
#insert: to insert element at specified position
a.insert(0,'Ranamandala')
print(a)
#remove:to remove wanted element 
a.remove('hyderabad')
print(a)
#to del element
del a[2]
print(a)
#pop: to remove element from last
a.pop()
print(a)
#pop using index
a.pop(5)
print(a)
