# .PHP topics; terms; tips
stack xampp/ mamp (port 8080)
htdocs folder
local host, 
vscode, emmits, 

 
web base scripting language- clint side script, server side script
websites - ststic(local html full) and dynamic(admin panel) website
wordpress cont management system
(easy, openSource, oop, cressplatform,30%Hcommunity, workAllservers) php--> create dynamic website with db----> web based software application
CMS, E-commercewebsite, mailServer, chattingSystem, fileStorageSystem, ERP, CRM

<?php
    $name = "Alice"; // String variable
    $age = 30; // Integer variable
    $price = 19.99; // Float/Double variable
    $is_active = true; // Boolean variable (true or false)
    $null_value = null; // Null variable

    echo "Null Value: " . var_dump($null_value) . "<br>"; // var_dump shows type and value

    // Variable reassignment
    $age = 31;
    echo "New Age: " . $age . "<br>";
?>
String: Sequence of characters (e.g., "Hello").
Integer: Whole numbers (e.g., 10, -5).
Float (or Double): Numbers with a decimal point (e.g., 3.14, 0.5).
Boolean: true or false.
Array: Stores multiple values in a single variable (covered later).
Object: Instances of classes (covered later).
NULL: A variable with no value assigned.
Resource: Special variables holding references to external resources (e.g., database connections).
Concatenation: The dot operator (.) is used to join strings together.
var_dump(): A useful function for debugging, displaying structured information (type and value) about an expression or variable.

gettype(): This function returns the type of a variable.

Arithmetic Operators:+-*/
Assignment Operators:=
Comparison Operators (return boolean) <=> (Spaceship operator): Returns -1, 0, or 1 if the first operand is less than, equal to, or greater than the second. 
Logical Operators: and, or, not, xor

foreach: Specifically designed for iterating over arrays and objects, making it very convenient.

Scope:
Local Variables: Declared inside a function, accessible only within that function.
Global Variables: Declared outside any function. To access them inside a function, use the global keyword or the $GLOBALS superglobal array.

Anonymous Functions (Closures): Functions without a defined name, often used as callbacks.
Arrow Functions: A more concise syntax for anonymous functions with a single expression












# Laravel 
framework
mvc(model view controller) architecture
