# Equality of Sets via Subsets

## Statement

\textit{Theorem}: Let $A$ and $B$ be sets. Then $A=B$ if and only if $A\subseteq B$ and $B\subseteq A$.

## Proof
$(\implies)$ Let $A$ and $B$ be sets with $A=B$. By this very definition, if $x\in A$, then $x\in B$, which fits the definition that $A\subseteq B$. Similarly, if $x\in B$, then $x\in A$, so $B\subseteq A$.

$(\impliedby$) Now suppose that we have $A\subseteq B$ and $B\subseteq A$. If we have $x\in A$, then since $A\subseteq B$ this means that $x\in B$. Similarly, if $x\in B$, then since $B\subseteq A$ we have $x\in A$. We therefore have $x\in A$ if and only if $x\in B$, which by the Axiom of Extensionality means that $A=B$.
