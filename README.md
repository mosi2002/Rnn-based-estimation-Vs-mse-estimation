# Rnn-based-estimation-Vs-mse-estimation

This repository contains an implementation of a Long Short-Term Memory (LSTM) model and MSE merhod for two-link arm.


# Model Details

Equation:

\[
\dot{x} = \begin{bmatrix}
\theta_1 \\
\theta_2 \\
\frac{u_1 - \text{damping1} \cdot \theta_1}{I1} \\
\frac{u_2 - \text{damping2} \cdot \theta_2}{I2}
\end{bmatrix}
\]

Where:
- \(\theta_1\) and \(\theta_2\) are the angles of the first and second joints.
- \(\dot{\theta}_1\) and \(\dot{\theta}_2\) are the angular velocities.
- \(I1\) and \(I2\) are the moments of inertia of the first and second links.
- \(u_1\) and \(u_2\) are the torques applied to the joints.
- \(\text{damping1}\) and \(\text{damping2}\) are the damping coefficients.



