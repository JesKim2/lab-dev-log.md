# Jessica Kim - July 2, 2025
## What I Learned Today
1. Words are broken into bytes, and then byte pair encoding to save symbols and feed to the LLMs for training
2. Inference is like unfair probability, and you need to change the weights to get the term you desire using trial and error
3. The eval() function in python evaluates a string, meaning it tries to run it like a python code
![AI 101: Training vs. Inference](https://www.backblaze.com/blog/wp-content/uploads/2023/11/AI-101_Training-vs.-Inference_Training-Diagram-1024x495.png)
- Project Gutenberg- Labyrinth is something where people are trying to make books whose copyrights have expired publicly accessible
- You use = when you assign something to an operator or variable and use == when it is a comparison
- Tokenization is breaking something into smaller pieces, called tokens (usually words, characters, to even subwords depending on the context) and is used to feed information to the LLMs

## Lab Reflection

> **_One thing I found surprising was that even professionals don't know how AI had a jump in inference capabilities, starting to recognize patterns and such._** I also liked how we could still use inference to guide the answer

<details>
<summary>Other things I found interesting</summary>

**For Chat bots, the entire conversation is turned into tokens, fed into the computer, and thus it infers the next thing to say**
- Ex: If "Hey chat, how many letters does the color red have? Good question, there is 3 letters. What about blue?" is the conversation, all of this is tokenized and gives "There is 4 letters."
- **If the number of tokens exceed the limit, then only the most recent/likely to be relevant tokens are saved and the rest discarded**

</details>

## Code Snippet

```python 
name = input("What is your name? ")
print("Hello " + name)
```
### Helpful Links

- [Terminal Walkthrough Video](https://youtu.be/ZkoEHvG3GI8?si=TD-g4ZgpJ0N-9sI3)

- [Tiktokenizer](https://tiktokenizer.vercel.app/?model=cl100k_base)

#ai_applications #obsidian #markdown_exercise