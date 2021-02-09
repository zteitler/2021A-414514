---
layout: assignment
title: Homework 4
duedate: 2021-02-17
mathjax: true
---

## Exercises

1.  Lebl 5.2.4: Prove the *mean value theorem for integrals*.
    That is, prove that if $$f : [a,b] \to \mathbb{R}$$ is continuous,
    then there exists a $$c \in [a,b]$$ such that $$\int_a^b f = f(c)(b-a)$$.

2.  TBB 6.7.4: Calculate $$\omega_f(0)$$ for each of the following functions.
    1. $$f(x) = \begin{cases} x, \text{if $x \neq 0$} \\ 4, \text{if $x = 0$} \end{cases}$$
    2. $$f(x) = \begin{cases} 0, \text{if $x \in \mathbb{Q}$} \\ 1, \text{if $x \notin \mathbb{Q}$} \end{cases}$$
    3. $$f(x) = \begin{cases} n, \text{if $x = \frac{1}{n}$} \\ 0, \text{otherwise} \end{cases}$$
    4. $$f(x) = \begin{cases} \sin \frac{1}{x}, \text{if $x \neq 0$} \\ 0, \text{if $x = 0$} \end{cases}$$
    5. $$f(x) = \begin{cases} \sin \frac{1}{x}, \text{if $x \neq 0$} \\ 7, \text{if $x = 0$} \end{cases}$$
    6. $$f(x) = \begin{cases} \frac{1}{x} \sin \frac{1}{x}, \text{if $x \neq 0$} \\ 0, \text{if $x = 0$} \end{cases}$$

3.  TBB 8.6.2: Show that the product of two Riemann integrable functions is itself Riemann integrable.

4.  Choose one of the following.
    1.  TBB 6.8.12: Show that the set of real numbers in the interval $$[0,1]$$
        that do not have a $$7$$ in their infinite decimal expansion
        is of measure zero.

    2.  TBB 7.2.10: Let a function $$f : \mathbb{R} \to \mathbb{R}$$ be defined by setting
        $$f(1/n) = c_n$$ for $$n = 1,2,3,\dotsc$$ where $$\{c_n\}$$ is a given sequence
        and elsewhere $$f(x)=0$$.
        Find a condition on that sequence so that $$f'(0)$$ exists.

    3.  TBB 7.6.12: Suppose that $$f$$ is differentiable on $$[0,\infty)$$ and that
        \\[ \lim_{x \to \infty} f'(x) = C . \\]
        Determine \\[ \lim_{x \to \infty} [f(x+a) - f(x)] . \\]

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
