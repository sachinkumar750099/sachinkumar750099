#program to get fibonacci bw 0 to 50.

lst = [0,1]
cnt = 0
while cnt < 48:
    lst.append(lst[cnt] +lst[cnt+1]) 
    cnt = cnt + 1
print(lst)
