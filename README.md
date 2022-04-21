<h2>What is java?</h2>

Java is one of the most popular languages in the coding world! It is owned by Oracle, and more than 3 billion devices run Java.
It is used for:
* Mobile applications (specially Android apps)
* Desktop applications
* Web applications
* Web servers and application servers
* Games
* Database connection
* And much, much more!

<h2>Why Use Java?</h2>

* Java works on different platforms (Windows, Mac, Linux, Raspberry Pi, etc.)
* It is one of the most popular programming language in the world
* It is easy to learn and simple to use
* It is open-source and free
* It is secure, fast and powerful
* It has a huge community support (tens of millions of developers)
* Java is an object oriented language which gives a clear structure to programs and allows code to be reused, lowering development costs.

<h3>Getting Started </h3>

We will be using JDoodle online compiler to learn coding in java. You don’t have to install anything on your system.

<h3>Hello World</h3>

System.out.println() is used to print something on the computer screen.

Write the following code in the Jdoodle compiler and press execute.

![Screenshot 2022-04-21 at 1 50 08 PM](https://user-images.githubusercontent.com/100328396/164412746-8612b915-4b68-446d-9523-5190e98f2a13.png)

Don't worry if you don't understand the code above - we will discuss it in detail in later chapters. For now, focus on how to run the code above.
The output should be:

![Screenshot 2022-04-21 at 1 50 08 PM](https://user-images.githubusercontent.com/100328396/164413136-335e3465-a33a-486e-bdf4-1ca8f1ea35ee.png)

Congratulations! You have written and executed your first Java program.

<h4>Java Syntax</h4>

Syntax basically means the correct structure to write code in Java.

![Screenshot 2022-04-21 at 1 50 08 PM](https://user-images.githubusercontent.com/100328396/164413593-63b5a393-179e-445d-a317-c0d408b6f3c0.png)

<p>Every line of code that runs in Java must be inside a class. In our example, we named the class Main. A class should always start with an uppercase first letter.</p>
<p>Note: Java is case-sensitive: "MyClass" and "myclass" has different meaning.</p>

The name of the java file must match the class name.

<h4> The main method </h4>

The main() method is required and you will see it in every Java program:

![Screenshot 2022-04-21 at 8 51 56 PM](https://user-images.githubusercontent.com/100328396/164491570-81715b34-78c8-42ef-8f8a-4d66bce44f5a.png)

<p>Any code inside the main() method will be executed. Don't worry about the keywords before and after main. You will get to know them bit by bit while learning Java.</p>
For now, just remember that every Java program has a class name which must match the filename, and that every program must contain the main() method.

<h4> System.out.println() </h4>

Inside the main() method, we can use the println() method to print a line of text to the screen:

![Screenshot 2022-04-21 at 8 53 57 PM](https://user-images.githubusercontent.com/100328396/164491963-a80666c3-b895-4342-995a-02e7bcc4031a.png)

<p>Note: The curly braces {} marks the beginning and the end of a block of code.</p>
<p>System is a built-in Java class that contains useful members, such as out, which is short for "output". The println() method, short for "print line", is used to print a value to the screen (or a file).</p>
<p>Don't worry too much about System, out and println(). Just know that you need them together to print stuff to the screen.</p>

You should also note that each code statement must end with a semicolon (;).

You can add as many println() methods as you want. Note that it will add a new line for each method:

![Screenshot 2022-04-21 at 9 00 02 PM](https://user-images.githubusercontent.com/100328396/164494814-48b9cebd-5121-4b0f-96e4-1b4a649a0205.png)

Output:

![Screenshot 2022-04-21 at 9 01 09 PM](https://user-images.githubusercontent.com/100328396/164495485-f235f12f-6a9b-4055-bcdf-50323338f9d5.png)

You can also output numbers, and perform mathematical calculations:

![Screenshot 2022-04-21 at 9 02 06 PM](https://user-images.githubusercontent.com/100328396/164496069-411b4a27-4d4a-4dc6-a57a-e666056840d8.png)

Note that we don't use double quotes ("") inside println() to output numbers.


Output:

![Screenshot 2022-04-21 at 9 08 22 PM](https://user-images.githubusercontent.com/100328396/164498067-eb63668f-c2d2-4b72-94bf-5a4b4d2f4f41.png)



There is also a print() method, which is similar to println().

The only difference is that it does not insert a new line at the end of the output:

![Screenshot 2022-04-21 at 9 05 26 PM](https://user-images.githubusercontent.com/100328396/164497468-93d65590-0a95-4eac-a5ef-e4274288e6c5.png)


Output:

![Screenshot 2022-04-21 at 9 06 06 PM](https://user-images.githubusercontent.com/100328396/164497612-1cd64ed3-d90c-4be8-b407-653a05d9d93e.png)

<h3>Java Comments</h3>

Comments can be used to explain Java code, and to make it more readable. It can also be used to prevent execution when testing alternative code.

<h4>Single-line Comments</h4>

Single-line comments start with two forward slashes (//).

Any text between // and the end of the line is ignored by Java (will not be executed).

This example uses a single-line comment before a line of code:

![Screenshot 2022-04-21 at 9 10 33 PM](https://user-images.githubusercontent.com/100328396/164498534-c9393c36-7c29-420c-b6a3-43d4af8dc026.png)

Output:

![Screenshot 2022-04-21 at 9 11 18 PM](https://user-images.githubusercontent.com/100328396/164498682-3ae0be73-c4d5-4dbf-b815-5e766c2bc127.png)

<h3>Java Multi-line Comments</h3>

Multi-line comments start with /* and ends with */.

Any text between /* and */ will be ignored by Java.


Ths example uses a multi-line comment (a comment block) to explain the code:

![Screenshot 2022-04-21 at 9 15 25 PM](https://user-images.githubusercontent.com/100328396/164499527-7c669d67-5540-417d-a12a-fd75366a6e8e.png)

Output:

![Screenshot 2022-04-21 at 9 15 54 PM](https://user-images.githubusercontent.com/100328396/164499629-92190eb5-7ed1-40bb-b20b-4bb88448a6c9.png)

Single or multi-line comments?

It is up to you which you want to use. Normally, we use // for short comments, and /* */ for longer.

<h3>Java Variables</h3>

Variables are containers for storing data values.

In Java, there are different types of variables, for example:

* String - stores text, such as "Hello". String values are surrounded by double quotes
* int - stores integers (whole numbers), without decimals, such as 123 or -123
* float - stores floating point numbers, with decimals, such as 19.99 or -19.99
* char - stores single characters, such as 'a' or 'B'. Char values are surrounded by single quotes
* boolean - stores values with two states: true or false

<h4>Declaring (Creating) Variables</h4>

To create a variable, you must specify the type and assign it a value:

Syntax:

<i>type variableName=value</i>

Where type is one of Java's types (such as int or String), and variableName is the name of the variable (such as x or name). The equal sign is used to assign values to the variable.

The general rules for naming variables are:

* Names can contain letters, digits, underscores, and dollar signs
* Names must begin with a letter
* Names should start with a lowercase letter and it cannot contain whitespace
* Names can also begin with $ and _ (but we will not use it in this tutorial)
* Names are case sensitive ("myVar" and "myvar" are different variables)
* Reserved words (like Java keywords, such as int or boolean) cannot be used as names

To create a variable that should store text, look at the following example:

Create a variable called name of type String and assign it the value "John":

![Screenshot 2022-04-21 at 9 21 28 PM](https://user-images.githubusercontent.com/100328396/164500710-54eda021-c52f-4c04-baa3-7f7eac820d4c.png)

Output:

![Screenshot 2022-04-21 at 9 22 05 PM](https://user-images.githubusercontent.com/100328396/164500848-5a29c1e7-d70a-4753-bb8f-b7bdd7715099.png)

To create a variable that should store a number, look at the following example:

![Screenshot 2022-04-21 at 9 22 51 PM](https://user-images.githubusercontent.com/100328396/164501022-9f1cdd60-1a67-409a-930a-a36c779440a0.png)

Output:

![Screenshot 2022-04-21 at 9 23 39 PM](https://user-images.githubusercontent.com/100328396/164501171-836d0e66-0896-488c-b563-ad2f4c667a8c.png)

You can also declare a variable without assigning the value, and assign the value later:

![Screenshot 2022-04-21 at 9 24 19 PM](https://user-images.githubusercontent.com/100328396/164501295-8dfd190a-e8ce-419c-9de0-e2f84a401dad.png)

Output:

![Screenshot 2022-04-21 at 9 24 57 PM](https://user-images.githubusercontent.com/100328396/164501425-7f6d4193-828f-459b-8cae-c908931acebe.png)

Note that if you assign a new value to an existing variable, it will overwrite the previous value:

![Screenshot 2022-04-21 at 9 25 54 PM](https://user-images.githubusercontent.com/100328396/164501619-365ca8f5-21d0-4365-9741-da13841c2072.png)

Output:

![Screenshot 2022-04-21 at 9 26 21 PM](https://user-images.githubusercontent.com/100328396/164501702-954f5a30-9b1f-4fcd-9a04-5b41d8646e2a.png)

<h3>Final Variables</h3>

If you don't want others (or yourself) to overwrite existing values, use the final keyword (this will declare the variable as "final" or "constant", which means unchangeable and read-only):

![Screenshot 2022-04-21 at 9 29 57 PM](https://user-images.githubusercontent.com/100328396/164502333-4a351be6-d76d-49fb-ae54-8e48657c8ed3.png)

Output:

![Screenshot 2022-04-21 at 9 30 42 PM](https://user-images.githubusercontent.com/100328396/164502480-b2769e43-a9c5-4dfc-99a2-0e27766e6206.png)

 
A demonstration of how to declare variables of other types:

![Screenshot 2022-04-21 at 9 31 22 PM](https://user-images.githubusercontent.com/100328396/164502612-73313328-bf0f-40f5-b30f-69716a99e489.png)

You can also use the + character to add a variable to another variable:

![Screenshot 2022-04-21 at 9 32 03 PM](https://user-images.githubusercontent.com/100328396/164502755-687b9c85-2a5e-4fe4-bac2-de285f6ca529.png)

Output:

![Screenshot 2022-04-21 at 9 32 47 PM](https://user-images.githubusercontent.com/100328396/164502898-8f491c3f-31ff-449c-9fe1-86b962afffc4.png)

Declare Many Variables

To declare more than one variable of the same type, you can use a comma-separated list:

Instead of writing:

![Screenshot 2022-04-21 at 9 33 35 PM](https://user-images.githubusercontent.com/100328396/164503072-19d3670a-4d72-44a4-8885-677e7d62cc05.png)

We could write:

![Screenshot 2022-04-21 at 9 34 17 PM](https://user-images.githubusercontent.com/100328396/164503206-0088861e-fb49-4fcd-9d95-59593afa434b.png)

We can also assign the same value to multiple variables in one line:

![Screenshot 2022-04-21 at 9 35 15 PM](https://user-images.githubusercontent.com/100328396/164503367-f658b0a7-978d-413a-9bfc-1c7039eebf82.png)

<h3>Java Data Types</h3>


Data types are divided into two groups:
* Primitive data types - includes byte, short, int, long, float, double, boolean and char
* Non-primitive data types - such as String, Arrays and Classes (you will learn more about these in a later chapter)

<h4>Primitive Data Types</h4>

A primitive data type specifies the size and type of variable values, and it has no additional methods.

There are eight primitive data types in Java:

![Screenshot 2022-04-21 at 9 36 55 PM](https://user-images.githubusercontent.com/100328396/164503679-693f9a53-39a2-4cf8-bc6e-dcf25f8a92aa.png)


Even though there are many numeric types in Java, the most used for numbers are int (for whole numbers) and double (for floating point numbers).

<h4>Integer Types</h4>

<h5>Byte</h5>

The byte data type can store whole numbers from -128 to 127. This can be used instead of int or other integer types to save memory when you are certain that the value will be within -128 and 127:

![Screenshot 2022-04-21 at 9 39 57 PM](https://user-images.githubusercontent.com/100328396/164504212-772fba75-e63f-40c7-a11b-fcab0a7c176f.png)

<h5>Short</h5>

The short data type can store whole numbers from -32768 to 32767:

![Screenshot 2022-04-21 at 9 43 23 PM](https://user-images.githubusercontent.com/100328396/164504825-56a3eb03-407f-4c38-a605-4237434019f9.png)

<h5>Int</h5>

The int data type can store whole numbers from -2147483648 to 2147483647. In general, and in our tutorial, the int data type is the preferred data type when we create variables with a numeric value.

![Screenshot 2022-04-21 at 9 44 11 PM](https://user-images.githubusercontent.com/100328396/164504965-42cd7d41-4777-4027-b347-c784270e14e2.png)


<h5>Long</h5>

The long data type can store whole numbers from -9223372036854775808 to 9223372036854775807. This is used when int is not large enough to store the value. Note that you should end the value with an "L":

![Screenshot 2022-04-21 at 9 44 59 PM](https://user-images.githubusercontent.com/100328396/164505112-849c34d4-ffe7-4287-a77e-6b8f20cd839b.png)

<h4>Floating Point Types</h4>

You should use a floating point type whenever you need a number with a decimal, such as 9.99 or 3.14515.

<h5>Float</h5>

The float data type can store fractional numbers from 3.4e−038 to 3.4e+038. <p>Note that you should end the value with an "f":</p>





