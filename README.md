# Human Typing Simulator
## Overview
The <b>humanTypingSimulator()</b> function is a JavaScript function that simulates a human typing in an input form. This can be useful for testing and automation purposes where you want to simulate user interaction with a form.

## Installation

You can install the <b>humanTypingSimulator()</b> function by downloading the humanTypingSimulator.js file and including 

it in your HTML file:


``` <script src="humanTypingSimulator.js"></script> ```

## Usage

To use the <b>humanTypingSimulator()</b> function, you need to pass in two arguments: the input field element and the text you want to simulate typing.


Here's an example:
``` const inputField = document.getElementById('myInput');
const textToType = 'Hello, World!';
humanTypingSimulator(inputField, textToType);
```

This code will simulate a human typing "Hello, World!" in the input field with the ID myInput.

## Options
The <b>humanTypingSimulator()</b> function also takes an optional third argument, an object with options. The available options are:

<b>delay:</b> the delay between each character typed (in milliseconds). Defaults to 50ms.
Here's an example:
``` const inputField = document.getElementById('myInput');
const textToType = 'Hello, World!';
const options = {
  delay: 100,
};
humanTypingSimulator(inputField, textToType, options);
```

This code will simulate a human typing "Hello, World!" in the input field with the ID myInput, with a delay of 100ms between each character typed and deleted.

## License
This project is licensed under the MIT License. See the <b>LICENSE.md</b> file for details.