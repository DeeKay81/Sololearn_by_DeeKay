<h3>What is JavaScript?</h3>
JavaScript is a text-based programming language used both on the client-side and server-side
that allows you to make web pages interactive. Where HTML and CSS are languages that give
structure and style to web pages, JavaScript gives web pages interactive elements that engage a
user. Common examples of JavaScript that you might use every day include the search box on Amazon,
a news recap video embedded on The New York Times, or refreshing your Twitter feed.
<hr />
<h3>What is JavaScript used for?</h3>
JavaScript is mainly used for web-based applications and web browsers. But JavaScript is also
used beyond the Web in software, servers and embedded hardware controls. Here are some basic
things JavaScript is used for:
<ul>
    <li>Adding interactive behavior to web pages</li>
    <li>Creating web and mobile apps</li>
    <li>Building web servers and developing server applications</li>
    <li>Game development</li>
</ul>
<hr />
<h3>Basics:</h3>
<ul>
<li>inside an html doc you have to use 'script' to write js</li>
<li>in html you should usually use hyphens (also in doc names) - spiritualize it use google chrome 
for testing (it's requirements are much more strict than in other browsers;</li>
<li>means: if it doesn't work in chrome, you'll have to look closer)</li>
<li>JS is case sensitive (lastName and lastname are two different variables!)</li>
<li>'var' is still a common way to create variables, but the modern way is 'let' (both are allowed 
... yet)</li>
<li>first character of a variable name must be a letter, underscore (_), or a dollar sign ($)</li>
<li>Subsequent characters can be letters, digits, underscores, or dollar signs</li>
<li>first character of a variable name can’t be a number.</li>
<li>variable names can’t include a mathematical or logical operator in their name</li>
<li>(for instance, 2*something or this+that)</li>
<li>variable names can’t contain spaces</li>
<li>you’re not allowed to use any special symbols, like my#num, num%, etc.</li>
<li>JS is a hyphen free zone (they’re reserved for subtractions)</li>   
</ul>
<hr />
<h3>Datatypes:</h3>
Read through: <a href="https://www.programiz.com/javascript/data-types">Programize - Data Types</a>
<p>Overview - basic data types:</p>
<li>string</li>
<li>number</li>
<li>BigInt</li>
<li>boolean</li>
<li>undefined</li>
<li>null</li>
<li>symbol</li>
<li>object</li>
<hr />
<h3>Operators:</h3>
Find more on this page: <a href="https://www.programiz.com/javascript/operators">Programize - 
JavaScript Operators</a>
<h5><u>Arithmetic Operators:</u></h5>
Take a look at this picture over here: <a href="https://api.sololearn.com/DownloadFile?id=2745">get 
pic</a>
<br>
Ok, we all know the basics, but what does this 'increment' or 'decrement' do?<br>
<p>The increment operator increases the numeric value of its operand by 1. When placed before the 
operand, it’ll return the incremented value. When placed after it, it’ll return the original value 
and then increments the operand.</p>
<p>The decrement operator decreases the numeric value of its operand by 1. When placed before the 
operand, it’ll return the decremented value. When placed after the operand, it’ll return the 
original value and then decrements the operand.</p>
Let's say we have a variable x = 5 ...
<br>
Increment and Decrement see at this <a href="increment_decrement.html">increment_decrement.html</a> 
file. Run it in your chrome browser.
For an arithmetical example go to the <a href="practice.html"> practice.html</a> (task: office 
computers).
<h5><u>Assignment Operators:</u></h5>
Take a look at this picture over here: <a href="https://api.sololearn.com/DownloadFile?id=2747">get 
pic</a>.
They are used to assign values to variables.
<h5><u>Comparison Operators:</u></h5>
Take a look at this picture over there: <a href="https://api.sololearn.com/DownloadFile?id=2748"> 
get pic</a>.
We can use comparison operators in logical statements to find out if variables or values are 
different.
<br>
For a comparison example go to the <a href="practice.html"> practice.html</a> (task: find the adults).
<h5><u>Logical Operators:</u></h5>
Take a look at this picture over there: <a href="https://api.sololearn.com/DownloadFile?id=2749"> 
get pic</a>.
Logical Operators are also known as Boolean Operators, evaluate an expression and return true or 
false.
With logical operators you can connect as many expressions as you want or need to.
<br>
For a boolean example go to the <a href="practice.html"> practice.html</a> (task: noon or midnight).
<hr />
<h3>if / else if / else Statements:</h3>
You can use the JavaScript if...else statement to create a program that can make decisions. We use 
<strong>if</strong> to specify a block of code that we want to be executed if a specified condition 
is true. We can use the <strong>else</strong> statement to specify a block of code that will execute 
if the condition is false. The <strong>else if</strong> statement is useful because it lets us 
specify a new condition if the first condition is false.<br>
For a if, else if, else example go to the <a href="practice.html"> practice.html</a> (if, else if, else 
example).
<hr />
<h3>switch Statement:</h3>
In case of need to test multiple condition, you can use the switch statement. The switch statement 
evaluates an expression and executes the corresponding body that matches the expression's result.
<br>
For a switch example go to the <a href="practice.html"> practice.html</a> (switch example).
<br>
<li>The break statement is optional. If the break statement is encountered, the switch statement ends.</li>
<li>If the break statement is not used, the cases after the matching case are also executed.</li>
<li>The default clause is also optional.</li>
Let's do another example. Go to the <a href="practice.html"> practice.html</a> (dark theme).
<hr />
<h3>Loops:</h3>
For example, if you want to show a message 100 times, then you can use a loop. It's just a simple example; you can achieve much more with loops.
<h5><u>for loop:</u></h5>
for (initialExpression; condition; updateExpression) {<br>
    // for loop body<br>
}
<ol>
<li>The initialExpression initializes and/or declares variables and executes only once.</li>
<li>The condition is evaluated.
    <ul>
    <li>If the condition is false, the for loop is terminated.</li>
    <li>If the condition is true, the block of code inside the for loop is executed.</li>
    </ul>
