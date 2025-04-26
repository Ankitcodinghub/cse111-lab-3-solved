# cse111-lab-3-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/cse111-solved-18/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;131301&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE111 Lab 3  Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
<div class="kksr-stars">
    
<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
    
<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>
                

<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
Lab Assignment no: 3

Question 1

Write a class that for running the following codes:

[You are not allowed to change the code below]

#Write your class code here

data_type1 = DataType(‘Integer’, 1234) print(data_type1.name) print(data_type1.value) print(‘=====================’) data_type2 = DataType(‘String’, ‘Hello’) print(data_type2.name) print(data_type2.value) print(‘=====================’) data_type3 = DataType(‘Float’, 4.0) print(data_type3.name)

print(data_type3.value)

Output:

Integer

1234

=====================

String

Hello

=====================

Float

4.0

Subtasks:

1. Create a class named DataType with the required constructor.

2. Assign name and values in constructor according to the output.

Question 2

Design a class called Flower with the instance variables so that after executing the following line of code the desired result shown in the output box will be printed. [You are not allowed to change the code below]

#Write your class code here flower1 = Flower() flower1.name=”Rose” flower1.color=”Red” flower1.num_of_petal=6

print(“Name of this flower:”, flower1.name) print(“Color of this flower:”,flower1.color) print(“Number of petal:”,flower1.num_of_petal) print(“=====================”) flower2 = Flower() flower2.name=”Orchid” flower2.color=”Purple” flower2.num_of_petal=4

print(“Name of this flower:”,flower2.name) print(“Color of this flower:”,flower2.color) print (“Number of petal:”,flower2. num_of_petal)

#Write the code for subtask 2 and 3 here

Output:

Name of this flower: Rose

Color of this flower: Red Number of petal: 6

=====================

Name of this flower: Orchid

Color of this flower: Purple

Number of petal: 4

Subtask:

1) Design the class Flower with default constructor to get the above output.

2) At the end of the given code, also print the address of flower1 and flower2 objects. 3) Do they point to the same address? Print (‘they are same’ or ‘they are different’) at the very end to answer this question.

Question 3

A class has been designed for this question. Solve the questions to get the desired result as shown in the output box.

[You are not allowed to change the code below]

class Wadiya(): def __init__(self): self.name = ‘Aladeen’

self.designation = ‘President Prime Minister Admiral General’ self.num_of_wife = 100 self.dictator = True

#Write your code for subtask 1, 2, 3 and 4 here

Output:

Part 1:

Name of President: Aladeen

Designation: President Prime Minister Admiral General

Number of wife: 100 Is he/she a dictator: True Part 2:

Name of President: Donald Trump

Designation: President

Number of wife: 1

Is he/she a dictator: False

Subtask:

1) Create an object named wadiya.

2) Use the object to print the values as shown in part 1 (Also print the sentence Part 1)

3) Use the same object to change and print the values in part 2 (Also print the sentence Part 2)

4) Did changing the instance variable values using the same object, affect the previous values of Part 1? (Print ‘previous information lost’ or ‘No, changing had no effect on previous value’)

Question 4

Design a class Joker with parameterized constructor so that the following line of code prints the result shown in the output box.

[You are not allowed to change the code below]

#Write your class code here

j1 = Joker(‘Heath Ledger’, ‘Mind Game’, False) print(j1.name) print(j1.power) print(j1.is_he_psycho) print(“=====================”)

j2 = Joker(‘Joaquin Phoenix’, ‘Laughing out Loud’, True) print(j2.name) print(j2.power) print(j2.is_he_psycho) print(“=====================”) if j1 == j2:

print(‘same’) else:

print(‘different’) j2.name = ‘Heath Ledger’ if j1.name == j2.name:

print(‘same’) else:

print(‘different’)

#Write your code for 2,3 here

Output:

Heath Ledger

Mind Game

False

=====================

Joaquin Phoenix

Laughing out Loud True

=====================

different

same

Subtask:

1) Design the class using a parameterized constructor.

2) The first if/else block prints the output as ‘different’, but why? Explain your answer and print your explanation at the very end. 3) The second if/else block prints the output as ‘same’, but why? Explain your answer and print your explanation at the very end.

Question 5

