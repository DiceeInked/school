# Lesson 1 Cheat Sheet: JavaScript foundations

## Variable declaration

    let ink = 100;

Creates a variable named ink with the value 100.

## Common value types

| Type | Example | Meaning |
|---|---|---|
| Number | 100 | A numeric value |
| String | "Explorer" | Text |
| Boolean | true or false | Yes/no state |

## Reassigning values

    ink = 50;       // Set ink to 50
    ink = ink + 10; // Add 10
    ink += 10;      // Same as above
    ink -= 5;       // Subtract 5

## Printing a value

    console.log(ink);

Displays the value in the console.

## Remember

- let declares a variable that can change.
- Text in quotation marks is a string.
- true and false without quotation marks are booleans.
- += adds to the current value.
- -= subtracts from the current value.
- JavaScript runs statements in order.

## DAG example

    let ink = 60;
    let hasWeapon = false;
    ink += 25;
    hasWeapon = true;
    console.log(ink); // 85
    console.log(hasWeapon); // true
