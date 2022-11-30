# PRM-Assigment-1-
Technical Coding Assessment Python
new_list = []
d = {}
list = ['great', 'abc', 'hello','hiyo']
for i in list:
    d[i[-2]]=i
m = sorted(d)
for i in m:
    new_list.append(d[i])
print(new_list)
