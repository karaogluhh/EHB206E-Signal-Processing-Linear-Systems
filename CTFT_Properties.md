```math
\begin{align}
		\hline & \textbf{Property}                &\qquad & \textbf{Time domain} 		&\qquad & \textbf{CTFT domain} \\ \hline
		\\[.05em]
		& \textrm{Linearity}               &\qquad &  A x(t) + B y(t) 			&\qquad &  A X(\Omega) + B Y(\Omega) \\
		\\[.05em]
		& \textrm{Time Shifting}           &\qquad &  x(t-t_0) 					&\qquad &  X(\Omega) e^{-j \Omega t_0} \\
		\\[.05em]
		& \textrm{Time Scaling}            &\qquad &  x(\alpha t) 				&\qquad &  \frac{1}{|\alpha|} X\left( \frac{\Omega}{\alpha} \right) \\
		\\[.05em]
		& \textrm{Frequency Shifting}      &\qquad &  x(t) e^{j \Omega_0 t} 	&\qquad &  X(\Omega-\Omega_0) \\
		\\[.05em]
		& \textrm{Conjugation}             &\qquad &  x^{*}(t) 					&\qquad &  X^*(-\Omega) \\
		\\[.05em]
		& \textrm{Time Reversal}           &\qquad &  x(-t) 					&\qquad &  X(-\Omega) \\
		\\[.05em]
		& \textrm{Convolution}             &\qquad &  x(t) * y(t)  				&\qquad &  X(\Omega) Y(\Omega) \\
		\\[.05em]
		& \textrm{Multiplication}          &\qquad &  x(t) y(t) 				&\qquad &  \frac{1}{2 \pi} X(\Omega) * Y(\Omega)  \\
		\\[.05em]
		& \textrm{Differentiation}         &\qquad &  \frac{d }{dt} x(t) 		&\qquad &  (j \Omega) X(\Omega) \\
		\\[.05em]
		& \textrm{Integration}             &\qquad &  \int_{-\infty}^{t} x(\tau) \, d \tau &\qquad &  \left( \frac{1}{j \Omega} \right) X(\Omega) \\
		\\[.05em]
		& \textrm{Conjugate Symmetry} 		&\qquad &  x(t) \textrm{ is real } &\qquad &  X(\Omega) =  X^*(-\Omega) \\
		\\[.05em]
		& \textrm{Real and Even Signals}   &\qquad &  x(t) \textrm{ is real and even } 	&\qquad &  X(\Omega) \textrm{ is real and even} \\
		\\[.05em]
		& \textrm{Real and Odd Signals}    &\qquad &  x(t) \textrm{ is real and odd } 		&\qquad &  X(\Omega) \textrm{ is purely imaginary and odd } \\
		\\[.05em]
		& \textrm{Parseval's Relation}     &\qquad &  \int_{-\infty}^{\infty} |x(t)|^2 \, dt &\qquad &  \frac{1}{2 \pi} \int_{-\infty}^{\infty} |X(\Omega)|^2 \, d\Omega \\
		\end{align}
   ```
