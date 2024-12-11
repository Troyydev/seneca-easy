# seneca-easy

[senecalearning.com](https://senecalearning.com)

Use the following script to display your math-field element, listen for input changes, and log the current answer to the console:

```javascript
// Select the math-field element by its ID. Adjust if your ID is different.
const mathField = document.querySelector('#hidden-mfe');

if (mathField) {
    // Ensure the math-field is displayed
    mathField.style.display = 'block';

    // Listen for input events
    mathField.addEventListener('input', () => {
        // Retrieve the current value from the math-field
        const answer = mathField.getValue();
        console.log("Answer:", answer);
    });

    console.log("Math field found and is now being monitored for input.");
} else {
    console.log("No math-field with the specified selector was found.");
}

Short term the Calcuator Questions answer grabber thingy 
