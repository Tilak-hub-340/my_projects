\# Day 7 — Math Refresh



\## Algebra Diagnostic



5/5 correct.



Math gaps: Algebra — none identified from this diagnostic.





\## Probability Diagnostic



7/10 correct after correcting the heart-question answer in the quiz.



Math gaps: Probability — review complements ("at least one"), independence, and the Bernoulli distribution.\\



\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

\## ML Connection



Conditional probability is directly connected to what a language model does when it predicts the next token. When I calculate P(A|B) = P(A and B) / P(B), I am asking how likely A is when I already know that B happened. A language model does something similar, except A is a possible next token and B represents all the tokens that came before it. For example, given the text "The cat sat on the", the model estimates probabilities for possible next tokens such as "mat", "floor", or "chair". It uses the context to change the probability of each possible next token. The scale is much larger than the examples I calculated by hand, but the basic idea is still conditional probability: P(next token | previous tokens). The model learns patterns from data that allow it to estimate these conditional probabilities and choose or sample from the resulting distribution.



