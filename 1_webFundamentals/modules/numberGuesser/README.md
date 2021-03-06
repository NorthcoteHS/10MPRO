# numberGuesser

I'm thinking of a number between 1 and 100. Can you guess it?

Your job is to create a program that "thinks" of a number and lets the user guess!
With each guess, you should tell the user whether they're too high, too low, or correct.

## Steps

1. Always start by opening Brackets, creating a new file, and saving it.

    - Save the new file as `numberGuesser.html`.
    - Fill out the basic structure of the HTML from memory, or use a template or past project.

2. In JavaScript, create a variable with a random number - this is what the user will be trying to guess.

3. Tell the user what the game is and the rules (e.g. number range), either in HTML or an alert.

4. Get the user's guess, either using `prompt()` or an `<input>` and `<button>`.

5. Check if the guess is higher, lower or equal to the computer's number and respond accordingly.

6. Allow the user to continue guessing - either by allowing multiple clicks of the `<button>` (HTML) or using a loop (JS and `prompt()`).

7. Use the resources below to guide you through the process.

## Resources

| Concept              | Resource |
|----------------------|----------|
| Random values        | <ul><li>[JavaScript random](https://www.w3schools.com/js/js_random.asp) (in particular, "random integers")</li><li>getting a random array value - try [Google](https://www.google.com.au/)!</li></ul> |
| If statements        | <ul><li>[If statements](https://www.w3schools.com/js/js_if_else.asp)</li></ul> |
| Displaying results   | <ul><li>[JavaScript output summary (W3Schools)](https://www.w3schools.com/js/js_output.asp)</li><li>Option 1: [JS alert box](https://www.w3schools.com/js/js_popup.asp)</li><li>Option 2: [Changing HTML content](https://www.w3schools.com/js/js_htmldom_html.asp)</li><li>Option 3: [console.log](https://www.w3schools.com/jsref/met_console_log.asp)</li></ul> |
| Loops                | <ul><li>[JS while loop](https://www.w3schools.com/js/js_loop_while.asp)</li><li>[JS for loop](https://www.w3schools.com/js/js_loop_for.asp)</li></ul> |
| General     | <ul><li>[StackOverflow](https://stackoverflow.com/)</li><li>[W3Schools](https://www.w3schools.com/)</li><li>[CSS-Tricks](https://css-tricks.com/)</li><li>[Course Resources](/resources/)</li></ul> |

For HTML versions (using `<input>`, buttons, and `.innerHTML`):

| Concept              | Resource |
|----------------------|----------|
| Input elements | <ul><li>[Different input types (W3Schools)](https://www.w3schools.com/tags/att_input_type.asp)</li></ul> |
| Buttons     | <ul><li>[HTML button element](https://www.w3schools.com/tags/tag_button.asp)</li><li>[Button onclick event (linking to functions)](https://www.w3schools.com/jsref/event_onclick.asp)</li></ul> |
| Getting HTML content | <ul><li>[getElementById() (W3Schools)](https://www.w3schools.com/jsref/met_document_getelementbyid.asp)</li><li>[Input text value property (W3Schools)](https://www.w3schools.com/jsref/prop_text_value.asp)</li><li>[Getting dropdown selection value (W3Schools)](https://www.w3schools.com/jsref/prop_select_value.asp)</li></ul> |

## Extensions

- Create a give up/reset button to give the user an option to start again
- Give the user only a limited amount of guesses
- Create more advanced clues

## Assessment

| Level  | Expectations |
|--------|--------------|
| Bronze | Hard-coded number, lets the user guess once |
| Silver | Random number and lets the user guess repeatedly |
| Gold   | Has a score (based on # of guesses) |
| Diamond | Lets the user reset with a new number, choose different difficulties, or any other creative ideas! |

- **Note:** all code should be commented and you should have no redundant code.

Remember to commit each time you've made a major change to your code, and to push to GitHub frequently.
