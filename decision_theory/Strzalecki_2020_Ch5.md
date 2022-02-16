## Risk

### A modicum of probability

Let $S$ be the finite set of all states of the world. 

The state space is equipped with a probability distribution $P:S\rightarrow\left[0,1\right]$ such that $\sum_{s \in S} P\left(s\right)=1$. 

A collection of states is called an event. For any event $E \subset S$, we can extend the probability distribution using

$$P\left(E\right) = \sum_{s\in E} P\left(s\right)$$

This extension is called a probability measure. Probability measures must satisfy additivity 

$$\forall E \cap F = \empty : P(E\cap U) = P(E) + P(F)$$

Let $Z$ be a set of basic prizes and let $\Delta(Z)$ denote the set of all probability measures on $Z$. Expected utility preferences $\succsim$ over $\Delta(Z)$ are represented by

$$EU(p) = \sum_{z\in Z} u(z)p(z)$$

Random variable are function $f:S\rightarrow Z$. Let $\mathcal{F} = Z^S$ denote the set of random variables also known as acts.

Subjective expected utility of $f$ is defined by 

$$SEU(f) = \sum_{s \in S} u(f(s)) P(s)$$

The critical difference is that expected utility is defined over probability measures while subjective expected utility is defined over random variables (or acts).

Knowing a preference $\succsim$ on $\Delta(Z)$ carries more information than a preference $\succsim$ on $\mathcal{F}$ if $S$ is not "rich enough".

Expected utility is used to model situations in which probabilities are known to the agent, while subjective expected utilty is useful when different reasonable agents have different beliefs regarding probabilities. 

Expected utility is linear in $p$. To see this, we need some definitions. 

For any $z \in Z$, the Dirac measure $\delta_z \in \Delta(Z)$ attaches probability one to $z$.

For any two probability distributions $p,q \in \Delta(Z)$ and a number $\alpha \in \left[0,1\right]$, we define $\alpha p + (1 - \alpha) q \in \Delta(Z)$ which assigns probability $\alpha p(z) + (1 - \alpha) q(z)$ to each $z \in Z$.

Expected utility is linear in probabilities in the sense that $EU(\alpha p + (1 - \alpha) q)=\alpha EU(p) + (1 - \alpha) EU(q)$.

### Expected Utility 

A preference relation $\succsim$ has an expected utility representation if there exists a Bernoulli utility function $u:Z\rightarrow \mathbb{R}$ such that the function $U(p)=\sum_{z} u(z) p(z)$ represents $\succsim$.


