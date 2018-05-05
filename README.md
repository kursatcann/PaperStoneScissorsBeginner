print("""___Hello You Are Wellcome To RPS Game____
      Please Read The Description For Rules:
      For First Player:_________
      1 means=>Paper,2 means=>Rock,3= Means=>Scissors
      For Second Player:__________
      4 means=>Paper,5 means=>Rock,6= Means=>Scissors
      """)
p1=int(input("What Is player 1's request \n\n\n\n"))
p2=int(input("What Is player 2's request \n\n\n\n"))
cho=list([1,2,3])
ko=list([4,5,6])
if cho.index(p1)== ko.index(p2):
    print("Draw")
if cho.index(p1) == (ko.index(p2) +1)%3:
    print("Player 2 Wins ")
if ko.index(p2)==(cho.index(p1)+1)%3:
    print("Player 1 Wins")
if p1 not in cho or p2 not in ko:
    print("Invalid Value")
# PaperStoneScissorsBeginner
print("""___Hello You Are Wellcome To RPS Game____
      Please Read The Description For Rules:
      For First Player:_________
      1 means=>Paper,2 means=>Rock,3= Means=>Scissors
      For Second Player:__________
      4 means=>Paper,5 means=>Rock,6= Means=>Scissors
      """)
p1=int(input("What Is player 1's request \n\n\n\n"))
p2=int(input("What Is player 2's request \n\n\n\n"))
cho=list([1,2,3])
ko=list([4,5,6])
if cho.index(p1)== ko.index(p2):
    print("Draw")
if cho.index(p1) == (ko.index(p2) +1)%3:
    print("Player 2 Wins ")
if ko.index(p2)==(cho.index(p1)+1)%3:
    print("Player 1 Wins")
if p1 not in cho or p2 not in ko:
    print("Invalid Value")
