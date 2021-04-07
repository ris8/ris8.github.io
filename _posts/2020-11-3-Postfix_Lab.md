---
layout: post
title: Postfix Lab
subtitle: 
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [test]
comments: true
---

The average result of calculate_me.csv was -37. To get this number, I first passed an individual row to calcPostfix(), which evaluated each expression. It did this by pushing each character in the expression to a stack, left to right. If it encountered an operand, it popped the previous two numbers pushed, and combined them using the operand. This result was then pushed back onto the stack. This was continued until there were no characters left in the equation. Then, each of these results were combined and averaged, resulting in -37.  

My process consisted of first looking up how the notation actually worked, then coming up with a game plan. Once I had the game plan, I first coded calcPostfix(), then worked on feeding the CSV file to it. I've learned about Postfix notation, which is pretty neat.