# diceCalculator-201950022
Personal Project on My Interests or Hobbies

**PROJECT DETAILS**

> Project Name: DiceCalc
> 
> Author: Aren Deza, 2019-50022
>
> Version: 1.0
> 
> Date Completed: Jan 9, 2021

**WHAT'S THIS?**

> This is a Dice Calculator that I created in compliance with the requirements for CMSC 22. 
It will take any dice roll (such as two 6-sided dice or five 10-sided dice)
and then it will print the possible range (minimum and maximum) as well as
the average possible roll.

**JAVA DESIGN PATTERNS USED**
> **Creational (Singleton)** -
I used the singleton pattern, as the extremely simple nature of this program doesn't necessitate using more than one object. 
As such, I only created one instance (that being 'roll') to facilitate our calculations and make the template easier on the eyes.

> **Structural (Adapter)** -
I use the adapter pattern to assign the inputs to specific variables when constructing our single object.
This was selected because having a separate class for calculations necessitated having a pattern that could
adapt the inputs taken from the user into values that we could perform computations with.

> **Behavioural (Template)** -
I selected the template pattern because of how it makes everything easier to trace, and makes it easier for me to visualize the 
program's output as I write the code. Additionally, it makes viewing the source code much easier when I'm required to call 
several methods in quick succession.

**BEST CODING PRACTICES USED**
> (these practices were applied as needed)
> 
> source files 
>
> naming conventions
>
> methods
>
> if-checks
>
> declarations
>
> assignments
>
> documentation and comments

**NOTE**

> the source code contains a combination of javadoc block comments and single-line comments, as I used the single-line comments for 
my own reference and later added the javadoc block comments for full documentation purposes.
