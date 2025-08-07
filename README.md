# Quantum Galton Box Simulation 🪄🧩

End-to-end, *reproducible* simulations of the **Quantum Galton Board (QGB)**:

* **Paper-style physical peg** implementation  
  * fresh coin per layer → RIGHT→LEFT sweep  
  * matches classical **Binomial → Gaussian** when noise-free  
  * noise model (T₁, T₂, depolarizing, readout) + angle schedule optimizer  
* **Noiseless all-to-all samplers**  
  * **Exponential** distribution (`pₖ ∝ e^{-λk}`)  
  * **Hadamard quantum walk** distribution after *T* steps  
* **Verification suite**  
  * mean/variance, **TVD**, Hellinger, JS, KL, χ², Wasserstein-1, KS  
  * **95 % bootstrap CIs** for every metric  
* Fully-annotated Jupyter notebooks → copy-paste ready blocks & Markdown  
* Python ≥3.9 / PennyLane ≥0.36

