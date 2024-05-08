
<h1>What is HTML?</h1>
<ul>
<li>HyperText Markup Language is the foundation of everything digital as it serves as a channel for different types of content</li><br> 
<li>HTML is straightforward as it is a declarative language that gives it it's simplicity.</li>
<li>HTML uses tags to markup different elements as it is a language used to structure web pages</li>
<li>HTML markup is a bridge or connection between the human world and computers it achieves this by giving meaning to content and helping computers understand it</li><br>
<li>When nesting elements to each other you need to pay attention to how you open and close tags as this helps convey meaning about the content and interface <br>
<li>HTML elements marking up headlines come in six different types and they convey a hierarchy in how the browser interprets the page.<br>
<li>This hierarchical system is used distingsh what is most important from what is less important, this helps users easily navigate the page<br>
<li>Tags come in # HTML-CSStwo types, open < p> and closed< /p> these tags work together to define elements<br>
<li>Some paragraphs have an emphasized tag < em> and </ em><br>
<li>Headline tags are i hierarchical form for example < h1> </ h1> to < h6></ h6> with h6 being the smallest<br> 
<li>We use the < p> tag to tell the browser to separate the paragraphs<br>
<li>There are two elements for bold and there are two for italic
for Bold we use < b> and < strong> and for italic we you < i> and < em><br>
<li>We also use a definition list that uses the tags < dl> but yet for definations that are specific we use different tags like< dt> for defination term<br>
<li>For a defination description we use the tags < dd><br>
<li>HTML elements also help us cover qoutes
<li>For us to be able to attribute the person who said the words we use < cite> element after doing that we wrap the whole thing up with < blockqoute> element these elements are used for interpretation as they provide a convinient wayto apply customer styling <br>
<li>HTML attributes addmore to HTML elements for exsmple datetime attributes allow us to write specific time and date in a way that allows the compute to understand like <time datetime="2024-03-07">March 7, 2024</time>.</ul><br><br>
<h2>HTML Capabilities: Troubleshooting and Debugging</h2><br><br>
<li>In HTML involves identifying issues that may arise in your web pages. Validation: ensures your HTML code follows specifications by using online validation services.</li>
<li>HTML attributes: are used to define the characteristics of elements. 
All HTML tags have some attributes along with some default values.
The attributes are usually made up of two parts, the name and value (name= "value"). 
For example, if you want to change the background colour to red, bicolor will be your name and value will be red.</li>


  
<br><br>
<h2>Working with Forms and Interactive Elements</h2><br>
<li>HTML Form is a section of the document that collects input from the user.</li>
<li>A form contains special interactive elements that users use to insert data.</li>
<li>The HTML < input> tag defines the field where the user can enter data.</li>
<li>type - determines the type of input the <input> tag takes.<br><br>
 # Types of inputs include text, date, email, button, checkbox etc.</li><br><br>
 <h2>HTML Form Action:POST and GET</h2><br><br>
 <li>The method attribute in the form element specifies how the data is sent to the server.</li>
 <li>Using the < action> attribute. define the action to be performed when the form is submitted. It is usually the URL for the server where the form data is to be sent.</li>
 <li>GET method - used to request data from a specified resource.</li>
 <li>POST method - used to send data to a server to update a resource.</li><br><br>
 <h1>Introduction to CSS.</h1><br>
 <p>CSS is used to make web pages look better and more appealing.<br>
It stands for Cascading Style Sheets.<br>
We can style the web pages by changing fonts, colors and spacing.</p><br><br>
<h2>CSS synta:</h2><br><br>
<h4>CSS has two parts:<br></h4>
<li>The selector-which points to the html elements you want to style.</li>
<li>The declaration box- which contains one or more declarations separated by a semicolon.</li><br><br>
<h2>CSS Selectors</h2>
<h4>CSS selectors can be divided into five categories:</h4><br><br>
<li>Simple selectors</li>
<li>Combinator selectors</li>
<li>Pseudo class selectors</li>
<li>Pseudo element selectors</li>
<li>Attribute selectors</li><br><br>
<h2>The CSS element selector</h2>
The element selector selects the html elements based on the element name.<br.
Example:  p: {text-align: center; color: blue; }<br>
Here all the <p> elements will be center aligned, with a blue text color.<br><br>
<h2>The CSS Id selector</h2>

