```markdown
# Sentence Maker

This JavaScript project generates two creative stories using template strings and variable substitution. It is designed to help beginners practice variable declaration, reassignment, and string interpolation in JavaScript.

## 🚀 Features

- Declares variables for sentence components: `adjective`, `noun`, `verb`, `place`, `adjective2`, and `noun2`
- Uses a sentence template to build stories dynamically
- Outputs two different stories using variable reassignment

## 📚 What You Will Learn

- `let` variable declaration and reassignment
- String concatenation and template literals
- Console output using `console.log()`

## 🧩 Story Template

Each story follows this structure:

``

Once upon a time, there was a(n) \[adjective] \[noun] who loved to eat \[noun2].
The \[noun] lived in a \[place] and had \[adjective2] nostrils that blew fire when it was \[verb].

``

## 🛠 How to Run

1. Copy the script into a `.js` file, e.g., `sentenceMaker.js`
2. Run the file using Node.js:

```bash
node sentenceMaker.js
``

3. You should see output like:

``
First story: Once upon a time, there was a(n) fierce dragon who loved to eat marshmallows...
Second story: Once upon a time, there was a(n) tiny kitten who loved to eat tuna...
``

## 🧠 Example Code

```javascript
let adjective = "fierce";
let noun = "dragon";
let verb = "angry";
let place = "cave";
let adjective2 = "fiery";
let noun2 = "marshmallows";

let firstStory = `Once upon a time, there was a(n) ${adjective} ${noun} who loved to eat ${noun2}. The ${noun} lived in a ${place} and had ${adjective2} nostrils that blew fire when it was ${verb}.`;
console.log("First story: " + firstStory);

adjective = "tiny";
noun = "kitten";
verb = "cold";
place = "castle";
adjective2 = "sparkly";
noun2 = "tuna";

let secondStory = `Once upon a time, there was a(n) ${adjective} ${noun} who loved to eat ${noun2}. The ${noun} lived in a ${place} and had ${adjective2} nostrils that blew fire when it was ${verb}.`;
console.log("Second story: " + secondStory);
``

## 📄 License

This project is open-source and free to use for learning and practice.

```
