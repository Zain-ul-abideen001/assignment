function one() {
  var username = prompt("enter your name");
  alert(`hi, ${username}`);
}
function two() {
  var table = prompt("enter a table number");
  var tablehtml = document.getElementById("talbe");
  tablehtml.innerHTML = `
    ${table} x 1 = ${table * 1}<br>
    ${table} x 2 = ${table * 2}<br>
    ${table} x 3 = ${table * 3}<br>
    ${table} x 4 = ${table * 4}<br>
    ${table} x 5 = ${table * 5}<br>
    ${table} x 6 = ${table * 6}<br>
    ${table} x 7 = ${table * 7}<br>
    ${table} x 8 = ${table * 8}<br>
    ${table} x 9 = ${table * 9}<br>
    ${table} x 10 = ${table * 10}
    `;
}
function three() {
  var cityname = prompt("enter your city name").toLowerCase();
  if (cityname == "karachi ") {
    alert("welcom to city of light");
    console.log(cityname);
  } else if (cityname == "") {
    alert("plz enter a city name");
  } else {
    alert(`welcome to ${cityname}`);
  }
}
function four() {
  var usergender = prompt("enter your gender").toLowerCase();
  if (usergender == "male") {
    alert("good morning sir");
  } else if (usergender == "female") {
    alert("good morning mam");
  } else alert("plz enter correct gender");
}
function five() {
  var signalcolor = prompt("enter the signal color").toLowerCase();
  if (signalcolor == "red") {
    alert("vehicles must stop");
  } else if (signalcolor == "yellow") {
    alert("vehicles should get ready to move");
  } else if (signalcolor == "green") {
    alert("vehicles can move now");
  } else alert("plz enter correct color name");
}
function six() {
  var age = +prompt("enter your current age");
  var maxage = +prompt("enter your max age");
  if (age <= maxage) {
    alert("You are welcome");
  } else alert("mar gaya");
}
function seven() {
  var fuel = +prompt("enter your fuel quantity");
  if (fuel <= 0.25) {
    alert("Please refill the fuel in your car");
  } else alert("fuel is enough");
}
function eight() {
  var a = 4;
  if (++a === 5) {
    alert("given condition for variable a is true");
  }
  var b = 82;
  if (b++ === 83) {
    alert("given condition for variable b is true");
  }
  var c = 12;
  if (c++ === 13) {
    alert("condition 1 is true");
  }
  if (c === 13) {
    alert("condition 2 is true");
  }
  if (++c < 14) {
    alert("condition 3 is true");
  }
  if (c === 14) {
    alert("condition 4 is true");
  }
  var materialCost = 20000;
  var laborCost = 2000;
  var totalCost = materialCost + laborCost;
  if (totalCost === laborCost + materialCost) {
    alert("The cost equals");
  }
}
function nine() {
  var subone = +prompt("subject one nunmber out of 100");
  var subtwo = +prompt("subject two nunmber out of 100");
  var subthree = +prompt("subject three nunmber out of 100");
  var subtotal = subone + subtwo + subthree;
  if (subtotal > 300) {
    alert("plz enter the marks under 100");
  } else {
    var percentage = (subtotal * 100) / 300;
    alert(`your percentage is ${percentage}`);
  }
}
function ten() {
  var itemone = +prompt("enter item one price");
  var itemtwo = +prompt("enter item two price");
  var itemtotal = itemtwo + itemone;
  var discount = 0;
  if (itemtotal >= 10000) {
    discount = itemtotal * 0.1;
  } else if (itemtotal >= 5000) {
    discount = itemtotal * 0.05;
  } else if (itemtotal >= 3000) {
    discount = itemtotal * 0.03;
  } else alert("no discount available");
  alert(`your total price is ${itemtotal}  your discount is ${discount} your sub total price is ${itemtotal- discount}`)
}
function eleven(){
  var secretno =6
  var userno = +prompt("guess the secret number")
  if (secretno == userno ){
    alert("“Bingo! Correct answer”.")
  }else if(userno == secretno-1 || userno == secretno+1){
    alert("“Close enough to the correct answer”.")
  }else{
    alert("your guess number is incorrect")
  }
}
function twelve(){
  var userno = +prompt ("enter the number ")
  if (userno%3==0){
    alert("your number is divisible")
  }else{
    alert("your number is not a divisible")
  }
}
function fifteen(){
var user = +prompt("enter a number")
if (user%2== 0){
  alert("your number is even")
}else alert("your number is odd")
}
function sixteen(){
  var userin = prompt ("enter ayour current temperature")
  if (userin == "40"){
alert ("It is too hot outside.")
  }else if (userin == "30"){
    alert("“The Weather today is Normal.”")
  }else if (userin == "20"){
    alert("“Today’s Weather is cool.”")
  }else alert("“OMG! Today’s weather is so Cool.”")
}
function seventeen(){
  var num1= +prompt("enter a first number")
  var num2= +prompt("enter a second number")
  var operator = prompt("enter a operator")
  if (operator === '+') {
    alert("Result: " + (num1 + num2));
} else if (operator === '-') {
    alert("Result: " + (num1 - num2));
} else if (operator === '*') {
    alert("Result: " + (num1 * num2));
} else if (operator === '/') {
    if (num2 === 0) {
        alert("Error: Division by zero is not allowed.");
    } else {
        alert("Result: " + (num1 / num2));
    }
} else if (operator === '%') {
    alert("Result: " + (num1 % num2));
} else {
    alert("Invalid operator. Please try again.");
}
}
function eighteen() {
  let day = prompt("Enter the day name:").toLowerCase();  
  if (day === "monday" || day === "tuesday" || day === "wednesday" || day === "thursday" || day === "friday") {
      alert("It’s a week day.");
  } else if (day === "saturday") {
      alert("It’s weekend.");
  } else if (day === "sunday") {
      alert("Yay! It’s a holiday.");
  } else {
      alert("Invalid input. Please enter a valid day name.");
  }
}
function nineteen() {
  let score = parseFloat(prompt("Enter your score:"));
  if (score > 50) {
      alert("You are passed.");
  } else {
      alert("Try again!");
  }
}
function  twenty() {
  let num1 = parseFloat(prompt("Enter the first number:"));
  let num2 = parseFloat(prompt("Enter the second number:"));
  if (num1 > num2) {
      alert("The greater number of " + num1 + " and less number" + num2 )
  } else if (num2 > num1) {
      alert("The greater number of " + num2 + " and less number " + num1 )
  } else {
      alert("Both numbers are equal.");
  }
}
function twentyone(){
}