<li>The Id selector selects the html element with specific Id attribute.</li>
<li>It is written with the (#) character, followed by the Id of the element.</li><br><br>
<h2>The CSS class selector</h2><br><br>
<li>The CSS class Selector selects the Html elements with a specific class attribute.</li>
<li>To select elements with specific class, write a period character (.), followed by the class name.</li><br><br>
<h2>Grouping selectors</h2>
<li>The group selector is used to select all the elements with the same style definition.</li>
<li>Commas are used to separate each selector in grouping.</li><br><br>
<h2>CSS Images & Colours</h2><br>
<li>The background-color property sets the background color of an element.</li> 
<li>It applies to the entire size of the element, including padding and border (but not the margin). </li>
<li> To ensure readability, choose a background color that contrasts well with the text color.</li><br><br>
<h2>The syntax for setting the background color</h2><br>
<li>Altering the color of the text can add visual interest or align with a specific design scheme.</li>
  <li> The color property is used to set the color of the text.</li><br><br>
  <h2>Understanding Images in CSS</h2><br>
 <li> <b>JPEG (Joint Photographic Experts Group):</b> It uses lossy compression, meaning that the image quality may be slightly degraded in order to reduce file size.</li>

<li><b>PNG (Portable Network Graphics):</b> PNG images use lossless compression, meaning that image quality is preserved without sacrificing file size. </li>

<li><b> GIF (Graphics Interchange Format):</b> GIF images support transparency and animation, making them popular for memes and social media content.</li>

The syntax for setting the back-ground image:
       body{
          background-image:url(‘the.png’);
          }<br><br>
<h2>CSS Boxes, Sizes & Types</h2>
<li>The fonts, height, width, margins, padding, etc. are set on a web page with the length units. For example, height 100px, width 100px, font 2em, etc. </li>
<li>These length units are categorised into Absolute and Relative Units.</li>
<li>CSS uses a box model to define the size of elements on a web page.</li>
<br><br>
<h1>Introduction to JavaScript:</h1>
<li>JavaScript, often abbreviated as JS, was created by Brendan Eich in 1995 while he was working at Netscape Communications Corporation.</li>
<li>Initially developed as a scripting language for web browsers to enhance HTML pages with interactivity.</li><br>
<h2>Key Features:</h2>
<li>Client-Side Scripting: Primarily used for client-side web development to make web pages interactive.</li>
<li>Versatility: Can be used for both front-end and back-end development (Node.js).</li>
<li>Dynamic Typing: Variables are not explicitly typed, allowing flexible data handling.</li>
<li>Prototype-based: Object-oriented language where objects inherit properties and methods directly from other objects.</li>
<li>Event-Driven: Responds to events triggered by user actions or system events.</li>
<li>Asynchronous: Supports asynchronous programming with features like callbacks, promises, and async/await.</li><br>
<h2>Syntax:</h2>
<li>Syntax is similar to C-based languages such as Java and C++, making it relatively easy to learn for programmers familiar with those languages.</li>
<li>JavaScript code is executed by web browsers' JavaScript engines.</li><br>
<h2>Basic Syntax Examples:</h2>
// Hello World program<br>
console.log("Hello, World!");<br>
<h2>Data Types:</h2>
<li>Primitive: Number, String, Boolean, Undefined, Null, Symbol (added in ECMAScript 6).</li>
<li>Non-primitive (Reference types): Objects, Arrays, Functions.</li><br>
<h2>Control Structures:</h2>
<li>Conditional Statements: if-else, switch-case.</li>
<li>Looping Constructs: for, while, do-while.</li><br>
<h2>Functions:</h2>
<li>JavaScript functions are first-class objects, meaning they can be passed around like any other object.</li>
<li>Can be defined using the 'function' keyword or as arrow functions (introduced in ECMAScript 6).</li><br>
<h2>Objects and Prototypes:</h2>
<li>JavaScript is object-oriented, where objects are collections of key-value pairs.</li>
<li>Objects can inherit properties and methods from other objects through prototypes.</li><br>
<h2>Arrays:</h2>
<li>Arrays are ordered collections of elements, and they can contain elements of different data types.</li>
<li>Various built-in methods are available for array manipulation, such as 'push()', 'pop()', 'slice()', 'map()', 'filter()', etc.</li><br>
<h2>DOM Manipulation:</h2>
<li>Document Object Model (DOM) represents the structure of HTML documents.</li>
<li>JavaScript can manipulate the DOM dynamically to change the content, structure, and style of web pages.</li><br>
<h2>Event Handling:</h2>
JavaScript can respond to various events such as clicks, keypresses, mouse movements, etc., using event listeners.<br>
<h2>Asynchronous Programming:</h2>
JavaScript supports asynchronous programming to handle tasks that might take some time to complete, such as fetching data from a server or reading files.<br>
<h2>Modules:</h2>
<li>ECMAScript 6 introduced the concept of modules for organizing and encapsulating JavaScript code.</li>
<li>Modules allow for better code organization, reusability, and maintainability.</li><br>
<h2>Popular Libraries and Frameworks:</h2>
<li>Front-end: React.js, AngularJS, Vue.js.</li>
<li>Back-end: Node.js, Express.js.</li>
<li>Testing: Jasmine, Mocha, Jest.</li><br>
<h2>Development Tools:</h2>
<li>Various integrated development environments (IDEs) and text editors support JavaScript development, including Visual Studio Code, Sublime Text, Atom, etc.</li>
<li>Debugging tools like Chrome DevTools are widely used for debugging JavaScript code in web browsers.</li>

<h1>Introduction to Java</h1>
<li>Origin: Java was created by James Gosling at Sun Microsystems in 1995. Initially developed for consumer electronics, it quickly found its niche in web development.</li>
<li>Name Change: Originally named Oak, it was later renamed Java, inspired by the coffee consumed by the development team.</li>
<h2>Key Features:</h2>
<li>Platform Independence: Java programs are compiled into bytecode, which can run on any device with a Java Virtual Machine (JVM). This enables "write once, run anywhere" (WORA) capability.</li>
<li>Object-Oriented: Java follows the object-oriented programming paradigm, emphasizing modularity and reusability through classes and objects.</li>
<li>Robust: Java's robustness stems from features like automatic memory management (garbage collection), strong type checking, and exception handling.</li>
<li>Secure: The Java platform incorporates security features such as bytecode verification and a security manager to protect systems from malicious code.</li>
<li>High Performance: Java achieves high performance through Just-In-Time (JIT) compilation, where bytecode is translated into machine code at runtime for efficient execution.</li>
<h2>Java Virtual Machine (JVM):</h2>
<li>Execution Environment: JVM provides a platform-independent execution environment for Java bytecode.</li>
<li>Memory Management: JVM manages memory allocation and deallocation, including garbage collection.</li>
<li>Platform Specific Implementations: Different JVM implementations exist for various operating systems and architectures, ensuring compatibility across diverse environments.</li>
<h2>Syntax:</h2>
<li>Java syntax resembles C and C++, making it familiar to programmers from those languages.</li>
<li>Every Java application must contain at least one class with a main() method, serving as the entry point for execution.</li>
<h2>Basic Syntax Examples:</h2>
<p>The "Hello World" program demonstrates the simplest Java syntax, where System.out.println() prints a message to the console.</p>
<h2>Data Types:</h2>
<li>Primitive Data Types: These include numeric types (byte, short, int, long, float, double), character type (char), and boolean type (boolean).</li>
<li>Non-primitive Data Types: Arrays, Strings, and Classes are examples of non-primitive data types.</li>
<h2>Control Structures:</h2>
<li>Conditional Statements: Java supports if-else and switch-case statements for decision-making.</li>
<li>Looping Constructs: for, while, and do-while loops enable repetitive execution of code blocks.</li>
<h2>Object-Oriented Programming (OOP):</h2>
<li>Classes and Objects: Classes define the blueprint for creating objects, encapsulating data and behavior.</li>
<li>Inheritance: Subclasses can inherit properties and behaviors from a superclass, promoting code reuse.</li>
<li>Polymorphism: Java supports polymorphism, where objects of different classes can be treated interchangeably through method overriding and method overloading.</li>
<li>Encapsulation and Abstraction: Encapsulation hides internal state and requires interaction through well-defined interfaces. Abstraction emphasizes essential characteristics while hiding implementation details.</li>

<br><br>
<h1>What is Python?</h1>
Python is a high-level, general-purpose, and very popular programming language.<br> Python programming language (latest Python 3) is being used in web development, and Machine Learning applications, along with all cutting-edge technology in Software Industry.<br> Python language is being used by almost all tech-giant companies like – Google, Amazon, Facebook, Instagram, Dropbox, Uber…<br>

<h2>Python Data Types</h2>
<li>Strings</li>
<li>Numbers</li>
<li>Booleans</li>
<li>Python List</li>
<li>Python Tuples</li>
<li>Python Sets</li>
<li>Python Dictionary</li>
<li>Python Arrays</li>
<li>Type Casting</li>
<br>
<h3>Strings:</h3>
Strings represent sequences of characters enclosed within single quotes (''') or double quotes ('"').<br>
message = "Hello, World!"<br>
print(message)  # Output: Hello, World!<br>
<h3>Numbers:</h3>
Python supports various numeric types, including integers, floating-point numbers, and complex numbers.<br>
x = 10  # Integer<br>
y = 3.14  # Float<br>
z = 5 + 2j  # Complex<br>
<h3>Booleans:</h3>
Booleans represent truth values, either True or False.<br>
is_valid = True<br>
has_error = False<br>
<h3>Lists:</h3>
Lists are ordered collections of items, mutable (modifiable), and enclosed within square brackets ('[]').<br>
fruits = ["apple", "banana", "cherry"]<br>
fruits.append("orange")<br>
print(fruits)  # Output: ['apple', 'banana', 'cherry', 'orange']<br>
<h3>Tuples:</h3><br>
Tuples are ordered collections of items, immutable (cannot be modified), and enclosed within parentheses ('()').<br>
coordinates = (10, 20)<br>
x, y = coordinates<br>
print(x)  # Output: 10<br>
<h3>Sets:</h3>
Sets are unordered collections of unique items, enclosed within curly braces ('{}'). Sets do not allow duplicate elements.<br>
unique_numbers = {1, 2, 3, 4, 5}<br>
<h3>Dictionary:</h3>
Dictionaries are unordered collections of key-value pairs, enclosed within curly braces ('{}'). Keys are unique within a dictionary.<br>
<h3>Arrays:</h3>
Arrays are not built-in data types in Python, but you can use lists or the array module for similar functionality.<br>
import array<br>
nums = array.array('i', [1, 2, 3, 4, 5])  # 'i' denotes integer type<br>
<h3>Type Casting:</h3>
Type casting is the process of converting one data type into another.<br>
num_str = "10"<br>
num_int = int(num_str)  # Convert string to integer<br>




