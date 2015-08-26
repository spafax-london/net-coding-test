## General Information

- Please take as much time as you need.
- Feel free to use any internet sources, however please complete this exercise on your own.
- All code must be supported by tests.
- No actual database implementations are required, feel free to mock any data access you need.
- Please make sure your code follows SOLID principles.
- Please **do not** email us your solution. Return your code in a public github repo or file sharing website.
- Task 3 D) is a BONUS question.

---

### Task 1

Create a function which counts the number of occurrences of a given letter in a string.

Example:

Input: <pre>'e' and "I have some cheese"</pre>
Output: <pre>**5**</pre>

---

### Task 2

Create a function which decides if a string is a palindrome.

Examples:

Input: <pre>I have some cheese</pre>
Output: <pre>**False**</pre>

Input: <pre>God saved Eva’s dog</pre>
Output: <pre>**True**</pre>

---

### Task 3

#### Part A)

Create a function which counts the number of occurrences of words from a "censored words list" in a text.

Example:

Input: <pre>{"dog", "cat", "large"} and "I have a cat named Meow and a dog name Woof. I love the dog a lot. He is larger than a small horse."</pre>
Output: <pre>**cat: 1, dog: 2, large: 1, total: 4**</pre>

#### Part B)

Create a way to censor words featured in the "censored words list" that appear in the text.

Example:

Input: <pre>{"moew", "woof"} and "I have a cat named Meow and a dog name Woof. I love the dog a lot. He is larger than a small horse."</pre>
Output: <pre>**"I have a cat named M$$w and a dog name W$$f. I love the dog a lot. He is larger than a small horse."**</pre>

#### Part C)

Create a way to censor a single word palindrome in a text.

Example:

Input: <pre>"Anna went to vote in the election to fulfil her civic duty"</pre>
Output: <pre>**"A$$a went to vote in the election to fulfil her c$$$c duty"**</pre>

#### Part D - BONUS)

Come up with at least 3 different ways to provide the "censored words list" to the application. This task does not require coding, please send us  3 bullet points on how you would do this. 

---

Thanks for your time.
