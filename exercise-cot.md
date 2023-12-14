# Exercise: Chain of Thoughts Prompt

Here's an example problem statement:

_"A bookstore sells three types of books: novels, biographies, and science books. The store sold 126 books last week. The number of novels sold was twice the number of biographies, and the number of science books sold was half the number of biographies. How many of each type of book were sold?"_

**Your Goal**: Create a prompt that leads GPT to logically deduce the sales of each type of book, demonstrating clear reasoning steps.

> Some language models will interpret this and even generate code to solve it! However, we want to learn the concepts as CoT is a common prompting approach and it can help you apply similar approaches to your business problems.

To create the prompt, you can use the bakery example below as a one-shot prompt. See the example in the slides of "Standard Prompting vs Chain-of-Thought Prompting".

## Bakery Business Example

"A bakery produces three types of pastries: croissants, muffins, and scones. Last Saturday, they sold a total of 150 pastries. The number of croissants sold was three times the number of muffins, and the number of scones sold was twice the number of muffins. How many of each type of pastry were sold?"

### Reasoning steps

Here are the reasoning steps:

1. **Identify Each Category**:
   - Represent the number of muffins sold as 'M'.
   - Croissants: Sold three times as many as muffins, so '3M'.
   - Scones: Sold twice as many as muffins, so '2M'.
2. **Total Sales Equation**: The total sales were 150 pastries. So, M + 3M + 2M = 150.
3. **Solve for 'M'**: Guide GPT to calculate the value of 'M'.
4. **Determine Each Type's Sales**: Calculate the number of croissants and scones based on 'M'.

### Using the Reasoning Steps

Explain each step in simple steps to the language model. To start you off:

- Let the number of muffins sold be M.
- The number of croissants sold is 3 times the muffins, so 3M.

