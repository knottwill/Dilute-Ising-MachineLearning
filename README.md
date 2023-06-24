# Dilute Ising Moel Machine Learning

This project was submitted in partial fulfillment of my Bachelor's of Science in Physics with Theoretical Physics at King's College London. 

### Abstract

In this report we investigate the extent to which unsupervised machine learning methods can decipher the underlying physics of the 2D dilute Ising model above the percolation threshold. We first reproduce results of applying principal component analysis (PCA) to the 2D pure Ising model, then present a method for finding the critical temperature using KMeans clustering, and finally we extend the same methodology to the 2D dilute Ising model with site concentration $p = 0.8$. We find that the clustering method is an accurate method for finding an estimate of the critical temperature when dealing with small datasets. This study determines that PCA and KMeans clustering can successfully distinguish between the ordered ferromagnetic phase and disordered paramagnetic phase of the dilute Ising model, and is capable of finding it's critical temperature, but is less accurate at doing so than for the pure Ising model.