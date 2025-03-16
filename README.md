# Becroud1071
Sum of Consecutive Odd Numbers I
x = int(input())
y = int(input())
if x>y:
    x,y = y,x
count = 0
for i in range(x+1,y):
    if i%2!=0:
        count += i
print(count)
