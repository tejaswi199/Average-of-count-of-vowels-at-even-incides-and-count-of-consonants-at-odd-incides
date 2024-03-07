s=input()
v="AEIOUaeiou"
vc=0 
cc=0 
for i in range(len(s)):
  if i%2==0:
    if s[i] in v:
      vc=vc+1 
  else:
    if s[i] not in v:
      cc=cc+1 
print((cc+vc)/2)
      