Design a class called Pokemon using a parameterized constructor so that after executing the following line of code the desired result shown in the output box will be printed. First object along with print has been done for you, you also need to create other objects and print accordingly to get the output correctly. [You are not allowed to change the code below]

#Write your code for class here

team_pika = Pokemon(‘pikachu’, ‘charmander’, 90, 60, 10) print(‘=======Team 1=======’) print(‘Pokemon 1:’,team_pika.pokemon1_name, team_pika.pokemon1_power)

print(‘Pokemon 2:’,team_pika.pokemon2_name, team_pika.pokemon2_power)

pika_combined_power = (team_pika.pokemon1_power + team_pika.pokemon2_power) * team_pika.damage_rate print(‘Combined Power:’, pika_combined_power)

#Write your code for subtask 2,3,4 here

Output:

=======Team 1=======

Pokemon 1: pikachu 90

Pokemon 2: charmander 60 Combined Power: 1500

=======Team 2=======

Pokemon 1: bulbasaur 80

Pokemon 2: squirtle 70

Combined Power: 1350

Subtask:

1) Design the Pokemon class using a parameterized constructor. The 5 values that are being passed through the constructor are pokemon 1 name, pokemon 2 name, pokemon 1 power, pokemon 2 power, damage rate respectively.

After designing the class, if you run the above code the details in Team 1 will be printed. 2) Create an object named team_bulb and pass the value ‘bulbasaur’, ‘squirtle’, 80, 70, 9 respectively.

3) Use print statements accordingly to print the desired result of Team 2.

Note: Power is always being calculated using the instance variables. Example:

(team_pika.pokemon1_power + team_pika.pokemon2_power) * team_pika.damage_rate

Question 6

Design the Player class so that the code gives the expected output. [You are not allowed to change the code below]

# Write Your Class Code Here

player1 = Player() player1.name = “Ronaldo” player1.jersy_number = 9

player1.position = “Striker” print(“Name of the Player:”, player1.name) print(“Jersey Number of player:”, player1.jersy_number) print(“Position of player:”, player1.position) print(“===========================”) player2 = Player() player2.name = “Neuer” player2.jersy_number = 1 player2.position = “Goal Keeper” print(“Name of the player:”, player2.name) print(“Jersey Number of player:”, player2.jersy_number) print(“Position of player:”, player2.position)

Output:

Name of the Player: Ronaldo

Jersy Number of player: 9

Position of player: Striker

===========================

Name of the player: Neuer

Jersy Number of player: 1

Position of player: Goal Keeper

Question 7

Design the Country class so that the code gives the expected output. [You are not allowed to change the code below]

# Write your Class Code here

country = Country() print(‘Name:’,country.name) print(‘Continent:’,country.continent) print(‘Capital:’,country.capital) print(‘Fifa Ranking:’,country.fifa_ranking) print(‘===================’) country.name = “Belgium” country.continent = “Europe” country.capital = “Brussels” country.fifa_ranking = 1 print(‘Name:’,country.name) print(‘Continent:’,country.continent) print(‘Capital:’,country.capital)

print(‘Fifa Ranking:’,country.fifa_ranking)

Output:

Name: Bangladesh

Continent: Asia

Capital: Dhaka

Fifa Ranking: 187

===================

Name: Belgium

Continent: Europe

Capital: Brussels

Fifa Ranking: 1

Question 8

Write the DemonSlayer class so that the code gives the expected output. [You are not allowed to change the code below]

# Write your Class Code here

tanjiro = DemonSlayer(“Tanjiro”, “Water Breathing”, 10, 10) print(‘Name:’,tanjiro.name) print(‘Fighting Style:’,tanjiro.style) print(f’Knows {tanjiro.number_of_technique} technique(s) and has killed {tanjiro.kill} demon(s)’) print(‘===================’) zenitsu = DemonSlayer(“Zenitsu”, “Thunder Breathing”, 1, 4) print(‘Name:’,zenitsu.name) print(‘Fighting Style:’,zenitsu.style) print(f’Knows {zenitsu.number_of_technique} technique(s) and has killed {zenitsu.kill} demon(s)’) print(‘===================’) inosuke = DemonSlayer(“Inosuke”, “Beast Breathing”, 5, 7) print(‘Name:’,inosuke.name) print(‘Fighting Style:’,inosuke.style) print(f’Knows {inosuke.number_of_technique} technique(s) and has killed {inosuke.kill} demon(s)’) print(‘===================’) print(f'{tanjiro.name}, {zenitsu.name}, {inosuke.name} knows total {tanjiro.number_of_technique + zenitsu.number_of_technique

+ inosuke.number_of_technique} techniques’) print(f’They have killed total {tanjiro.kill + zenitsu.kill + inosuke.kill} demons’)

