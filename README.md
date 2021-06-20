[random_password_generator.txt](https://github.com/jyothi1910/password_generator/files/6681832/random_password_generator.txt)
# password_generator
Password_generator using python
import random 
import string

MAX_LEN = int(input("Enter the length of the input:"))


COMBINED_LIST = string.digits + string.ascii_letters + string.punctuation


temp_pass = random.sample(COMBINED_LIST, MAX_LEN)  


password = ""
for x in temp_pass:
		password = password + x
		
print(password)

