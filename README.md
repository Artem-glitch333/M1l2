import random
symbols = "567853647858988" 
pasword = '' 
count = int(input('длина пароля:')) 

for i in range(count): 
    pasword += random.choice(symbols) 

print(pasword)
