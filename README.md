# PYTHON
my_dict={"Nairobi": 35.5, "Kakamega": 32.6,"Nakuru": 31.8, "Muranga": 29.7}
print(my_dict)
for key in my_dict:
    print(key)
for value in my_dict.values():
    print(value)
for key,value in my_dict.items():
    print(key,value)

my_dict2={key:value*9/5+32 for key,value in my_dict.items()}
print(my_dict2)
