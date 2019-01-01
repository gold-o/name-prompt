# name-prompt
//ask user for name then capitalize first letter and make all other letters lowercase

//1.Create a variable that stores name that user enters via prompt.
//2.Capitalize first letter of their name.
//3.make rest of letters lowercase.
//4.Use capitalized version of their name to greet them using an alert.

var name = prompt("What is your first name?");
var firstLetter = name.slice(0,1);
var firstLetterCapitalized = firstLetter.toUpperCase();
var restOfLetters = name.slice(1,name.length);
var restOfLetters = restOfLetters.toLowerCase();
var capitalizedName = firstLetterCapitalized + restOfLetters;
alert("Hello, " + capitalizedName);
