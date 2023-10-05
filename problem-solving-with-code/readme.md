# Problem Solving Methodologies

Learning to code is only one part of being a software developer. The most important skill to develop is your ability to identify and solve problems.

In this lesson, you'll learn about some common ways to solve problems with code. You'll also deep dive into one particular problem solving technique and see how it can be applied to solving code challenges.

## Learning Objectives

By the end of this lesson you should be able to:

- Analyze a coding problem by asking clarifying questions.
- Devise multiple ways to solve a single problem before intentionally choosing one.
- Evaluate a code solution with sample inputs and outputs.
- Reflect back on a solution, identifying areas for improvement.

---

## How do we solve problems?

When you first encountered the lesson on problem solving, you had some examples that you did not need to write any code for. Now, you'll see some examples of how to use your problem solving skills to solve coding challenges.

Let's review Poly'as problem solving technique

## Polya's problem solving technique

[Polya's Problem Solving Technique](https://math.berkeley.edu/~gmelvin/polya.pdf) can be applied to solving code challenges.

### Understand the problem

The first step is to understand the question. This means making sure you understand what the question is asking as well as asking clarifying questions.

#### Key terms

For example, take a look at the following coding prompt:

```
Write a recursive function that takes an integer and returns its associated
Fibonacci number as defined by the Fibonacci sequence.
```

This question is dense with technical and mathematic terms. In order to understand what is being asked, you'll need to be able to understand a number of key terms including:

- recursive function
- integer
- Fibonacci number and sequence

Without understanding the terms above, you'll certainly find it difficult to develop a solution for this problem. This is why your first step in approaching a problem should be to make sure you understand all of the key terms present in the problem prompt.

#### Inputs and output

Although applicable to all kinds of problems, it's particularly important with coding problems to understand the inputs and the output. Inputs refers to what information you will have in order to solve the problem. Output refers to what kind of result is needed.

For example, take a look at the following problem:

```
How many cupcakes can be made with 2lbs of flour?
```

In the question above, the input you have is the amount of flour: 2lbs The output is the number of cupcakes that can be baked.

#### Clarifying questions

Additionally, it's normal to question the boundaries of the problem, so you can better find a solution. These kind of clarifying questions are useful for understand what you should and should not focus on.

For example, consider the following question:

```
On average, how many children rode a New York City Bus each day in the
winter months of 2015?
```

The question above is pretty specific, but when you dig into the problem, you may come up with a number of questions:

- What age range counts as being an child
- What date range is considered for winter months?
- If an child rode the bus multiple times in a day, how often should they be counted?

These kind of questions allow you to figure out both base requirements and edge cases.

### Devise a plan

Once you accurately understand the problem to the best of your ability, it's time to figure out how you are going to solve it. While a few problems have a single way of completing them, many complex problems allow for multiple approaches.

#### Seek multiple paths

Consider the following problem:

```
Apply a 20% discount on all purchases over $100.
```

After spending time understanding the problem, including inputs and outputs, it's time to think about how you would solve this problem. While this is a relatively straightforward problem, you could solve it in a couple different ways:

1. Get the discount by multiplying the total by `0.2`. Then, subtract the discount from the total.
2. Multiply the total by `0.8`.

Is there a "right" answer here? Not necessarily. If each one achieves the same goal, then in many ways it's up to you which path to choose. However, the second option above is a bit simpler. Coming up with multiple options can sometimes lead to you finding a more elegant solution.

#### Coding paths

Particularly when it comes to coding, there are a lot of ways to attain the same result. For example, `if/else` statements are sometimes interchangeable with `switch` statements. Whenever you use a method like `.push()` you could be using array indexing. Arrays and objects can often be used similarly, depending on the type of problem.

With code, it's important to consider qualities like efficiency, readability, and flexibility. It's also important to consider which path seems most possible for you to do.

### Solve it

Once you understand the problem and have a path to take in mind, it's time to actually solve the problem. At this point, coming up with a solution will still be difficult. However, with all the work you've done up to this point, it should be significantly easier than attempting do all of the previous steps at once.

As an example, consider the following problem.

```
Write a function that takes an array of objects, where each object has two keys:
`firstName` and `lastName`. Then, sort the array in ascending alphabetical
order by last name.
```

For the problem above, after considering a few different options, you may come up with the following plan:

> To solve this problem I will use the `.sort()` method, to sort the array by last name. Then, I'll return the array.

The above plan essentially describes your implementation. To get started, you'll start by picking inputs and what output you would expect. Then, you'll just need to write the code to do it.

That's not to say it won't be tricky. You would need to remember how to write a function, return a value, and how to use the `.sort()` method. However, these are all concepts that can be looked up quickly. If you have a plan in place, writing the solution will be much easier.

### Reflect back

Once you've written your solution, it's important to reflect back on what you've just done. While there are many important reasons to look back, two of the most important are to check your solution for correctness and then check for potential improvements.

#### Check for correctness

Depending on how you're solving your problem, checking for correctness may be very easy. If you're writing code, you could run your code to see if you get the desired result. You might also run tests against your code, to verify it works in a number of ways.

If you're working on a problem where it's more difficult to check for correctness, you may instead just be checking your work. For example, consider the following problem:

```
Write an application for a job that will be accepted.
```

If you are tackling the above problem, you can't really know if your application will be accepted until it is or is not. However, you can certainly do your best to check your work, make sure you've completed the application in full, and check for any mistakes you may have made.

#### Making improvements

There are almost always ways to improve your solution. Whether by making it more efficient or elegant, it's important to look back at difficult problems you face and consider how you could make it better next time.

When it comes to code, there are a number of common improvements that can often be made, even if the code you've written works for your situation.

- Can you make the code easier to read? Perhaps you need to add comments, or update some variable names to be more clear.
- Can you make the code more efficient? Perhaps you can rethink how you loop through data, or how much memory a solution uses.
- Can you remove any duplicate code blocks? Perhaps you can make helper functions or leverage scope in a different way.
- Can you refactor the code to be more reusable for the future? Perhaps you can change hardcoded values to variables that may be changed in the future.

Even spending just a few moments looking back at the code you've written to improve it can make a huge difference for the quality of your solution.
