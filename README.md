import random


num = random.randint(1,100)
answer = 0
count = 0
while answer != num and count<3:
    answer = int(input())
   # print('answer:',type(answer),repr(answer))
    if answer < num:
        print('too small')
    if answer > num:
        print('too big')
    if answer == num:
        print('BINGO!')
    count += 1
    print(answer,num,count)
