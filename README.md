# summer-training
import csv
f=open("size.csv","r")
data=csv.reader(f)
for line in data:
    print(line)
#print(f.read())
#f.write("$$$$$$")
#f.close()
