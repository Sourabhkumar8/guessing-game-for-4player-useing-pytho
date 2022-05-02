# guessing-game-for-4player-useing-pytho
4player can participate in this game.
import random
ch ="yes"
while(ch != "no"):

      print(" welcome to guessing game")

      
      player1 = int(input(" player1 guess the number "))
      player2 = int(input(" player2 guess the number "))
      player3 = int(input(" player3 guess the number "))
      player4 = int(input(" player4 guess the number "))

      number = random.randint(0,10)
      if (player1 and player2 and player3 and player4)== number:
          print("you all are super ! you all won the game")       
      elif player1 == number:#sourabh kumar prince
              print(" player1 win the game")
              print(" player2,3,4 better luck next time")
      elif player2 == number:
              print(" player2 win the game")
              print(" player1,3,4 better luck next time")
      elif player3 == number:
            print(" player3 win the game ")
            print("player1,2,4 better luck next time")
      elif player4 == number:
            print("player4 win the game") 
            print("player1,2,3 better luck next time")  
      elif (player1 and player2)== number:
            print("player1 and player2 win the game")
            print("player3,4 better luck next time")
      elif (player1 and player3)== number:
            print("player1 and player3 win the game")
            print("player4,2 better luck next time")
      elif (player1 and player4)== number:
            print("player1 and player4 win the game")
            print("player3,2 better luck next time")
      elif (player2 and player3)== number:
            print("player3 and player2 win the game")
            print("player1,4 better luck next time")      
            print("player4 and player2 win the game")
            print("player3,1better luck next time")
      elif (player3 and player2)== number:
            print("player3 and player2 win the game")
            print("player1,4 better luck next time")
      elif (player3 and player4)== number:
            print("player3 and player4 win the game")
            print("player1,2 better luck next time") 
      elif (player1 and player2 and player3 and player4)== number:
          print("you all are super ! you all won the game")       
      elif player1 !=number and player2 !=number and player3 != number and player4 !=number:
             print( "oops! wrong guess , right guess is "+str(number))
      else:
             print("right guess is "+str(number))
      print("right guess is "+str(number)) 
      ch = input("Do you want to continue game press yes for continue and no for exit ")                  



