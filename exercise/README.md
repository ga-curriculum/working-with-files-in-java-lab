<h1>
  <span class="headline">Working with Files in Java Lab</span>
  <span class="subhead">Exercise</span>
</h1>

## Exercise (45 min)

In this lab, you will build a superhero quiz application. The starter code has some parts of this app that are already completed for you.

### Review current code

Start by reviewing the existing code in the <code class="filepath">./src/main/java/org/example/exercise/Main.java</code> and <code class="filepath">./src/main/java/org/example/exercise/Superhero.java</code> files along with the <code class="filepath">./input.txt</code> file. Take a moment and research anything that you're unfamiliar with, such as [BufferedReader](https://www.javatpoint.com/java-bufferedreader-class).

**To quickly summarize**: So far, this app reads the superhero info from the `input.txt` file and stores it in an `ArrayList` named `superheroes`.

Each superhero in the array list has this information: a `superheroName`, a `realName`, and a `placeOfBirth`.

### Build a quiz game!

Use this information to build a quiz game that takes input from the console to collect user answers.

You must ask at least three questions in the quiz. You can create any questions you like, given the data you have. For example:

- What superhero was born in X?
- What is X's real name?

Replacing X with the appropriate values held in the `superheroes` ArrayList.

Keep track of the number of right and wrong answers provided by a user.

It should not matter what casing a user provides their answer in. For example, `Batman`, `batman`, and `BaTmAn` should all be acceptable answers to the question, "What superhero was born in Gotham City?".

> 🧠 Check out this writeup for the [Scanner](https://www.javatpoint.com/Scanner-class) class - it will help you take input from the user in the console.

### Write the results to an <code class="filepath">output.txt</code> file

If the number of right answers is greater than the wrong ones, declare the user a winner and write the result of the quiz in an `output.txt` file.

Include these details for each question:

- The question that was asked.
- The user's answer to the question.
- The correct answer.
- Whether the user was right or wrong.

Also include the total number of right and wrong guesses and a percentage of right/wrong overall.

> 🧠 This [BufferedWriter](https://www.javatpoint.com/java-bufferedwriter-class) article will help you successfully write to a file.
