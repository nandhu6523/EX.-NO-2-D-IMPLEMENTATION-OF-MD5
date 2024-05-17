# EX.-NO-2-D-IMPLEMENTATION-OF-MD5

## AIM:
  To write a program to implement the MD5 hashing technique.
## ALGORITHM:
  
  STEP-1: Read the 128-bit plain text.
  
  STEP-2: Divide into four blocks of 32-bits named as A, B, C and D.
  
  STEP-3: Compute the functions f, g, h and i with operations such as, rotations, permutations, etc,.
  
  STEP-4: The output of these functions are combined together as F and performed circular shifting and then given to key round.
  
  STEP-5: Finally, right shift of ‘s’ times are performed and the results are combined together to produce the final output.
  
## PROGRAM:
```# importing the required libraries
import hashlib
# making a message
inputstring = input("Enter the input message:")
# encoding the message using the library function
output = hashlib.md5(inputstring.encode())
# printing the hash function
print("Hash of the input string:")
print(output.hexdigest())
```


## OUTPUT:
![Screenshot 2024-05-17 104419](https://github.com/nandhu6523/EX.-NO-2-D-IMPLEMENTATION-OF-MD5/assets/123856724/6e197a8e-6eb5-4cf6-bae7-322c78f8ccfe)


## RESULT:
  Thus the implementation of MD5 hashing algorithm had been implemented successfully using C.
