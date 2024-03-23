**LET**
The `let` keyword was introduced in [ES6 (2015)](https://www.w3schools.com/js/js_es6.asp)

Variables declared with `let` have **Block Scope**

Variables declared with `let` must be **Declared** before use

Variables declared with `let` cannot be **Redeclared** in the same scope

**Constants**
To declare a constant (unchanging) variable, use `const` instead of `let`

- **Uppercase constants**
There is a widespread practice to use constants as aliases for difficult-to-remember values that are known before execution.

Such constants are named using capital letters and underscores.

For instance, let’s make constants for colors in so-called “web” (hexadecimal) format:

const COLOR_RED = "#F00";
const COLOR_GREEN = "#0F0";
const COLOR_BLUE = "#00F";
const COLOR_ORANGE = "#FF7F00";

// ...when we need to pick a color
let color = COLOR_ORANGE;
alert(color); // #FF7F00