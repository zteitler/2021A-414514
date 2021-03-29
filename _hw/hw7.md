---
layout: assignment
title: Homework 7
duedate: 2021-04-04
mathjax: true
---

## Exercises

1.  Lebl 6.3.4

2.  Lebl 6.3.8

3.  Lebl 6.3.9

4.  Consider the initial value problem
    $$ y' = x^2 + y^3 $$, $$ y(1) = 1 $$,
    with the constraints $$0 \leq x \leq 2$$, $$0 \leq y \leq 3$$.
    
    1.  Let $$F(x,y) = x^2 + y^3$$. Find the smallest possible bound for $$F$$
        on the rectangle $$R$$ defined by $$0\leq x \leq 2$$, $$0 \leq y \leq 3$$.
    
    2.  Find the smallest possible Lipschitz constant for $$F$$ in the rectangle $$R$$.
        (Hint: an upper bound for $$\partial F/\partial y$$ is a Lipschitz constant for $$F$$.)
    
    3.  Find the largest possible $$\alpha$$ such that the square
        $$[x_0-\alpha,x_0+\alpha] \times [y_0-\alpha,y_0+\alpha]$$
        is contained in the rectangle $$R$$,
        where $$(x_0,y_0)$$ is the initial point $$(1,1)$$.
    
    4.  Find a value $$h$$ so that the initial value problem is guaranteed to have
        a unique solution on the interval $$[x_0-h,x_0+h]$$.
        Try to find the largest possible such $$h$$.
        You may use Lebl's statements, or statements from class.
    


## Instructions

If you don't have LaTeX on your computer, you can use [Overleaf](https://overleaf.com).
Upload the PDF to Gradescope.
Don't submit the LaTeX source, just the PDF.

+ When you upload to Gradescope,
  please mark which page of the PDF has your answer to each question!

Email your instructor (that's me) if you have questions or need help.

Some additional formatting instructions are in the
[syllabus]({{ "/syllabus" | relative_url }}).
To summarize:

+ Use a new page (`\newpage`) for each problem.
+ State which question you are answering and the actual question.
  Then, start your answer in a new paragraph.
+ Use environments such as `proof` and `theorem`
  (via `\begin{proof}...\end{proof}`).
+ Use 12pt option `\documentclass[12pt]{amsart}` and `\linespread{2.4}`.

Please find and use the LaTeX template linked on the course website.

You are encouraged to work together on the homework!


## Additional reading

+ Visit the Mathematics Colloquium web page: <https://math.boisestate.edu/colloquium/>  
  Visit the Mathematics seminars web page: <https://math.boisestate.edu/seminars/>  
  You are invited to attend colloquium and seminar talks!
