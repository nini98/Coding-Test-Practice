#python3

N = int(input())

first = 666
count = 0

while(count != N):
    if str(first).count('666') >= 1:
        count += 1
    first += 1
    

print(first-1)
