# Assignment-1
to find upper case and lower case letters in a given string

s=input('input te text:')
u=0
l=0
for i in s:
    if i.isupper ():
        u=u+1
    elif i.islower():
        l=l+1
print('the number of upper case letter {} and the number of lower case letter{}:', format(u,l)
