# CS2660-lab08
Part II
The purpose of this program is to crack hashed passwords in the catamount community bank using a dictionary attack. The program uses the hashlib module and reads inn a list of passwords stored in the passwd file. It checks for common words used as passwords and then outputs the username and password if it is cracked.
Part III
The modifications made to the two files are as listed: I modified the hash_pw function to include a salt for each password which is created by using the os.random(40) which creates a unique salt for each password. I then modified the bank.py app to support the authenticate function in password_crack.py Finally I also updated the passwd file in the instance/static folder which now contains the salted and hashed passwords.
