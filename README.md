s1="Abc"
s2="Xyz"
result=""
while i<len(s1) or j<len(s2):
    result=result+s1[i]+s2[i]
    i=i+1
    j=j+1
print(result)
