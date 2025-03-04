# Glossary

(inner-product)=
## Inner Product
An inner product is a binary operation $\braket{\cdot, \cdot}: V \times V \rightarrow F$ satisfying
1. Conjugate Symmetry: $\braket{v,w}=\overline{\braket{w,v}}$
2. Positive Definiteveness: $\braket{v,v} \geq 0 \forall v \in \mathbb{V}$, with $\braket{v,v}=0 \Leftrightarrow v=0$
3. Linearity: $\braket{v,aw+bz}=a\braket{v,w} + b\braket{v,z}$


(reinforcement-learning)=
## Reinforcement Learning

Machine Learning technique where we built our input / output rows by choosing our inputs, letting a system evolved with the chosen input, either by a numerical simulation or experimentally, and feeding back the resulting output into our training loop.

## Supervised Learning
Nope

(orthogonal)=
## Orthogonal
A set of elements in a @hilbert-space where their @inner-product is $0$. 