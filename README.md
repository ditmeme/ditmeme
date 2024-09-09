- 👋 Hi, I’m @ditmeme
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
ditmeme/ditmeme is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import sys
import random 
playerchoose = int(input("enter...\n1 for rock,\n2 for paper, \n3 for Scissors:\n\n"))

player = int(playerchoose)
if player  < 1 or player > 3 :
    sys.exit ("pls chosoe 1 2 3")
  

computerchoice = random.choice("123")

computer = int(computerchoice)
print("")
print("you chose" + str(player) + ".")
print("python chose" + str(computer) + ".")
print("")

if player == 1 and computer ==3 :
    print("you win")
if player == 2 and computer ==1 :
    print("you win")    
if player == 3 and computer ==2 :
    print("you win")
if player == computer :
    print("draw")    
else:
    print("idiot")
