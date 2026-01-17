# Welcome to My Mastermind
***

## Task
The challenge is in the name of the project we have to make the game my masterind without colors but with numbers .

## Description
i create a program that will get the code and the number of attempt if the number of attempt or the code is give then it will be the code or the number of attempt 
but if there are nothing then for the code it will create a code randomly or/and for the number of attempt it will put it a 10 round ( attempt = round ) .
After that the game will start and the user input is read if the user input are the same as the code the user win if not the game continue and it telle the well placed pieces and the misplaced pieces 
and this will continue until all the round a finished or until the user win but before the number of attempt maximal is reach .

## Installation
For this project i had to do a Makefile with make, make re, make fclean & etc .

## Usage
at the start it verifies if there a flagt or flagc and if there are something after the flag and it will get the code and the number of attempt according to their flag for example for the flagc if a code is given it
will be the code but if there nothing it will create a code randomly that have no duplicate, at the right length and with each character between '0' & '8', as for the flagt if there a number that will be the 
new number of attempt but if there nothing the number of attempt will be 10.
After that the code and th attempt is given to another fonction who will "start the game" so there will be the text that say the game start and now the user will have to write a code that have no duplicate, 
at the right length and with each character between '0' & '8' if the condition are not respected it will print "wrong input!" and the user will have to write a code that respect the condition, 
after that it will verifies if the user input is the code if yes the user win and it will print "Congratz! You did it!" and if not the program continue and it will say if there any misplaced pieces 
or well placed pieces and how many and the round finish so there will be a new round that come and that until the user win or the number of attempt/round max are reach . 

```
make
./my_mastermind opt1 number1 ...
```

### The Core Team


<span><i>Made at <a href='https://qwasar.io'>Qwasar SV -- Software Engineering School</a></i></span>
<span><img alt='Qwasar SV -- Software Engineering School's Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px' /></span>
