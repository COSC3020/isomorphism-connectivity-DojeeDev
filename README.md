# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

We can prove that they don't have to be connected by proving the statement they must be completely connected false. Which would lead us to know that they don't have to be completely connected to be isomorphic. We can prove that then a counter example. 

Take graph A where $V_A = [A,B,C]$ and $E_A = [(A,B),(B,C)]$ and graph B where $V_B = [X,Y,Z]$ and $E_B = [(X,Y),(Y,Z)]$ Where both graphs are undirected graphs. Neither are completely connected. And we know they are isomorphic because we have a bijection function $f: V_A \rightarrow V_B$ for all edges in A to all edges in B. Like so, $ f = \{((A,B) \mapsto (X,Y)), ((B,C) \mapsto (Y,Z)) \}$.

Therefore, since we've proven that the statement that if two graphs are isomorphic they *have* to be fully connected, the inverse being, if two graphs are isomorphic they do *not* have to be completely connected must be true.




I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.
