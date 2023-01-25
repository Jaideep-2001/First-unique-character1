# First-unique-character1
todays task 1st problem
c=0
for i in range(len(s)):
    if s.count(s[i])==1:
        c+=1
        return i
        break
 if c==0:
    return -1
