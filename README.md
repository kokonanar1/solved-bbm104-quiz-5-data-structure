Download Link: https://assignmentchef.com/product/solved-bbm104-quiz-5-data-structure
<br>



<h1>Problem1: Display octal equivalents of decimal numbers</h1>

Write a main program that takes decimal numbers(between 1000-200000) from an input file (decimal.txt) as an argument and put them into any data structure, then finds and displays their octal equivalents by using a stack (octal.txt), i.e convert the number with base value 10 to base value 8.

Create a Stack class with:

<ul>

 <li>One constructor</li>

 <li>Push</li>

 <li>Pop</li>

 <li>Top</li>

 <li>isFull()</li>

 <li>isEmpty()</li>

 <li>Size</li>

</ul>

You must use ONLY stack(s) for decimal-to-octal operation, don’t use other data structures such as normal array, string etc.

<strong>Algorithm:</strong>

<ul>

 <li>Store the remainder when the number is divided by 8 into a stack.</li>

 <li>Divide the number by 8 now</li>

 <li>Repeat the above two steps until the number is not equal to 0.</li>

 <li>Print the content now.</li>

</ul>

Figure 1: Representation of decimal-to-octal