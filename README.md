# Advanced Generative Modeling: Theory and Implementation

This repository contains the course material for **Advanced Generative Modeling**, 
focusing on the mathematical foundations and practical implementations of modern generative models 
using **PyTorch** and **JAX**.
---
The course also demonstrates generative modeling across **multiple data modalities**:

- **Text**
- **Image**
- **Acoustic / Sound**

The course is designed for learners who want a **deep mathematical understanding** followed by **hands-on model training**.

---

## Course Philosophy

- **Theoretical Understanding with JAX**  
  JAX is used to explore **mathematical derivations, gradient computations, and simplified prototypes**, 
  giving learners a clear view of the underlying concepts.  

- **Practical Implementation with PyTorch**  
  PyTorch is used for **full-scale implementations, model training, and experimentation** 
  on **text, image, and acoustic datasets**.

By the end of this course, learners will be capable of **deriving, implementing, and evaluating** generative models across multiple domains.

---

---
The course is divided into four main modules:  

1. **Foundations of Generative AI**  
2. **Generative Adversarial Networks (GANs)**  
3. **Latent Variable Models & Variational Autoencoders (VAEs)**  
4. **Diffusion Models (DDPMs)**  

Both **mathematical derivations** and **hands-on implementations** are included.

---

# Course Structure

---

## Module 1: Foundations of Generative AI
1. Gen AI Basics  
2. F-Divergence  
3. Variational Divergence Minimization  
4. Generative Modeling via Variational Divergence Minimization  
5. Proof of Jensen's Inequality  

---

## Module 2: Generative Adversarial Networks (GANs)
6. Generative Adversarial Network (GAN)  
7. GANs as Classifier-Guided Generative Models  
8. Deep Convolution GANs (DCGANs) and Conditional GANs (cGANs)  
9. Wasserstein GANs (WGAN)  
10. Bi-Directional GANs (BiGAN / ALI)  
11. GAN Inversion via Latent Regression  
12. Inversion with GANs  
13. Domain Adversarial Networks  
14. Evaluation of Generative Models  

---

## Module 3: Latent Variable Models & VAEs
15. Introduction to Latent Variable Models  
16. Gaussian Mixture Models: Expectation-Maximization Algorithm  
17. Evidence Lower Bound (ELBO)  
18. Variational Autoencoder (VAE)  
19. Training VAE: Reparameterization Methods  
20. Training VAE (Implementation in PyTorch/JAX)  
21. Inference with a Trained VAE  
22. β-VAE  
23. Vector Quantized VAE (VQ-VAE)  

---

## Module 4: Diffusion Models (DDPMs)
24. Denoising Diffusion Probabilistic Models (DDPMs)  
25. DDPM: Formulation (Forward and Reverse Processes)  
26. ELBO for DDPM  
27. Optimization of DDPM Loss  
28. ELBO Equivalence  
29. Training of DDPM  
30. U-Net (Backbone for DDPM)  
31. Inference in DDPM  
32. Implementation of DDPM  
33. Alternate Interpretations of DDPMs  
34. DDPMs as Score-Predictors  
35. Guided Diffusion Models  
36. Latent Diffusion Models (LDMs)  
37. Denoising Diffusion Implicit Models (DDIMs)  
38. Inference in DDIM  
39. Implementation of DDPM Noise Estimation  
40. Implementation of DDIM  
41. Implementation of Guided DDPM  

---

## Module 5: Auto-Regressive Models & Transformers
42. Auto-Regressive Models  
43. Attention Mechanism  
44. Transformers for Auto-Regressive Models  
45. Transformer Architecture  
46. Transformers: Skip Connections and Normalization  
47. Transformers: Position Embeddings  
48. Transformers: Training and Inference  

---

## Module 6: Reinforcement Learning for Generative AI
49. An Overview of Reinforcement Learning  
50. Policy Gradient Theorem  
51. Expressing an AR-LM as RL Policy  
52. Proximal Policy Optimization (PPO)  
53. Trust Region Policy Optimization (TRPO)  

---

## Module 7: Preference Optimization & State-Space Models
54. Reward Modelling  
55. Direct Preference Optimization (DPO)  
56. State-Space Models  

---


## Programming Frameworks

- **PyTorch**: For practical model implementations and training.  
- **JAX**: For mathematical derivations, gradients, and experimental implementations.

---

## Learning Objectives

By the end of this course, participants will be able to:

- Understand the **mathematical foundations** of modern generative models.  
- Implement **GANs, VAEs, and DDPMs** from scratch in PyTorch and JAX.  
- Evaluate generative models using **quantitative and qualitative metrics**.  
- Apply generative models to **sampling, reconstruction, and domain adaptation** tasks.  



