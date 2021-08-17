# guessthenumber
# 终极密码
https://zh.wikipedia.org/wiki/%E7%B5%82%E6%A5%B5%E5%AF%86%E7%A2%BC
https://www.youtube.com/watch?v=DwN_6epk6Jo

终极密码 is created through my own self learning in Microsoft Learn Python. Basically took snippets of the code that are useful in the courses, then add in codes to build the 终极密码
game.

The features of 终极密码 include, enter a name of the dealer, anonymous name is fine, restrict integers to be keyed in from 1 - 100, reduction of available numbers in the range 
gradually till the correct one is left or the correct number is guessed way ahead.

The last feature is completely self developed by my own efforts.
Python range poses problem because it does not iterate to include the last value. For example if x=range(1,100), list(x) will produce [1,2,3...99]
To overcome this issue, some trial and error is run to make sure this program does the intended effect of reducing the range gradually, so the numbers available for selection is
shown after each incorrect guess, the already guessed numbers are left out of upper and lower bounds.

终极密码 is often played in variety show in Taiwan. It is a simple yet entertaining game, whereby the person who guess number correctly, or the last person left with no choice but the chosen number does a forfeit on the show. 
Sometimes the host of the show will deliberately change the chosen number to get the person to do the forfeit, so no matter what random number it is, the player's guess is the 
right number! Rigged!

Game starts by chosing one random number from 1-100. The number is only known by the dealer.
Each player takes turn to guess till one guess it right. The player who guess it right is the joker and does the forfeit. 
In the instance when two numbers are left, the player in the current turn still guessed the wrong number, the next player in line strikes
the jackpot and is the joker!


 终极密码 2 Players allows two players to register. Same concept but added in another while loop to run the game.
 
