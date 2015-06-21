---
date: 2014-09-30
round: Round 11
title: 'Assessment exercise: Finding Things'
author: Kirill Palamartchouk
permalink: /2014/09/assessment-exercise-finding-things/
tags:
  - Assessment
---
**1.**

You are a novice Python programmer, but you already know that functions are defined using a reserved word 'def' in Python. You have written a simple program (its text is in 'my_program.py' file) that contains a number of functions. Can you think of a way of reminding yourself their names?

> (1) find my_program.py -name def  
> (2) grep '^def ' my_program.py  
> (3) grep -v def my_program.py  
> (4) find def my_program.py  
> (5) grep -i def my_program.py

If you are *not* a novice, you can also comment on the limitations of the solution.

**2.**

Now that you understand how to find specific lines in a single file, explain what the following command does and what is the function if each of its elements. Which of the elements you could probably omit without any change in the result?

> grep '^def ' $(find . -type f -name '*.py')
