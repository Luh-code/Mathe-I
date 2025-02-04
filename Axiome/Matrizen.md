## Kommutativität
- $A + B = B + A$
## Assoziativität
- $A + (B +C) = (A +B) + C$
- $k(hA) = (kh)A$
## Distributivität
- $k(A + B) = kA + kB$
- $(k + h)A = kA + hA$
## Neutrales Element
- $A + 0 = A \implies$ 0 ist das neutrale Element
- $1A = A \implies$ 1 ist das neutrale Element
## Inverses Element
- $A + A^{-1} = 0 \implies$ Existenz eines inversen Elements
# Transposition
- $(A+B)^T = A^T + B^T$
- $(kA)^T = kA^T$
- $(A^T)^T = A$
- Spiegelung an der Haupt-diagonalen
# Quadratische Matrix
- Eine Matrix wird eine quadratische Matrix genannt, wenn $n=m$
- Kurzform: $\mathbb{R}^{n\times n} = \mathbb{R}^{n}$
# Einheitsmatrix
- $A \cdot \mathbb{I}_{n} = A = \mathbb{I}_m\cdot A = A$
- Eine Quadratische Matrix multipliziert mit der passenden Einheitsmatrix, ergibt die ursprüngliche Matrix
- Die Einheitsmatrix wird als $I_n$ geschrieben, wobei n für die Dimension der Matrix steht
## Kronecker Delta
$$\delta_{jk} = \begin{cases}
0, \quad \text{falls } j \neq k\\
1, \quad \text{falls } j = k
\end{cases}$$
Definition von $\mathbb{I} = \delta_{jk}$.
# Multiplikation
## Skalar
- $(kA)B = k(AB) = A(kB)$ -- schreibt man daher auch einfach $kAB$
## Assoziativgesetz
- A(BC) = (AB)C
## Distributivgesetze
- $(A+B)C = AC+BC$
- $A(B+C) = AB+BC$
- $(AB)^T = B^TA^T$
# Inverse Matrix
- Falls eine Matrix $AA^{-1} = A^{-1}A = A = \mathbb{I}$ erfüllt nennt man sie __invertierbar__ oder __regulär__
- Die Matrix $A^{-1}$ nennt man daher auch die Inverse Matrix von $A$
- Die Inverse Matrix von A hat immer die selber dimension wie A
## Berechnung
- Die Inverse Matrix ist die Matrix B welche $AB = \mathbb{I}$ erfüllt 