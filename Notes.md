# Processing Notes 

Processing is a fun language that lets you create all sorts of cool things, like art, animations, and games. I hope this can help you understand it better!

Here are some basic concepts:
&nbsp;

## Variables

Variables are like **containers that hold information**. Imagine you have a **box** labelled "toys" and you put all your toys inside. The box is the variable, and the toys are the information it holds.

Here's an example of how to create a variable in Processing:
```processing
int coins;
```

This line of code creates a variable called "coins". The **"int"** part tells Processing that the variable is an **integer**, which means it can only hold whole numbers (numbers with no decimals).

Now let's say you want the coins to start at 10. You can use the variable like this:
```processing
int coins;
coins = 10;
```
> After the first line we don't have to write the "int" anymore, because the code already knows that variable is an integer.

That line of code **initializes** an variable of type "int" (integer number), named "coins", and set the value to 10.

We can also give the variable an initial value on the first line, and then change it later:
```processing
int coins = 0;
coins = 10;
```
&nbsp;

## Functions

There are some lines of code that do **"actions" or "functions"**, they usually look like this:
```processing
functionName(parameter);
```
The name of the function followed by **parenthesis** "()".


Most of the functions have **parameters** or variables inside the parenthesis, that tells the function what values to use, for example:

One of the most useful functions in *Processing* is the **"print" function**, we can use it to see the value of what we type inside it.

Let's use it to check the coins variable we used before:

![](https://gyazo.com/ad1698926fec3defc6066c757c9cdd28.png)  

When we run the code, the **print function**, **tells the value of the variable** we put inside in the black box under the text editor, **on the console**.

The problem with "print" function is that it doesn't add breaks after printing something, for example if we code:
```processing
print(1);
print(2);
print(3);
```
This will say on the console:
>123

If you want **line breaks** after printing you should use a similar function called **"println"**:
```processing
println(1);
println(2);
println(3);
```
This will say on the console:
>1
>2
>3

We can also **print text** using this function, text in *Processing* is written using the **quotation marks** → " "
```processing
println("Hello");
```
&nbsp;

These are the functions we have seen so far:

| Function in Processing | Parameters | Definition |
|------|---------------|----------------------------|
|```print(variable)```| ```variable```: Can be any variable or text|Writes in the console the value or text of the variable      |
|float |Decimal Numbers|```int weight = 72.5;```    |
|String|Text           |```String name = "Seiyu";```|
|color |Color          |```color bgColor = color(50, 50, 0);```|
&nbsp;


## Variable Types

There are other types of variables besides "int": 

### Float

We have **"float"** for **decimal numbers** (also called **"floating point" numbers**):
```processing
float weight = 72.5;
print("My weight is ");
print(weight);
print(" kg.");
```
> My weight is 72.5 kg.

This code uses the float type for things that need decimal numbers, like the weight or height of a person.

### String

This is a secret the teacher didn't explain yet but it's good to know because it's really useful. We can also have **text** inside a variable, typing **"String"** like this (it's important to type it with an uppercase S and not s):
```processing
String name = "Mark";
print("I am ");
print(name);
```
> I am Seiyu

Remember that **text** in *Processing* needs to go **between " "**, if it's not inside a variable. In the example, we can see that we **use the *'name'* variable** inside the second **print function** with no problem, and without " " because it's already a variable.
> **Note**: Text It's called "*String*" in programming because they are made up of a sequence (or string) of characters.


### Color

Finally we also have **color** as a type of variable, the only difference with color is that you need to use a special function to create it:
```processing
color backgroundColor = color(0, 0, 100);
color squareColor = color(255, 0, 0);

size(400, 400);
background(backgroundColor);
fill(squareColor);
rect(200, 200, 100, 100);
```
![](https://gyazo.com/c7058485bb599661457acfebe0661d73.png)  

>If you don't remember what the ```fill()``` and ```rect()``` functions do, you can always search on the processing website because they have a lot of examples, for example you can search about rect there: https://processing.org/reference/rect_.html
Or if you want to know about the "fill" function just search: ```fill processing``` on google 😉

To create the color we use ```color(red, green, blue)``` a function that needs 3 number values, one for each primary color.
Each's colors parameter goes from **0 to 255 (dark to bright)**
As you can see when we used ```color(255, 0, 0)```, we created a really bright red, because we put the max value at the red parameter.

We can also combine the parameters to get other colors but if you want a fast way to get the color you want I would recommend to use this tool for picking the colors: https://g.co/kgs/wjm66v
![](https://gyazo.com/f085ddd1e8def8cd9b74a254bef8621c.png)  
You just have to copy the numbers on the left and paste it inside the processing's color function, like this:
![](https://gyazo.com/d38f76199dc73299d0cd2ff0547cb685.png)  
See how we get the same color we picked?
&nbsp;

Here is the list of the variable types that we have seen:

| Name in Processing | Definitions | Example |
|------|---------------|----------------------------|
|int   |Normal Numbers |```int coins = 10;```       |
|float |Decimal Numbers|```int weight = 72.5;```    |
|String|Text           |```String name = "Seiyu";```|
|color |Color          |```color bgColor = color(50, 50, 0);```|

&nbsp;

## Operations











I hope this helps you get started with Processing! Have fun coding!






