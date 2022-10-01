# A quick guide to understanding regex

## Summary

### Purpose
For this week's challenge of the ESMT Coding Boot Camp, I explain regular expressions, commonly known as regex. I will draw from diverse online resources, which I will link to for your further research, and I will detail the parts of a regex using a specific example.

### History
According to [Wikipedia](https://en.wikipedia.org/wiki/Regular_expression), the American mathematician Stephen Cole Kleen formalized the concept of a regular expression in 1951 with his definition of mathematical notation called "regular events." In the late 1960s, the use of regex in computer science and programming grew. Today, among its many uses, regex is widely supported in programming languages and libraries, including Javascript. Read more about [the history of regex on Wikipedia](https://en.wikipedia.org/wiki/Regular_expression#History).  

In this tutorial, I will focus on regex usage in Javascript.

### Definitions

A regular expression, or regex, is a pattern comprised of a sequence of characters and used for searching text. The aforementioned characters are either **literal characters** or **metacharacters**. 

Let's use the word "apple" as an example. 

A search for a literal character `a` would show one match with the "a" in **a**pple. A search for a `p` would show two matches in a**pp**le.  

Metacharacters, on the other hand, have special meanings. For example, in the sentence 

`I like to eat Gala apples.`

the word **apples** could be described and found with `\w\w\w\w\w\w`. The metacharacter `\w` stands for an alphanumeric character, that is, letters A to Z (whether lowercase or uppercase) and digits 0 to 9. The word **apples** is six characters long.  

There are many metacharacters (see the [JavaScript RegExp Reference](https://www.w3schools.com/jsref/jsref_obj_regexp.asp) on W3Schools). We will examine them in additional detail in the exercise below.

### Example code

For this tutorial, we will search for a URL in a body of text on a page written with Markdown, a markup language for plain-text editors. (This tutorial was written using Markdown.) The text has letters, numbers, and special characters and, of course, so does the URL. We thus want to find the unique combination of characters written as a regex to describe a URL.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors

### Quantifiers

### OR Operator

### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)