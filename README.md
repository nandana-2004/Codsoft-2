#PASSWARD

import random
a = 'ABCDEFGHIJKLMNOPQRSTUVWXYZ'
b = 'abcdefghijklmnopqrstuvwxyz'
x = '0123456789'
s = '!@#$^_()[]{}/'
all = a + b + x + s
length = int(input('enter a number : '))
password= "".join(random.sample(all,length))
print('The Generated Password is',password)
