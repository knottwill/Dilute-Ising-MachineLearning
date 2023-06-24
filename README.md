# Unsupervised Machine Learning applied to the Dilute Ising Model

This project was submitted in partial fulfillment of my Bachelor's of Science in Physics with Theoretical Physics at King's College London. 

In the scope of this project are three main accomplishments, namely:
1. Reproduced results from "Discovering phases, phase transitions, and
crossovers through unsupervised machine learning: A critical examination", Found at https://journals.aps.org/pre/abstract/10.1103/PhysRevE.95.062122
2. Presented a new method for finding the critical temperature using KMeans clustering. 
3. Extended this methodology to the dilute Ising model. 

### Abstract

In this report we investigate the extent to which unsupervised machine learning methods can decipher the underlying physics of the 2D dilute Ising model above the percolation threshold. We first reproduce results of applying principal component analysis (PCA) to the 2D pure Ising model, then present a method for finding the critical temperature using KMeans clustering, and finally we extend the same methodology to the 2D dilute Ising model with site concentration $p = 0.8$. We find that the clustering method is an accurate method for finding an estimate of the critical temperature when dealing with small datasets. This study determines that PCA and KMeans clustering can successfully distinguish between the ordered ferromagnetic phase and disordered paramagnetic phase of the dilute Ising model, and is capable of finding it's critical temperature, but is less accurate at doing so than for the pure Ising model.