Output:

Name: Tanjiro

Fighting Style: Water Breathing

Knows 10 technique(s) and has killed 10 demon(s)

===================

Name: Zenitsu

Fighting Style: Thunder Breathing

Knows 1 technique(s) and has killed 4 demon(s)

===================

Name: Inosuke

Fighting Style: Beast Breathing

Knows 5 technique(s) and has killed 7 demon(s)

===================

Tanjiro, Zenitsu, Inosuke knows total 16 techniques

They have killed total 21 demons

Question 9

Write the box class so that the code gives the expected output.

#Write your class code here

print(“Box 1”) b1 = box([10,10,10]) print(“=========================”) print(“Height:”, b1.height) print(“Width:”, b1.width) print(“Breadth:”, b1.breadth) print(“————————-“) print(“Box 2”) b2 = box((30,10,10)) print(“=========================”) print(“Height:”, b2.height) print(“Width:”, b2.width) print(“Breadth:”, b2.breadth) b2.height = 300 print(“Updating Box 2!”) print(“Height:”, b2.height) print(“Width:”, b2.width) print(“Breadth:”, b2.breadth) print(“————————-“) print(“Box 3”) b3 = b2 print(“Height:”, b3.height) print(“Width:”, b3.width) print(“Breadth:”, b3.breadth) Output:

Box 1

Creating a Box!

Volume of the box is 1000 cubic units.

=========================

Height: 10

Width: 10

Breadth: 10

———————————————

Box 2

Creating a Box!

Volume of the box is 3000 cubic units.

=========================

Height: 30

Width: 10

Breadth: 10 Updating Box 2!

Height: 300

Width: 10

Breadth: 10

———————————————

Box 3

Height: 300

Width: 10

Breadth: 10

Question 10

Design the required class from the given code and the outputs.

[You are not allowed to change the code below]

Hint:

Number of the border characters for the top and the bottom

= 1

+ Number of spaces between the left side border and the first character of the button name

+ Length of the button name

+ Number of spaces between the right side border and the last character of the button name

+ 1

NOTE: Don’t count the space or any character from the button representation to solve this problem.

#Write your class code here

word = “CANCEL” spaces = 10 border = ‘x’

b1 = buttons(word, spaces, border)

print(“=======================================================”) b2 = buttons(“Notify”,3, ‘!’)

print(“=======================================================”) b3 = buttons(‘SAVE PROGRESS’, 5, ‘$’)

Output:

CANCEL Button Specifications:

Button name: CANCEL

Number of the border characters for the top and the bottom: 28

Number of spaces between the left side border and the first character of the button name: 10

Number of spaces between the right side border and the last character of the button name: 10

Characters representing the borders: x

xxxxxxxxxxxxxxxxxxxxxxxxxxxx

x CANCEL x xxxxxxxxxxxxxxxxxxxxxxxxxxxx

=========================================================

Notify Button Specifications:

Button name: Notify

Number of the border characters for the top and the bottom: 14

Number of spaces between the left side border and the first character of the button name: 3

Number of spaces between the right side border and the last character of the button name: 3

Characters representing the borders: !

!!!!!!!!!!!!!!

! Notify !

!!!!!!!!!!!!!!

========================================================= SAVE PROGRESS Button Specifications:

Button name: SAVE PROGRESS

Number of the border characters for the top and the bottom: 25

Number of spaces between the left side border and the first character of the button name: 5

Number of spaces between the right side border and the last character of the button name: 5

Characters representing the borders: $

$$$$$$$$$$$$$$$$$$$$$$$$$

$ SAVE PROGRESS $ $$$$$$$$$$$$$$$$$$$$$$$$$
