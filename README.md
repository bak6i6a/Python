# Python
How to get binari value of a decimal in python

i want to get the binary of decimal ... from 255 i want to get 11111111,  in the next code i get a prefix 0b11111111 and i want to take away the prefix, how yo make it right, i'm new in python.

print("The decimal value of",dec,"is:")
strdec = str(dec)
strdec = strdec[2:]    #this line, i added strdec[2:] to pass the prefix and to take the 11111111, but it gives me error, how to do it proper?
print(bin(int(strdec)), "in binary.")
