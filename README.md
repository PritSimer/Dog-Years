# Dog-Years
Codecademy Javascript Beginners Practice Project
let myAge = 4; // my age assigned to a variable labeled myAge that can be reassigned as it is a let variable type
 let earlyYears = 2 // asigned value 2 to early years

let myRealAge= myAge;
 earlyYears *=10.5;
myAge -=2; // first 2 years have been accounted for that's why we have taken away 2. Assigned a variable called laterYears to save this number temporarily. 

laterYears = myAge;

 laterYears *=4; // calculate number of dog years accounted for by later years

myAgeInDogYears = earlyYears + laterYears;
console.log(myAgeInDogYears);

const myName=('Simerprit'.toLowerCase());//saved my name to a variable and assigned a method function that will print it in lowercase when printed

console.log(` My name is ${myName}. I am ${myRealAge} years old in human years which is ${myAgeInDogYears} years old in dog years.`);
