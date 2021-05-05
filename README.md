# Bracket-sequences
Python Programming

s=str(input())
c=0
l=0

for i in range(0,len(s)):
    if (s[i]=='('):
        c=c+1

for i in range(0,len(s)):
    if (s[i]==')'):
        l=l+1

if(c==l):
    m=int (len(s)/2)
    print(m)
else:
    print("Error")
