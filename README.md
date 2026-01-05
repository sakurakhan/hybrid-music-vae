# Hybrid Language Music Clustering using Beta-VAE

This project implements an unsupervised learning pipeline for clustering hybrid-language
(English and Bangla) music tracks using Variational Autoencoders (VAE).

## Overview
We use a multi-modal Beta-VAE that learns disentangled latent representations from:
- Audio MFCC features
- Lyrics embeddings
- Genre metadata

Clustering is performed on the learned latent space using K-Means, Agglomerative Clustering,
and DBSCAN.

## Dataset
Synthetic hybrid dataset:
- 100 music tracks
- 50 English songs
- 50 Bangla songs

## Methods
- Beta-VAE for representation learning
- UMAP for latent space visualization
- Clustering evaluation using Silhouette Score, ARI, NMI, and Davies–Bouldin Index

## Results
Results and plots are available in the `results/` directory.

## How to Run
Open the notebook:
