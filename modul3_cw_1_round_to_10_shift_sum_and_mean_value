numbers = [5,32,56,2,2,16,7,10,23,100]
mean_number = 0
index = 0

import math

for i in numbers:
  shifted = (i/10**(len(str(i))))
  lenght = (len(str(i)))
  #print (shifted)
  if lenght > 1:
    print ((round((shifted*10**(lenght-1))))*10)
    numbers[index] = round((shifted*10**(lenght-1)))*10
  else:
    print (10)
    numbers[index]=10
  index = index + 1

sortedlist = sorted(numbers)

sum=0

for i in sortedlist[1:-1]:
  sum += i
  #print (sum)
mean = sum / (len(sortedlist[1:-1]))

print (mean)
#print(sortedlist[1:-1])
#print (numbers[1:-1])
  #print (round(shifted))
