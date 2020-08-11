# python
name=input("enter num you wanna see the sum of:  ")
total=0
count=len(name)
for i in range(count):
    total+=int(name[i])
print(f"Here's the sum of strings:  {total}")
