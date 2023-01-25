The energy of a continuous-time signal $x(t)$
```math 
E_x=\int_{-\infty}^{\infty} |x(t)|^2 dt
```
The energy of a discrete-time signal $x[n]$ is
```math
E_x=\sum_{n=-\infty}^{\infty} |x[n]|^2
```

## Dirac Signal
The Dirac signal (continuous-time impulse signal) is defined by
```math
\delta(t) = \left\{
				\begin{eqnarray}
					\infty &\quad& \textrm{for} \quad t = 0 \\
					0	&\quad& \textrm{for} \quad t \neq 0
				\end{eqnarray}
				\right.
```
where


```math
\int_{-\infty}^{\infty} \delta(t) dt = 1
```

The Kronecker signal (discrete-time impulse signal) is defined by

```math
\delta[n] = \left\{
				\begin{eqnarray}
					1 &\quad& \textrm{for} \quad n = 0 \\
					0	&\quad& \textrm{for} \quad n \neq 0
				\end{eqnarray}
				\right.
```

### The properties of impulse signals:
- Energy: $E_x =$ not well defined
- Power: $P_x = 0$
- Even / Odd?: Even (Understanding why is beyond the purview of this course. You will not be tested on this.)
- Periodic?: No
- Causal?: Yes

## Step Functions
The continuous-time step function $u(t)$ is defined by
```math
u(t) = \int_{-\infty}^{t} \delta(\tau) d\tau
				= \left\{
				\begin{eqnarray}
					1 &\quad& \textrm{for} \quad t \geq 0 \\
					0 &\quad& \textrm{for} \quad t < 0
				\end{eqnarray}
				\right.
```

The discrete-time step function $u[n]$ is defined by
```math
u[n] = \sum_{k = -\infty}^{n} \delta[k]
				= \left\{
				\begin{eqnarray}
					1 &\quad& \textrm{for} \quad n \geq 0 \\
					0 &\quad& \textrm{for} \quad n < 0
				\end{eqnarray}
				\right.
```

### The properties of the Heaviside step functions:
- Energy: $E_x=\infty$
- Power: $P_x=1/2$
- Even / Odd?: Neither
- Periodic?: No
- Causal?: Yes
