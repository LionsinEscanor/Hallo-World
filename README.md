# Hallo-World
My first project with python ;)
iam new here and i would love to learn how to code with python, not just for meself but for my work as well.
Thanks a lot for this "easy" way to learn sth new.
# Program to check Armstrong number in a certain interval
lower = 101
upper = 3000
for num in range(lower, upper +1):
# oder of number
oder = len(str(num))
# initialize sum
sum = 0
temp = num
while temp >0:
digit = temp % 10
sum += digit ** oder
temp //= 10
if num == sum:
print(num)
