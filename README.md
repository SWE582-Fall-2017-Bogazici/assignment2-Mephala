# assignment2
gradient descent with momentum and adaptive alpha

# Accelerating Gradient descent

## Momentum methods, a.k.a., heavy ball

\begin{align}
p(\tau) & =  \nabla E(w(\tau-1)) + \beta p(\tau-1) \\
w(\tau) & =  w(\tau-1) - \alpha p(\tau) 
\end{align}

When $\beta=0$, we recover gradient descent.
