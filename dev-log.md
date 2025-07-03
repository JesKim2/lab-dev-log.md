## What I Learned Today
1. Words are broken into bytes, and then byte pair encoding to save symbols and feed to the LLMs for training
2. Inference is like unfair probability, and you need to change the weights to get the term you desire using trial and error
3. The eval() function in python evaluates a string, meaning it tries to run it like a python code
- Project Gutenberg- Labyrinth is something where people are trying to make books whose copyrights have expired publicly accessible
- You use = when you assign something to an operator or variable and use == when it is a comparison
- Tokenization is breaking something into smaller pieces, called tokens (usually words, characters, to even subwords depending on the context) and is used to feed information to the LLMs
## Lab Reflection

> **_One thing I found surprising was that even professionals don't know how AI had a jump in inference capabilities, starting to recognize patterns and such_** I also liked how we could still use inference to guide the answer
## Code Snippet

```python 
name = input("What is your name? ")
print("Hello " + name)
```
### Helpful Links

- [Terminal Walkthrough Video](https://youtu.be/ZkoEHvG3GI8?si=TD-g4ZgpJ0N-9sI3)

- [Tiktokenizer](https://tiktokenizer.vercel.app/?model=cl100k_base)
