fobj = open("resume.txt","r") #openeing a file which already exist.
content = fobj.read() #reading that file.
fobj.close() #closing that file.

visited="" #this will skip those letters who were already visited byt he interpreter.

for con in content: #for loop to read all the contents.
    count=0 # declared a counter
    if con in visited:
        continue # if the letter is already taken the continue.
    else:
        visited = visited + con #if not then store it in variable.
        
    for ch in content:
        if con == ch: #if given letter is taken.
            count=count+1 # then increment it by 1.
    
    print(con, "=" ,count)
    
print("visited string: ",visited)

OR

import collections 
import pprint
with open("resume.txt", 'r') as info:
  count = collections.Counter(info.read().upper())
  value = pprint.pformat(count)
print(value)
