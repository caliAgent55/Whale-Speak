# Whale-Speak
Project from Codecademy using for loops. 

/* Creat a loop to iterate through each letter of the input variable text. In a later step, we will compare each letter with our vowels array. 

for (let i = 0; i < input.length; i++) {

/* Create a nested for loop inside of the for loop you just wrote. Make the inner loop iterate through the vowels array each time the outer loop runs. 
This will enable you to check each letter of input against all the vowels elements during each iteration.

  for (let j = 0; j < vowels.length; j++) {
    if (input[i] === vowels[j]) {

/* Inside the second for loop, write a code block that compares the input letter in the vowels array. 

      resultArray.push(vowels[i]);
    }

/* To check your work, log the iterator numbered position inside the or loop and run your code. This should count the number of characters in your 
input string. Comment out this code when you're ready to move on */ 

     console.log('j is ' + j);
  }
};

/* Create a nested for loop inside of the for loop you just wrote. Make the inner loop iterate through the vowels array each time the outer loop runs.
This will enable you to check each letter of input against all the vowels elements during each iteration. */

for (let i = 0; i < input.length; i++) {
  for (let j = 0; j < vowels.length; j++) {
    if (input[i] === 'e') {
      resultArray.push(input[i]);
    }
  
  /* To check your work, log the iterator number positions inside the inner for loop and run your code. You should see 0 through 4 repeatedly because vowels is 5 elements 
  long. */

console.log('j is ' + j);

/* Inside the second for loop, write a code block that compares the input letter to every letter in the vowels array. */

{
      resultArray.push(input[i]);
    }
    
/* Whales double their e‘s and the u‘s in their language. Write an if statement that checks if each letter in the input string is equal to 'e'. If so, .push() input[i] to the resultArray. */   

 if (input[i] === 'e') {
      resultArray.push(input[i]);

/* Next, you want to double the letter u, so you must mimic the code from the last step. Re-create the if statement, but modify it so it pushes the letter u a second time. */

   {
    if (input[i] === 'e'){
      resultArray.push(input[i])
    }

/* At the bottom of the program, log resultArray to the console. Notice when we log the array, the output has commas between each letter. To produce proper whale language, we want to capitalize the array elements and put them together as one string. */

console.log(resultArray.join('').toUpperCase());

/* Run the program and sing the output out loud — you officially speak whale! To confirm, if you change the value of input to ‘turpentine and turtles’, the whale version would read: 'UUEEIEEAUUEE'. */

//completed code

let input = "turpentine and turtles";
const vowels = ['a', 'e', 'i', 'o', 'u']; 
let resultArray = [];  

for (let i = 0; i < input.length; i++) {
  for (let j = 0; j < vowels.length; j++) {
    if (input[i] === 'e') {
      resultArray.push(input[i]);
    }
    {
    if (input[i] === 'e'){
      resultArray.push(input[i])
    }
    if (input[i] === 'u'){
      resultArray.push(input[i])
    }
    if (input[i] === 'u'){
      resultArray.push(input[i])
    }
    if (input[i] === 'a'){
      resultArray.push(input[i])
    }
    if (input[i] === 'i'){
      resultArray.push(input[i])
    }
    if (input[i] === 'o'){
      resultArray.push(input[i])
    }
    }
  }
};
console.log(resultArray.join('').toUpperCase());