</li>
<li>The updateExpression updates the value of initialExpression when the condition is true.</li>
<li>The condition is evaluated again. This process continues until the condition is false.</li>
</ol>
For a for loop example go to the <a href="practice.html"> practice.html</a> (for loop example).
<br>
Take a look at this picture over there: <a href="for_loop_screenshot.png">explain for loop (screenshot)</a>.
<br>
Let's do another quick exercise: <a href="practice.html">practice.html</a> (for loop reputation).
<h5><u>while loop:</u></h5>
The while loop repeats through a block of code, but only as long as a specified condition is true.
The condition can be any conditional statement that returns true or false.
<p>
while (condition) {<br>
    // body of loop<br>
}
</p>
<ol>
<li>A while loop evaluates the condition inside the parenthesis ().</li>
<li>If the condition evaluates to true, the code inside the while loop is executed.</li>
<li>The condition is evaluated again.</li>
<li>This process continues until the condition is false.</li>
<li>When the condition evaluates to false, the loop stops.</li>
</ol>
For a for loop example go to the <a href="practice.html"> practice.html</a> (while loop example).
<br>
Take a look at this picture over there: <a href="while_loop_screenshot.png">explain while loop (screenshot)</a>.
<h5><u>do/while loop:</u></h5>
This loop will execute the code block once, before checking if the condition is true, and then it 
will repeat the loop as long as the condition is true.

let number = 15;<br>
do {<br>
document.write(number);<br>
number++;<br>
}<br>
while (number <= 25);

This example prints out numbers from 15 to 25. Note the semicolon used at the end of the 
do...while loop. This is important. The loop will always be executed at least once, even if the 
condition is false, because the code block is executed before the condition is tested.
<h5><u>break and continue:</u></h5>
The break statement is used to terminate the loop immediately when it is encountered. It's almost 
always used with decision-making statements. When break is used inside of two nested loops, break 
terminates the inner loop. When using nested loops, you can also terminate the outer loop with a 
label statement. However, labeled break is rarely used in JavaScript because this makes the code 
harder to read and understand. The break statement is also used with switch statements.
<br><br>
The continue statement is used to skip the current iteration of the loop and the control flow of the 
program goes to the next iteration. The continue statement also is almost always used with 
decision-making statements. The break statement terminates the loop entirely. However, the continue 
statement only skips the current iteration.<br>
In a for loop, continue skips the current iteration and control flow jumps to the updateExpression.
In a while loop, continue skips the current iteration and control flow of the program jumps back to 
the while condition. The continue statement works in the same way for while and do...while loops.
When continue is used inside of two nested loops, continue skips the current iteration of the inner 
loop. When using nested loops, you can skip the current iteration and the control flow of the 
program can be passed to a label statement's updateExpression. But labeled continue is rarely used 
in JavaScript because this makes the code harder to read and understand.
<br>
Let's have an example output. Go to the <a href="practice.html">practice.html</a> (break and continue).
<hr />
