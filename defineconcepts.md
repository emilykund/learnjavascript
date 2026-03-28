# Javascript, HTML, & CSS, oh my!

I found these definitions/use cases via the W3 School for JavaScript and I thought it worked perfectly for differentiating between JS, HTML, and CSS, that I'm borrowing it (with atrribution, obviously). 

JavaScript is one of the 3 languages all web developers must learn:

- HTML to define the content of web pages

- CSS to specify the layout of web pages/ to style it

- JavaScript to program the behavior of web pages

# Core concepts

When I thought about learning JavaScript, I thought about needing to understand how a page/content is structured. From there, I thought about how the content within the bigger elements are structured to display content. That's when it hit me that the bigger structure is like the page. The structure of code on the page is the content like sentences, tables, images, etc. JavaScript programs are the scripts (or code that composed of) statements that use variables, values, operators, expressions, and keywords to perform actions. This analogy works for me as I learn it. I think of it like learning Language Arts/English in school. It's the grammar and all of those things we learned when we learned how to communicate in writing in school. It kinda is like learning another language.

It's not just understanding the definitions but understanding how the concepts are applied.  That's why I have the concept and then an example of the application.  If I keep the language arts theme going, it's kind of like a spelling bee. What's the word and how is it used in a sentence? What's the concept and how is it used in the code?

We'll cover the following core concepts in this section:
- Variables
- Values
- Data types
- Functions
- Control flow
- Document Object Model (DOM)
  

**Variables are containers that store data values**
There are two types of variables variable declarations; ones that change and one that remain constant. Use a keyword ```let``` for variables that can change and ```const``` for variables that remain constant. 

    Example: 

    Using let (the value can be changed)
    ```let``` userName = "John";
    ```let``` userAge = 25;

    Using const (value cannot be changed after assignment)
    ```const``` pi = 3.14159;
    ```const``` siteName = "MDN Web Docs";

**Application** <br>
<img width="777" height="345" alt="Search and Value code" src="https://github.com/user-attachments/assets/13509f95-f341-46e7-9014-2511be6cc1cf" />

<img width="777" height="150" alt="Searchboxandtext" src="https://github.com/user-attachments/assets/1b5cfd5d-c02a-44cf-a919-26b740d5d114" />


The ```const``` variable is the search box <br>
The ```let``` variable is what you put in the search box

**Values: Stored in a variable**
In the Variables example above, the ```values``` are "John", 25, 3.14159, and "MDN Web Docs"

As we can see, values can be different types of data.        

**Data types:**
There are eight data types, which are categorized into two groups: primitive and non-primitive (reference) types. JavaScript is a dynamically typed language, meaning a variable can hold different data types at different times. To go back to our search box example above, the variable that allows us to type in a search term, allows for different data types. We could search for text/strings, numbers, and more. One search could be numeric while another could be sting.  Different data types and different times. 

*Primitive data types* are:
  · Numbers (intergers and floating point numbers),
  · Strings "Hello, world!", 
  · Booleans (true/false---typically used for conditional logic), and 
  · Objects (which store collections of data) 

They are a single value and are immutable (can't be changed).  As I was looking for the best plain language way of learning about these so that I could document it here, I thought,"And this is where it gets confusing. They can't be changed?  How does it work with the const and let keywords I just learned about?" 

Good ole Google to the rescue. I typed in what I wanted to know and viola!
```
let name = "Alice";
// In memory: A string "Alice" is created, and the variable 'name' points to it.

name = "Bob";
// In memory: A *new* string "Bob" is created. 
// The variable 'name' now points to "Bob". 
// The original "Alice" is untouched and eventually removed from memory.
```
There are two important points for me to remember: 
1. What looks like a change can actually be a reassignment.
2. ```Let``` lets you change the variable's value, typically through reassigning the value.

*Non-primative data types*:
These are data that can be changed and are also referred to as reference types. I actually prefer reference types to non-primative because to me, based on the following definition and description I found, it makes sense.  These are data that can hold collections of data that are objects, arrays, or functions. The variable can have the contents of its objects, arrays, or functions change. What makes it a reference type is that the variable is referring to the object, array, or function (in memory), not to the values themselves.

**Application**

We see the non-primative data types in action with the following real life examples. 

Objects <br>
User Profiles: Storing a user's details like their name, age, email, and address in a single, organized structure. <br>


https://cdn.dribbble.com/userupload/44898530/file/1adea1742f4bd3081e78d2298261577f.jpg?resize=752x&vertical=center<img width="2048" height="1536" alt="image" src="https://github.com/user-attachments/assets/38a62bf8-9bc7-4795-ae49-0c0dfa42b55c" />


  
**Functions: Reusable blocks of code that perform specific tasks**
Functions are essential for structuring code & executing the same logic multiple times without having repeat the same code. 

**Control flow: The order in which statements are executed**
If then/else statements are a good example of this.

**DOM (Document Object Model): Provides the ability to interact with the web page's structure**










  
