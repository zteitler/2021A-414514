---
layout: assignment
title: Homework 0
duedate: 2021-01-18
---



This homework will be about using LaTeX to create a PDF,
and uploading that PDF to [Gradescope](https://gradescope.com).
The goals of this homework are

+ For you to practice using LaTeX
+ For you to practice uploading an assignment to Gradescope
+ For me to practice grading an assignment in Gradescope

## Instructions

If you don't have LaTeX on your computer, you can use [Overleaf](https://overleaf.com).
Don't submit the LaTeX source, just the PDF.
Email your instructor (that's me) if you have questions or need help.

Please include your name and the homework number
(this is Homework 0) within the document.
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


## Problems

1.  (LaTeX: basics) Answer this question.
    Enter this LaTeX code into your tex file, and answer it:
    
    ```
    \begin{exer}
    What are the intersection $\{1,2,3,4,5\} \cap \{3,4,5,6,7\}$
    and the union $\{1,2,3,4,5\} \cup \{3,4,5,6,7\}$?
    \end{exer}
    \begin{answer}
    -enter your answer here-
    \end{answer}
    ```

2.  (LaTeX: basics) Answer this question.
    Enter this LaTeX code into your tex file, and answer it:
    
    ```
    \newpage
    \begin{exer}
    Suppose $S \subset \mathbb{R}$, $f : S \to \mathbb{R}$ is a function,
    $c$ is a cluster point of $S$, and $L \in \mathbb{R}$.
    What is the definition of $\lim_{x \to c} f(x) = L$,
    using $\epsilon$ and $\delta$?
    (Hint: See Definition 3.1.3 of the Lebl book.)
    \end{exer}
    \begin{answer}
    -enter your answer here-
    \end{answer}
    ```

3.  (LaTeX: Using "split" to align equations)
    Complete this simplification.
    Enter this LaTeX code into your tex file, and answer it.
    (Fill in the ?'s. You might not need all of them, so delete the extras.)
    
    ```
    \newpage
    \begin{exer}
    The derivative of $x^2$ is $2x$.
    \end{exer}
    \begin{proof}
    Using the limit definition of derivative, we have
    \begin{equation}
    \begin{split}
      \lim_{h \to 0} \frac{(x+h)^2 - x^2}{h} &= ? \\
        &= ? \\
        &= ? \\
        &= ? \\
        &= ? \\
        &= ? \\
        &= ? \\
        &= ? \\
        &= ? \\
        &= ?
    \end{split}
    \end{equation}
    \end{proof}
    ```

4.  Read [Self-Explanation Training for Mathematics Students](
    https://www.lboro.ac.uk/media/media/schoolanddepartments/mathematics-education-centre/downloads/research/SE-booklet.pdf).
    Write a self-explanation of Practice Proof 1.


5.  (About yourself) Answer the questions. This will not be graded for correctness.
    The goal is just to tell me a little bit about yourself
    (and also to practice using LaTeX's enumerate lists).
    
    ```
    \newpage
    \begin{exer}
    \begin{enumerate}
    \item What is your ``official'' name as on the class roster?
    \item What name do you like to go by in class?
    \item How is your name pronounced?
    \item What pronouns do you prefer (this could be she/her/hers, he/him/his,
      they/them/theirs, or other)?
    \item What is something that you are excited to learn in this class?
    \item What is something that you are concerned about in this class?
    \item Is there anything else you would like me to know?
    \end{enumerate}
    \end{exer}
    ```


## Special Grading

For this assignment, Homework 0, there will be special grading.
I will mark each problem out of 5 points, as if it were regular homework.
But the actual homework score will just be 10 points if you complete it.
