# Lesson 1: JavaScript foundations

**Course:** JavaScript for DAG  
**Status:** Completed

## What is a variable?

A variable is a named place where JavaScript stores information.

    let ink = 100;
    let playerName = "Explorer";
    let hasWeapon = true;

- let creates a variable that can be reassigned.
- A number stores a numeric value, such as 100.
- A string stores text, usually written inside quotation marks.
- A boolean stores either true or false.

## Changing a variable

    let ink = 100;
    ink = ink + 25;
    console.log(ink);

This prints 125.

The shorter version is:

    ink += 25;

The related -= operator subtracts and stores the result:

    ink -= 30;

## Why this matters in DAG

DAG needs to keep track of changing game information. Variables can store the player's ink, name, selected weapon, and whether an action is active.

    let ink = 80;
    let isMining = false;
    ink += 20;
    isMining = true;

## Experiment

Try changing the starting ink amount and the amount collected. Predict the result before running the code.

## Key idea

A variable can hold information, and reassignment lets the game update that information as things happen.
