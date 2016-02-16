# Bilinear maps

A bilinear map is defined as 
$e : G \times G -> G_t$,
where
\[
(\forall u,v):
e(g^u,g^v) =  e(g,g)^{uv}.
\]

In applications, $e$ is easy
to compute and non-trivial.

What bilinear maps give us,
among possibly many other things,
is that we can cheat to solve
CDH problem for once and only once, by
\[
\hat{g}^{st} = e(g, g)^{st} = e(g^s, g^t).
\]

Once we used $e$, we cannot use it
again to solve another CDH problem in $G$,
since all we have is an element from $G_t$.
