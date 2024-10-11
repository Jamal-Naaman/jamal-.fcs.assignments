assignmnet 2 
# Question  1
list1 = [54, 76, 2, 4, 98, 100]

# Take two integer inputs
int1 = int(input("Enter the first integer: "))
int2 = int(input("Enter the second integer: "))

for number in list1:
    if int1 <= number <= int2:
        print(number)

#Question 2 
 def print_names():
names = ["maria" , "hala " , "ghady" , "ehsan " , "joe " , "zoe" ]

letter = "a"
for name in names :
      if letter in name :
          print(name)


# Question 3
numbers = [-12, 4, 12, 25, 67]

while True:
    num = int(input("Enter a number (or -99 to stop): "))
    
    if num == -99:
        break
    
   numbers.append(num)
   numbers.sort() 
    
    print("Updated list:", numbers)


# Question 4 
words = "Is this the real life? Is this just fantasy? Caught in a landslide, no escape from reality Open your eyes, look up to the skies and see I'm just a poor boy, I need no sympathy Because I'm easy come, easy go, little high, little low Any way the wind blows doesn't really matter to me, to me Mama, just killed a man Put a gun against his head, pulled my trigger, now he's dead Mama, life had just begun But now I've gone and thrown it all away Mama, ooh, didn't mean to make you cry If I'm not back again this time tomorrow Carry on, carry on as if nothing really matters Too late, my time has come Sends shivers down my spine, body's aching all the time Goodbye, everybody, I've got to go Gotta leave you all behind and face the truth Mama, ooh (any way the wind blows) I don't wanna die I sometimes wish I'd never been born at all I see a little silhouetto of a man Scaramouche, Scaramouche, will you do the Fandango? Thunderbolt and lightning, very, very frightening me (Galileo) Galileo, (Galileo) Galileo, Galileo Figaro, magnifico But I'm just a poor boy, nobody loves me He's just a poor boy from a poor family Spare him his life from this monstrosity."

words = words.split()

int1 = int(input("Enter the first integer: "))
int2 = int(input("Enter the second integer: "))
if 0 <= int1 <= int2 <= len(words):

    print(" ".join(words[int1:int2+1]))
else:
    print("Invalid input. Please enter two valid integers.")


