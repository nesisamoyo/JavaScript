// variables declared using const are read-only. They are a constant value, 
// which means that once a variable is assigned with const, it cannot be reassigned:
   // const FAV_PET = "Cats";
   // FAV_PET = "Dogs";
// The console will display an error due to reassigning the value of FAV_PET.
// You should always name variables you don't want to reassign using the const keyword. 
// This helps when you accidentally attempt to reassign a variable that is meant to stay constant.
// Note: It is common for developers to use uppercase variable identifiers for immutable values 
// and lowercase or camelCase for mutable values (objects and arrays).

const FCC = "freeCodeCamp"; 
let fact = "is cool!";
fact = "is awesome!";
console.log(FCC, fact);
