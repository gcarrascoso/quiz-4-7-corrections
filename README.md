# quiz-4-7-corrections

Quiz 4:
 
 Question 5 -  While I did choose one of the correst answers which was the last one, I failed to realize that there was more answers than just the one I selected.  While I choose the one that correctly used p.innnerHTML, you do not have to declare a variable (p) for it as everything is linked correctly.
 
 Question 6 - This mistake was rather careless as I knew that all of the answers except 1 and -1 were falsey values.  0 should have also been marked as it is a falsey value.
 
 Question 9 - I choose that "let x = 27" was also a statement that declares and initializes a variable which is incorrect. That statement only initializes a variable it does not declare it.
 
 Question 11 -
 
 ```
function askedAndAnswered() {
  let name = prompt("Enter your first name.");
  let age = Number(prompt("Enter your age."));
  let agePlus = age + 1;
  var p = document.getElementById("asked-and-answered");
  p.innerHTML = `Hello ${name}. When do you turn ${agePlus}?`;
}
```

 ```
function classTrip() {
  let studentNumber = Number(prompt("Enter the number of students attending a class trip"));
  let chaperoneNumber = Number(prompt("Enter the number of chaperones (including teachers) attending a class trip"));
  let busCapacity = Number(prompt("enter the maximum capacity (not including the bus driver) of each bus."));
  let busesNeeded = Math.floor((studentNumber + chaperoneNumber) / busCapacity);
  console.log(busesNeeded + " busses are required to accommodate " + studentNumber + " students and " + chaperoneNumber + " chaperones.");
}
```

Quiz 5:

Question 2 - I thought that two falses would be logged onto the console, but this is not true as the "!!a" would invert it back into true.  The console would then read flase and true.

Question 4 - What I made my mistake on was the relational operators involving the first if statement as i put x == y.  That is wrong however as that woud only read the value type and it has to read both value type and data type making is x === y.

Question 5 - In this question I selected all the correct answers except I selected = when that was false.  "=" is not a relational operator.\

Question 7 - while the answer I did choose would hypothetically work in the given scenario, I failed to choose the fastest method.  The faster method did not involve both greater than And less than in the if statements, but just a simple greater than.

Question 15 - While the portion of code I selected did terminate in time, I missed another answer that would have also terminated which was the second choice.  Because it was x was already greater than 100, it would have immediately terminated.  



Quiz 6:

Question 3 - This question had two other answers that I did not find feasible until further inspection.  The first answer was also correct as if the user did not enter a value for c it would be read as undefined.  The other answer was also valid as it makes sense as all inputs wee inplace.  My msitake was that i thought th different console.logs would effect each other so I assumed there was only one answer.

Question 4 - The answer I choose for this question does not accept as parameters the values beig divided.  The correct answer which had divide(a, b); in it does as a and b are now parameters and are being divided.

Question 10 - I was correct in all of my answers except one which was Math.random.  All the other functions accept parameters except Math.random.

Question 12 - I was wrong in thinking that 1 would be printed out in the console because let functions are block scope not function scope.  That means an error on line 10 because it is outside the block.

Quiz 7:

Question 2 - There were 2 other answers I did not check in, as I was still unsure of what the indexOf and lastIndexOf methods did.  I know now that these methods would have searched the array to see if what you entered into the prompt was a German car based on the cars in the array.  If it wasn't false it would log that you owned a German car.

Question 13 - numbers[3] = 8; along with the rest of the parts of that portion of code would have also effectively added numbers to the array.  This is because they are asigning new values to new parst of the array as it only went up as far to numbers[2] before the code adds the new values to it.

Question 14 - The variable tripleDigits would have stayed the same regardless of whether there were numbers in the array that were less than 100 or greater than 999 because those numbers were only returned, not removed from the array.

