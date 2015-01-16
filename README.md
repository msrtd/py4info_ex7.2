# py4info_ex7.2
Python for Informatics, Ex. 7.2

Author, msrt

if len(fname) == 0:
    fname = 'mbox-short.txt'
fhand = open(fname)
for line in fhand:
    line = line.rstrip().upper()
    print line
