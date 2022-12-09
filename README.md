# Produced by Ali Hashemian Nejad
import random
path = "C:/Users/Ali/Desktop/password.txt"
f = open(path, "a")
l_w = "abcdefghijklmnompqrstwzyx"
u_w = l_w.upper()
n = "0123456789"
s = "!@#$%^&*()_ +=|\/><*`~.,';:[]}{-"
ch = l_w + u_w + n + s
password = "".join(random.sample (ch , 8))
for i in range(1):
    f.write("".join(random.sample (ch , 8)) + "\n")
