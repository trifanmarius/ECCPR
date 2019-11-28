zaruri = int(raw_input())
l = []
cl = []
count = 0
for i in range(zaruri):
    a = int(raw_input())
    l.append(a)
for j in range(1,7):
    for k in l:
        if j==k:
            count += 1        
    cl.append(count)
    count = 0
if max(cl) - min(cl) <= 10*zaruri/100:
    print(0)
else:
    print(1)
