# Model Distribution Formulas

---

### 1️⃣ Normal (Gaussian) Distribution
\[
p(x) = \frac{1}{\sqrt{2 \pi \sigma^2}} e^{-\frac{(x-\mu)^2}{2\sigma^2}}
\]

---

### 2️⃣ Uniform Distribution
\[
p(x) =
\begin{cases} 
\frac{1}{b-a}, & a \le x \le b \\ 
0, & \text{otherwise} 
\end{cases}
\]

---

### 3️⃣ Exponential Distribution
\[
p(x) = \lambda e^{-\lambda x}, \quad x \ge 0
\]

---

### 4️⃣ Beta Distribution
\[
p(x) = \frac{x^{\alpha-1}(1-x)^{\beta-1}}{B(\alpha,\beta)}, \quad 0<x<1
\]

---

### 5️⃣ Dirichlet Distribution
\[
p(\mathbf{x}) = \frac{1}{B(\boldsymbol{\alpha})} 
\prod_{i=1}^K x_i^{\alpha_i-1}, 
\quad \sum_i x_i = 1
\]
