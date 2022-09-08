# fizzbuzz-game-in-javascript
var output = [];
var series = 1;


function fizzBuzz() {
    while (series <= 100){
  if (series % 3 === 0 && series % 5 === 0){
     output.push("FizzBuzz");
 }
 else if (series % 3 === 0){
    output.push("Fizz");
 }
 else if (series % 5 === 0){
     output.push("Buzz");
 }
 
 else {
      output.push(series);
 }
     series++;
     console.log(output);
}
}
    fizzBuzz();
