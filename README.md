#Variables

[Python Compiler - Click here] (http://www.tutorialspoint.com/execute_python_online.php)

Variables are essential to any computer program. Variables hold different values that can easily be changed later in the program. In a variable, you _store_ values like how a cardboard box can store shoes. Likewise, one can label their shoe boxes for different types of shoes similarily to how someone can name variables for various purposes.

In a variable there is the __name__ which is on the left side (which you choose what the variable name is), an __```=``` sign__ after the name that assigns a __value__ (which is put after the ```=``` sign) to the variable name.

##Styles
A good variable name is short, to the point, and is descriptive enough to describe its purpose. There are styles of naming variables, especially when they get very long. It is __recommended to stick with one style__ while you code in order to keep the program neat.
Different programmers prefer different styles such as:

__Underscore__
```py
move_block_distance = 20
character_health = 100
```
With the Underscore style, all words in the variable are lower-case, separated by an underscore. This is the style most commonly used by Python programmers.

__Camel Casing__
```py
moveBlockDistance = 20
characterHealth = 200
```
With the Camel Casing style there are no underscores, however the first word is lower-case and the ones afterwards are capitalized.

The examples above are clearly defined; one can see how the variable ```move_block_distance``` is 20 which means the block movement is 20. The units (ft, meters) are not defined, but since we are working with variables, the value of ```move_block_distance``` can be changed within a program.
<br><br>

####Here are some examples of bad variables and bad styles:

__The Caps Abuser__
```py
ENEMYHEALTH = 36
BULLETDAMAGE = 4
FRIENDLYFIREDAMAGE = 2
```
While all caps variables are used in programs in certain cases, it is not preferable to fill up an entire document with capital words. There are also no distinct separations in words, thus making it more difficult to read.

__Mr. LongJohns__
```py
enemy_monster_tree_scare_green_health_after_two_days_at_night = 2
varTakenFromTurningBecauseItsWithThisScriptFromTheBeginning = 10
```
Variables are supposed to be descriptive, _yes_, however let a variable be a short description and one that does not take a tremendously long time to read.

__The Face Smasher / The Lazy Potato__
```py
b = 10 000
qdyu = 15
python = 10
Python = 2
wper = 12
uper = 534
mper = 20
```
The main problem for this style is that nobody, not even yourself, will be able to understand the variables created. When someone adds ```uper``` to ```qdyu``` and receive the number of ```549```, it will be more difficult to understand what the outcome means. Although a program can have hundreds of variables and can be tedious at times, it is always a good habit to created informative and readable variables.

#####IMPORTANT TO NOTE: 
* Certain symbols such as *s, /s or numbers cannot be used in variables since they mean something else.
* Variables are case-sensitive so ```Python``` is a different variable from ```python```
* The ```=``` sign when putting a value to a variable __does not__ mean that the variable is _equivalent_ to the value. The values on the right side is __assigned__ to the variable on the left. (If still hard to comprehend, the practice underneath will demonstrate how variables are assigned)

##Mini-Lesson : Operators
In order to use variables effectively, the programmer must learn a set of operators. Operators will be covered in more depth in a later lesson, however these are a few that should be used early on:
* ```+``` is used to __add__
* ```-``` is used to __subtract__
* ```*``` is used to __multiply__
* ```/``` is used to __divide__
* ```%``` is used to divide then find the __remainder__
* ```**``` is used for __exponents__

#Try It Yourself - Practice Exercises
Clear everything in the script before starting. Ask Kallen or a friend next to you if you need help; don't be afraid to ask for assistance!<br><br>

__Use ```print(insertVariableHere)``` in order to print and see the variables inside the brackets__

1. In a blank script, create a variable that describes the number of Morrey's cats. Assign a value to the variable that states Morrey has 12 cats.<br><br>
2. If Morrey
