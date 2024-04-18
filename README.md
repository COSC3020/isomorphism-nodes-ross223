[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/AtNXzL3S)
# Isomorphism

Prove that if two graphs $A$ and $B$ do not have the same number of nodes, they
cannot be isomorphic. I have started with the formal definition of isomorphism
below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Lets assume that if two graphs A and B do not have the same number of nodes then
they can be isomorphic.

This means that there exists some bijection between A and B.

Therefore, for each node in A there must be exactly one node in B that has equivilant
connections and each node in B has to have exactly one node in A with equivilant 
connections by the definition of bijection.

If A has less nodes than B, A can only map n-1 nodes to B as mapping n nodes would 
result in a function that is not one-to-one.

Similarly, if B has less nodes than A, A can still only map n-1 nodes to B as mapping
the final one would result in a function that is not one-to-one.

Therefore, the graphs are not isomorphic which results in a contradiction.

Therefore, if two graphs A and B have different amount of nodes they cannot be isomorphic
by contradiction.
