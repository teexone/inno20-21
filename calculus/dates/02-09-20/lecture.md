## Error
> If $x$ is the exact value and $\hat x$ is know approximation, therefore

<span style="text-align:center">

$\Delta(\hat x) := | x - \hat x |$

$\delta(\hat x) := \frac{\Delta(\hat x)}{|\hat x|}$



$x = \hat x + \Delta$

$\hat x - \Delta \le x \le \hat x + \Delta$

</span>

So $\delta(\hat x)$ is named _relational error_ and $\Delta(\hat x)$ is called
_absolute error_.

## Functions (mapping)

<span style="text-align:center">

$f : \forall x\in X : y \in Y y = f(x)$

or

$f(x) := \{y \in Y | \exists x$ $(x \in X \wedge y = f(x))\}$

or

$f: X \to Y$

</span>

## Mapping
- Subjective $x \to y \ | \ f(x) = y$
- Injective $\forall x_1x_2 \in X\ | \ f(x_1)=f(x_2) => x1 = x2$
- Bijective: injective and subjective

## Sequences

> A function $f : \natural \to X$ whose domain of definitions
is the set of natural numbers is called a sequence

> The terms of sequence is $f(n)$

> $x_n = f(n)$

> $\{x_n\} \equiv \{x_1, x_2, \dots, x_n\}$

### Limit

> A number $A$ belongs to the set of real numbers is called **the limit of
numerical sequence** if for every neighbourhood of A there exists such
 index N depending on neighbourhood of A, so $x_n \in V(A), \ n > N$.

 > $lim_{n\to \infty}x_n = A := \forall V(A) \exists N \in \natural \ \vdots
  \ \forall n > N (n \in V(a))$

> $lim_{n\to \infty}x_n := \forall \varepsilon > 0\ \exists\ N \in\ \natural \
\vdots\ \forall n > N \ \ |x_n - A| < \varepsilon$

#### Properites
> - If $\exists A \ \wedge\  \exists N \vdots\ x_n = A \forall n > N$, then $\{x_n\}$ is
ultimately constant
> - Any neighborhood of the limit of a sequence contains all but a finite number
of terms of the sequence
> - A convergent sequence cannot have two different limits.
> - A convergent sequence is bounded.

> $\{x_n\}$ and $\{y_n\}$ - numerical sequences. Then there is some product,
quotient and sum. $\{x_n + y_n\},\ \{x_n \cdot y_n\}, \ \{\frac{x_n}{y_n}\}$


### Convergent
> If $lim_{n\to \infty} = A$ and $x_n \to A$ as $n \to \infty$, then $\{x_n\}$
converges to A (tends to A)

> If a sequence does not have a limit, it is called divergent.
