# Password Generator.

import random
import string


print("Welcome to the Pypassword Generator!")
l = input("How many alphabet would you like in your password? \n")
s = input("How many symbols would you like? \n")
n = input("How many numbers would you like? \n")

length = int(l) + int(s) + int(n)


letters = string.ascii_letters
l = random.choice(letters)


symbols = string.punctuation
s = random.choice(symbols)

numbers = string.digits
n = random.choice(numbers)

combined = letters + symbols + numbers



password = ''.join(random.choices(combined, k = length))

print(f"Here is your Password : {password}")
