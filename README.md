# Basic_python_programs
#Task1 Printing the numeric datatype
dt_num=100
print("Task1 output values is:")
print(dt_num)
print(type(dt_num))

#Task2 printing the decimal data type
dt_dec=199.99
print("Task2 output values is")
print(dt_dec)
print(type(dt_dec))

#Task3 printing the string and doing operation 
dt_txt="I Am Elavarasan R From Salem, Pursuing My PG Degree At Bharathiar University"
print("Task3 output values is")
print(dt_txt.upper())
print(dt_txt.lower())
print(dt_txt.index("Salem"))
print(dt_txt.endswith("University"))
print(dt_txt.find('Bharathiar'))
print(dt_txt.replace('Salem','Coimbatore'))

#Task4
ts_marks= 67+56+76+88+25
print("Average of the marks :",ts_marks/5)
print("datatype of average marks")
print(type(ts_marks))
print("Converting the decimal value into integer")
print(int(ts_marks))
print(type(ts_marks))

#Task5
my_profile=[10,"Elavarasan","Ramesh","Male",7,"Indian"]
print(my_profile)
print(len(my_profile))
my_profile.append('Salem')
my_profile.extend("TAMIL")
print(my_profile)
print(len(my_profile))
my_profile.pop()
my_profile.extend(["Salem","636351"])
print(my_profile)
del(my_profile[5])
print(my_profile)
my_profile1=["BCA","MSc"]
print(my_profile1)
print(my_profile+my_profile1)
print(my_profile1+my_profile)
"Elavarasan" in my_profile

#Task6
my_data=("Elavarasn","Ramesh","Tamil",7,(8,9))
print(len(my_data))
print(my_data.count(7))
print(my_data.index("Tamil"))
print(my_data)
print(my_data[0])
print(my_data[4])
print(my_data[1:2])
print(my_data[4:6])
print(my_data[1][5])

#Task7
wt_corpa={'Morning':'mrng','Good':'gud','Night':'ni8','Okay':'ok','Sorry':'sry'}
print(wt_corpa.keys())
wt_corpa.pop('Sorry')
print(wt_corpa.get("Morning"))
print(wt_corpa.values())
wt_corpa['Thank You']='Tq'
print(wt_corpa)
del(wt_corpa['Night'])
wt_corpa
