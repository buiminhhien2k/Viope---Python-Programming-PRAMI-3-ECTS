# -*- coding: cp1252 -*-

handle = open("strings.txt", "r")
content = handle.readlines()
handle.close()

for line in content:
    if(line.replace("\n", "").isalnum()):
        print(line, "was ok.")
    else:
        print(line, "was invalid.")
