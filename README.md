WHILE LOOPS CARDIO
==================

Let's get some practice with while loops!  
![](https://media.giphy.com/media/hWddcO7xQWCqIew5rH/giphy.gif)

GOAL
------
Today you are going to apply your knowledge of while loops and arrays in order to complete itterative processes. Remember the basic structure of a while loop is that it will continue to run while a given condition remains true. For example:
```javascript
var counter = 0;
while(counter < 10){
  counter++;
  // This will print out numbers 1 to 10. the while loop stops when it gets to a value of 10.
  console.log(counter);
}
```

Once you have increased your proficiency on while loops, we will work to combine these skills with your knowledge of arrays!

TASKS
---------
1. WARM UP: Create a while loop that counts to 10. Print out each value.
2. HEATING UP: Create a while loop that prints out a word (like Hello!) 5 times.
3. Count to 22, but this time print out a message that tells the user how many numbers they have counted to (E.g "I have counted to 1", "I have counted to 2", etc.)
4. A numlist has been created for you. Use a while loop to add 10 random numbers to this list. **HINT** - Remember we can add to a list using .push(). Additionally you can make a random number using the following code:
```javascript
// Prints out a random number between 1 and 9;
var randomNumber = Math.floor(Math.random()*10)
console.log(randomNumber);
```
5. Our favorite foods list is back! Print out each of the favorite foods using a while loop. HINT: Think about how you can use the .length property here! 
```javascript
var list = ["Thing 1", "Thing 2", "Thing 3"];
//Prints out 3 as there are 3 items on our list.
console.log(list.length);
```
6. Make a list of your favorite TV shows. Use a while loop to print out a sentence saying each of your favorite shows (e.g. "I like to watch Stranger Things", "I like to watch Game of Thrones", etc.)




// 7. Heads/Tails: Using a while loop and random numbers, make a program that flips a coin 10 times and prints out if you flipped heads or tails. Finally, return a message telling them how many times they filpped heads or tails.