# name-prompt
//ask user for name then capitalize first letter and make all other letters lowercase

//Create a variable that stores name that user enters via prompt.

var name = prompt("What is your first name?");

var firstLetter = name.slice(0,1);

//Capitalize first letter of their name.

var firstLetterCapitalized = firstLetter.toUpperCase();

var restOfLetters = name.slice(1,name.length);

//make rest of letters lowercase.

var restOfLetters = restOfLetters.toLowerCase();

var capitalizedName = firstLetterCapitalized + restOfLetters;

//Use capitalized version of their name to greet them using an alert.

alert("Hello, " + capitalizedName);
