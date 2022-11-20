## JavaScript Where To

### The <script> Tag

In HTML, JavaScript code is inserted between `<script>` and `</script>` tags.

```javascript
<script>
document.getElementById("demo").innerHTML = "My First JavaScript";
</script>
```



### JavaScript in <head> or <body>

Scripts can be placed in the `<body>`, or in the `<head>` section of an HTML page, or in both.



### External JavaScript

```html
<script src="myScript.js"></script>
```

To add several script files to one page - use several script tags:

```html
<script src="myScript1.js"></script>
<script src="myScript2.js"></script>
```



## JavaScript Output

* Writing into an HTML element, using `innerHTML`.
* Writing into the HTML output using `document.write()`.
* Writing into an alert box, using `window.alert()`.
* Writing into the browser console, using `console.log()`.

### Using document.write( )

Using document.write() after an HTML document is loaded, will **delete all existing HTML**:

### Example

```html
<!DOCTYPE html>
<html>
<body>

<h1>My First Web Page</h1>
<p>My first paragraph.</p>

<button type="button" onclick="document.write(5 + 6)">Try it</button>

</body>
</html>
```

### Using window.alert()

You can skip the `window` keyword.

In JavaScript, the window object is the global scope object. This means that variables, properties, and methods by default belong to the window object. This also means that specifying the `window` keyword is optional.

## JavaScript Statements

## Semicolons ;

Semicolons separate JavaScript statements.

Add a semicolon at the end of each executable statement



## JavaScript White Space

JavaScript ignores multiple spaces. You can add white space to your script to make it more readable.

The following lines are equivalent:

```javascript
let person = "Hege";
let person="Hege";
```



### JavaScript Line Length and Line Breaks

For best readability, programmers often like to avoid code lines longer than 80 characters.

If a JavaScript statement does not fit on one line, the best place to break it is after an operator:

```javascript
document.getElementById("demo").innerHTML =
"Hello Dolly!";
```



### JavaScript Keywords

JavaScript statements often start with a **keyword** to identify the JavaScript action to be performed.

https://www.w3schools.com/js/js_statements.asp



## JavaScript Syntax

### JavaScript Values

The JavaScript syntax defines two types of values:

* fixed values
* Variable values

Fixed values are called **Literals**. Variable values are called **Variables**.

### JavaScript Literals

**Numbers** are written with or without decimals: 

```javascript
10.50
1001
```

 **Strings** are text, written within double or single quotes: 

```javascript
"John Doe"
'John Doe'
```



### JavaScript Variables

In a programming language, **variables** are used to **store** data values.

JavaScript uses the keywords `var`, `let` and `const` to **declare** variables.

An **equal sign** is used to **assign values** to variables.



### JavaScript Expressions

An expression is a combination of values, variables, and operators, which computes to a value.

The computation is called an evaluation.

For example, 5 * 10 evaluates to 50:

```javascript
5 * 10
```

Expressions can also contain variable values:

```javascript
x * 10
```



### JavaScript Keywords

JavaScript **keywords** are used to identify actions to be performed.

The `let` keyword tells the browser to create variables:

```javascript
let x, y;
x = 5 + 6;
y = x * 10;
```













