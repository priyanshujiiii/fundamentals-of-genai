# Model Distribution Visualization using JAX

This project visualizes **various probability distributions** using **JAX** for sampling and **Matplotlib/Seaborn** for visualization.  

We cover the following distributions:

---

## 1️⃣ Normal (Gaussian) Distribution

- **Formula**:  
  $$
  p(x) = \frac{1}{\sqrt{2 \pi \sigma^2}} e^{-\frac{(x-\mu)^2}{2\sigma^2}}
  $$

- **Parameters**:  
  - Mean \( \mu \)  
  - Standard Deviation \( \sigma \)

---

## 2️⃣ Uniform Distribution

- **Formula**:  
  $$
  p(x) =
  \begin{cases} 
  \frac{1}{b-a}, & a \le x \le b \\ 
  0, & \text{otherwise} 
  \end{cases}
  $$

- **Parameters**:  
  - \( a \) = minimum value  
  - \( b \) = maximum value  

---

## 3️⃣ Exponential Distribution

- **Formula**:  
  $$
  p(x) = \lambda e^{-\lambda x}, \quad x \ge 0
  $$

- **Parameter**:  
  - \( \lambda \) = rate parameter

---

## 4️⃣ Beta Distribution

- **Formula**:  
  $$
  p(x) = \frac{x^{\alpha-1}(1-x)^{\beta-1}}{B(\alpha,\beta)}, \quad 0<x<1
  $$

- **Parameters**:  
  - \( \alpha \) = shape parameter 1  
  - \( \beta \) = shape parameter 2  

---

## 5️⃣ Dirichlet Distribution

- **Formula**:  
  $$
  p(\mathbf{x}) = \frac{1}{B(\boldsymbol{\alpha})} 
  \prod_{i=1}^K x_i^{\alpha_i-1}, 
  \quad \sum_i x_i = 1
  $$

- **Parameter**:  
  - \( \boldsymbol{\alpha} = [\alpha_1, \alpha_2, ..., \alpha_K] \)

---

## 📊 Visualization

The notebook samples **10,000 values** from each distribution using `jax.random` and visualizes their **histograms and density curves** using **Seaborn**.

Example output:

- Normal distribution: bell-shaped curve
- Uniform distribution: flat histogram
- Exponential distribution: decaying curve
- Beta distribution: skewed to one side
- Dirichlet distribution: shown as histogram of the first component

---

## 🚀 Usage in Google Colab

1. Open the notebook in **Google Colab**.
2. Run the code cells to **generate samples and visualize distributions**.
3. Formulas can be viewed in this README or as **Markdown cells with LaTeX** in Colab.
