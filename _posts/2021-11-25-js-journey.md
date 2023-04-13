## My Journey Learning the Basics of JavaScript

Hey, it's Qamar again, and in this post, I'm excited to share my journey of learning the basics of JavaScript.

When I first started learning JavaScript, I was overwhelmed by the amount of information out there. But by breaking it down into manageable steps, I was able to learn the basics and build some cool projects. Here's how I did it:

Starting with the basics: I began with the basic concepts of JavaScript such as variables, functions, and data types. Here's an example of how I defined and used a variable in JavaScript:

```javascript
var name = "Qamar";
console.log("My name is " + name);
```

Applying what I learned: Once I had a solid understanding of the basics, I started applying what I learned to small projects. Here's an example of a simple program that calculates the sum of two numbers:

```javascript
function addNumbers(a, b) {
  return a + b;
}

var sum = addNumbers(5, 10);
console.log(sum);
```

Using online resources: I found online resources like Codecademy and FreeCodeCamp to be incredibly helpful in expanding my knowledge of JavaScript. Here's an example of a Codecademy exercise that helped me understand how to use arrays in JavaScript:

```javascript
var fruits = ["apple", "banana", "orange"];
console.log(fruits[0]);
```

Building projects: Once I had a solid understanding of the basics, I started building more complex projects. Here's an example of a simple weather app that I built using JavaScript:

```javascript
var apiKey = "your-api-key-here";
var apiUrl = "https://api.openweathermap.org/data/2.5/weather?q=";

function getWeather(city) {
  var url = apiUrl + city + "&appid=" + apiKey;
  fetch(url)
    .then((response) => response.json())
    .then((data) => {
      console.log(data);
    });
}

getWeather("New York");
```

Practicing regularly: Finally, I made it a point to practice coding regularly. I found that coding challenges and exercises were a great way to improve my skills. Here's an example of a simple coding challenge that helped me improve my problem-solving skills:

```javascript
function findLargestNumber(numbers) {
  var largestNumber = numbers[0];
  for (var i = 1; i < numbers.length; i++) {
    if (numbers[i] > largestNumber) {
      largestNumber = numbers[i];
    }
  }
  return largestNumber;
}

var numbers = [2, 5, 10, 7, 1];
console.log(findLargestNumber(numbers));
```

See you in the next stop!
