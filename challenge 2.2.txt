'''Implement a class called Player that represents a cricet player the class should have a
method called play() which prints "the plyer is playing cricet"Derive two classes,Batsman and
Bowler,from the Player class.Override the play() method derived class to print "The batsman
is batting" and "the bowler is bowling",respectively.Write a program to create objects of both the 
Batsman and Bowler classes and call the play() method for each objects.'''


# Define the base class player
class Player:

  def play(self):
    print("The player is playing cricket.")


# Define the dervied class Batsman
class Batsman(Player):

  def play(self):
    print("The batsman is batting.")


# Define the derived class Bowler
class Bowler(Player):

  def play(self):
    print("The bowler is bowling.")


# Create objects of Batsman and Bowler classes
batsman = Batsman()
bowler = Bowler()

# call the play() method for each objeclass Player:
batsman = Batsman()
bowler = Bowler()
player = Player()
player.play()
batsman.play()
bowler.play()
