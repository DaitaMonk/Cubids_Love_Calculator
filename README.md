# Cubids_Love_Calculator

# CUPID'S LOVE CALCULATOR


**Love calculators are like mischievous little cupids hiding inside our computers. They claim to have the secret formula for measuring love, but in reality, they're just mischievous matchmakers playing with our hearts.**

**When you enter your name and your crush's name into a love calculator, it's like throwing ingredients into a magical cauldron. The calculator starts bubbling and whirring, trying to compute an enchanting love score. It's as if the calculator is whispering sweet nothings to the numbers, coaxing them to reveal your fate.**

**But be warned! Love calculators have a mischievous sense of humor. They might giggle and tease you with a high score, making your heart race and your palms sweat. Or they might playfully nudge you with a modest score, leaving you hopeful but wanting more.**



**The code below is a simple love calculator that takes two names as input and calculates a "love score" based on the occurrences of specific letters in the combined names.**

## **Here's a simplified explanation of how the code works:**

The code prompts the user to enter two names: U and p.

It concatenates the two names together and assigns the result to the variable full.

The full.lower() line attempts to convert the combined name to lowercase. However, since it doesn't assign the result back to a variable, it doesn't affect the subsequent code.

Two lists, t and l, are defined. Each list represents the letters of the words "true" and "love" respectively.

Two variables, scoree and scor, are initialized to zero. These variables will be used to keep track of the score for the letters in the combined name.

The code uses a loop to iterate over each letter in the t list and adds the count of that letter in the full name to the scoree variable.

Similarly, another loop iterates over each letter in the l list and adds the count of that letter in the full name to the scor variable.

The score variable is created by concatenating the scoree and scor values together as strings.

## **The code then compares the score with certain thresholds to determine the output message:**

If the score is greater than 70, it prints "Cupid Agrees!".
If the score is less than or equal to 70, it prints "Cupid Says Maybe".
If the score is less than or equal to 50, it prints "Cupid is silent".
Overall, the code calculates a "love score" by counting the occurrences of specific letters in the combined names and provides a response based on that score. However, it's important to note that this code is a very simplistic representation of a love calculator and shouldn't be taken as an accurate measure of love. It's purely for illustrative purposes.

## Author
[ALvin Momoh](https://github.com/DaitaMonk)
