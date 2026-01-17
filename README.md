Gryffindor = 0
Ravenclaw = 0
Hufflepuff = 0
Slytherin = 0




answer = int(input("Q1)Do you like Dawn or Dusk ?\n1) Dawn\n2) Dusk      answer : "))
if answer == 1:
  print('+1 Ravenclaw')
  Ravenclaw += 1
elif answer == 2:
  print('+1 Slytherin')
  Slytherin += 1
else:
  print("Wrong input.")

answer = int(input('Q2) When Im dead, I want people to remember me as:\n1)The Good\n2)The Great\n3)The Wise\n4)The Bold     answer : '))
if answer == 1:
  print('+2 Hufflepuff')
  Hufflepuff += 2
elif answer == 2:
  print('+2 Slytherin')
  Slytherin += 2
elif answer == 3:
  print('+2 Ravenclaw')
  Ravenclaw += 2
elif answer == 4:
 print('+2 Gryffindor')
 Gryffindor += 2
else :
  print ("Wrong input.")

answer = int(input('Q3) Which kind of instrument most pleases your ear ?\n1) The violin\n2) The trumpet\n3) The piano\n4) The drum     answer :'))
if answer == 1 :
 print('+4 Slytherin')
 Slytherin += 4
elif answer == 2 :
  print('+4 Hufflepuff')
  Hufflepuff += 4
elif answer == 3: 
  print('+4 Ravenclaw')
  Ravenclaw += 4
elif answer == 4:
  print('+4 Gryffindor')
  Gryffindor += 4
else :
  print ('Wrong input.')


print ('Gryffindor:' , Gryffindor)
print ('Slytherin:' , Slytherin)
print ('Hufflepuff' , Hufflepuff)
print ('Ravenclaw' , Ravenclaw)
