# FI-PIP-formulas
permutational invariant polynomial(PIP) fundamental invariant(FI) formulas.
This is a repository for permutational invariant polynomial(PIP) fundamental invariant(FI) formulas.
Those kind of polynomial are widely adopted in potential energy surface(PES) construction for mulecular dynamics simulation.

There is a .txt file including all the PIP below degree D, and a a .txt file including all selected generators set(FI) below degree D.

Bond length sequence: for atom $i$ and atom $j$ of a $N$-atoms system, the label of corresponding bondlength is $(N-1)i + j-1 -\frac{(i+1)i}{2}$.
Note that $i$, $j$ varies in $0,1,2,3,\cdots, N-1$ and the bondlength label varies from $0$ to $\frac{N(N-1)}{2}-1$.This is actually the sequence that is 
```
temp = 0;
for(i = 0; i < N; i++)
  for(j = i + 1; j < N; j++)
  {
    label[i, j] = temp;
    temp++;
  }
```
System included by this repository:
