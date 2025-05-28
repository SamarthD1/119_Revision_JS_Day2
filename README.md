# 119_Revision_JS_Day2

Q1. DOM (Document Object Model)

1.What does DOM stand for?
(a) Document Object Model
reference: https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model

2.Which method is used to select an element by its ID?
(c) getElementById()
reference: https://developer.mozilla.org/en-US/docs/Web/API/Document/getElementById

3.What does document.querySelector(".box") select?
(b) The first element with class "box"
reference: https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelector

4.How do you change the text of an element with ID "message"?
(d) document.getElementById("message").innerText = "Hello"
reference: https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement/innerText

5.What is the purpose of innerHTML?
(c) To get or set the HTML content of an element
reference: https://developer.mozilla.org/en-US/docs/Web/API/Element/innerHTML


Q2. Events

1. What is an event in JavaScript?
b) A user or browser action

2. Which event occurs when a user clicks on an HTML element?
c) onclick

3. How can you add a click event to a button in JavaScript?
b) addEventListener("click")
(Complete usage: button.addEventListener("click", functionName))

4. What does event.preventDefault() do?
b) Stops default action like form submission

5. Which method is used to attach an event handler?
c) addEventListener()


Q3. Math.random()

1. What does Math.random() return?
 c) A number between 0 and 1

2. How do you get a random integer from 1 to 10?
 c) Math.floor(Math.random() * 10) + 1

3. What is the output range of Math.random()?
 c) 0 (inclusive) to 1 (exclusive)

4. Which function converts a float to an integer?
 b) Math.floor()

5. What will Math.floor(4.9) return?
 b) 4


Q4. Variables

1. How do you declare a variable in JavaScript?
 d) All of the above
(All three—var, let, and const—can be used to declare variables.)

2. Which variable type allows reassignment?
 b) let

3. Which keyword declares a block-scoped variable?
 c) let
 
4. What will happen if you use a variable without declaring it?
 b) It becomes a global variable (in non-strict mode) (⚠️ In strict mode, it will throw an error.)

5. Which keyword creates a constant in JavaScript?
 c) const


Q5. Functions

1. What is a function?
 b) A reusable block of code

2. How do you define a function named sayHello?
 a) function sayHello() {}

3. How do you call a function in JavaScript?
 c) sayHello()

4. What is the keyword to return a value from a function?
 c) return

5. What is a parameter in a function?
 b) A variable passed into a function

Q6. Mixed Concepts

1. What will typeof "hello" return?
 a) string

2. What does console.log() do?
 c) Outputs messages to the browser console

3. How do you write a comment in JavaScript?
 b) // comment

4. Which of these is a valid function expression?
 b) let add = function(x, y) { return x + y; }

5. What does NaN mean?
 a) Not a Number

6. Which method is used to convert a string to a number?
 a) parseInt()



Q. Bonus Conceptual Questions: Mandatory
1. Why is using let safer than var?
->
 a. Because let is block-scoped, while var is function-scoped.
 b. let prevents accidental overwriting or access outside the intended scope.
 c. var can lead to bugs due to hoisting and wider accessibility.

2. What is the main benefit of separating JavaScript from HTML?
->
a. Improved maintainability, reusability, and cleaner code structure.
b. Keeps HTML focused on structure/content.
c. Keeps JavaScript focused on logic/behavior.
d. Easier debugging and team collaboration.
e. Allows reusing the same script across multiple pages.

3. Why is Math.random() useful in games or UI effects?
->
a. It adds unpredictability and variety.
b. Used for random events (like dice rolls, enemy spawns, loot drops).
c. Enhances user engagement through dynamic effects or layout changes.

4. What happens if two event listeners are attached to the same element?
->
a. Both event listeners will run in the order they were added.
b. JavaScript allows multiple listeners on the same element.
c. Each function runs independently unless one uses event.stopPropagation() or event.preventDefault().

5. Why should we use functions to organize code?
->
a. Functions help with reuse, readability, and separation of logic.
b. Prevent code duplication.
c. Make debugging and testing easier.
d. Enable modular, maintainable code.
