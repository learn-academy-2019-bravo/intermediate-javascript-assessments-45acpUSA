# Intermediate Javascript Assessments

### Without using Google answer the following:

1. What is the difference between .map() and .filter()?
While both are higher-order functions (also known as iterator methods), .map() returns a new array with all the same elements after running through the intended logic within the block, while .filter() returns a new array with ONLY elements that pass a requirement set by the logic within the block.

2. Why would you use object destructuring?
Object destructuring allows for ease of access of the element you choose to destructure. You are now able to call upon the destructured element without having to type "this." every time which not only saves time as the developer, but allows for easier readability for other developers.

3. What is the difference between var, let, and const?
With regards to the development of JavaScript as a language, var preceded both let and const. While all are used as declarative keywords, they have different uses. In 2015, ES6 brought about let and const which allowed for more versatility of JS.

const is predominantly used when declaring a data type that is not intended to be reassigned. const actually prevents the reassignment of that data type, giving you an error message if attempted. This allows outside developers the ability to identify data types that are intended to be consistent throughout the block or entire file, depending on scope (although const is generally used to declare data types in the global scope). While data types declared with const cannot be reassigned, they remain mutable.

let, on the other hand, is used for data types that are intended to be reassigned allowing for higher functionality and versatility throughout the language. let is primarily used within the block scope because of the availability of reassignment. Data types declared with let are also mutable.

var, prior to ES6, was the only way to declare a data type. As more companies and developers are adopting the new syntax of ES6, var is becoming less common practice, although you may still see it used to declare data types in the global scope. Data types declared with var are mutable as well.

4. Why is testing important?
Testing is extremely important. Not only does it allow you to check whether your code fulfills its intended function, it can also check whether your code is dynamic enough to handle various cases. Almost every tech-based business requires testing as part of their common practice because it shows shareholders, clients and other non-developer personnel that the code is doing what it was intended for.

5. What is a higher order function?
A higher order function is a function that either takes in a function (commonly represented as an anonymous function) as an argument, returns a function or both. These specific functions are highly versatile and are great tools for developers.

6. What is the difference between a class and an object?
A class is a blueprint (or factory) for objects. Objects themselves have two key characteristics: attributes and behaviors. These are slightly different from hashes in Ruby, which only have attributes.

7. What did you learn during the group project this week? Please include any additional feedback you may have.
I learned a lot about interpersonal communication during the group projects this week. Without getting into too much detail, everyone has their own communication style and everyone should be sensitive to that. I believe it is everyone's responsibility to grow in their interpersonal communication skills and learn to deal with the various communication styles that one may come across.

I heard one suggestion from a fellow classmate that was, in my opinion, extremely intelligent and highly practical in this specific situation. In the situation that a few students are a little further along and receive a more advanced project, mob or pair programming may not be the best learning style because it is human nature to feel pride, which in turn inflates ones' ego and can cause disputes between the group members. The disputes can arise for a variety of reasons, but primarily because everyone thinks that their idea is the best and should be implemented. In this situation, the fellow student and I believe that working on the project alone, but in the same proximity of the other students would be a more effective strategy. This allows for each student to implement their ideas as well as seek guidance or help from their peers who are working to accomplish the same goal.


### HTML/CSS Review questions: First, try to answer each question on your own then Google the answer to further your knowledge.

1. How do you link a CSS file to your HTML page?
You link a CSS file to your HTML page within the <head> of the HTML page. You use the link tag along with the href attribute and set that equal to the string of the CSS file pathway (simply the file name if housed within the same directory).

Linking a JavaScript file is slightly different. Within the body, typically just above the closing body tag, you would use the oepning and closing <script> tags along with the attribute src and set that equal to the string of the JS file pathway (or simply the file name if housed within the same directory). This is typically located at the bottom of the body because everything in the HTML page linked to JS above these tags will be recognized. Anything below these tags (while still within the body) will not be recognized by the JS file.

2. What is the difference between a div and a span?

3. What is a CSS class? When should you use an id instead of a class?

4. Name 4 semantic HTML tags.

5. What are three options for creating responsive design?


### Stretch: The following questions are potential interview questions. First, try to answer each question on your own then Google the answer to further your knowledge.

1. What is front end development? Can you identify any tools/skills that are uniquely required of front end developers?

2. What is block scope in JavaScript?

3. How would you explain the idea of "inheritance" in object oriented programming?
