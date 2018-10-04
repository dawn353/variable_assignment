
# Variable Exercises

1. Age Calculator:
* Store your birth year in a variable.
* Store a future year in a variable.
* Calculate your 2 possible ages for that year based on the stored values.
* For example, if you were born in 1988, then in 2026 you'll be either 37 or 38, depending on what month it is in 2026.
* Log them to the screen like so: "I will be either `ageMin` or `ageMax` in `futureYear`", substituting the values.

let myYear = 1993;
let futureYear = 2020;
let ageMin = (futureYear - myYear) - 1;
let ageMax = futureYear - myYear;
console.log("I will be either " + ageMin + " or " + ageMax + " in " + futureYear);



2. Snack Supply Calculator:
* Store your current age in a variable.
* Store a maximum age in a variable.
* Store an estimated snack amount per day (as a number).
* Calculate how many snacks you would eat total, from your current age until the maximum age.
* Log the result to the screen like this: "You will need `snackNumber` to last you until the age of `maxAge`".

let myAge = 25
let maxAge = 50
let snackNumber = 5

console.log("You will need " + 365 * snackNumber * maxAge + " to last you until the age of " + maxAge)




3. Calculate properties of a circle, using the definitions [here](http://math2.org/math/geometry/circles.htm).
* Use google: find how to get the number `PI` in JavaScript.
* Store a radius into a variable.
* Calculate the circumference based on the radius, and log "The circumference is `circumferenceResult`".
* Calculate the area based on the radius, and log "The area is `areaOfCircle`".

let radius = 4
let diameter = 2 * radius
let circumferenceResult= Math.PI * diameter;
let areaOfCircle = Math.PI * radius


console.log(circumferenceResult)
console.log(areaOfCircle)



4. Temperature Converter:
* Store a celsius temperature into a variable.
* Convert it to fahrenheit and output "`tempInCelcius`°C is `tempInFahrenheit`°F".
* Now store a fahrenheit temperature into a variable.
* Convert it to celsius and output "`tempInFahrenheit`°F is `tempInCelcius`°C."

let tempInCelcius = 39
let tempInFahrenheit = tempInCelcius * 9/5 + 32


console.log(tempInCelcius + "°C"+ " is " + tempInFahrenheit + "°F" )


console.log(tempInFahrenheit + "°F"+ " is " + tempInCelcius + "°C" )




### What will be logged:
5.
```js

let num1 = 2
let num2 = 5
let num3 = num1 * num2
console.log(num3)
```
10

6.
```js
let str = 'jel'

str += 'lo'

console.log(str)
```
'jello'

7.
```js

let string =  'My favorite number is ';
let number = 42
let sentence = string + number
console.log(typeof(sentence))
```
string
