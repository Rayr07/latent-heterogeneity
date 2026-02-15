# Latent Heterogeneity in Multimodal Survival Prediction

This project investigates why multimodal survival models show unstable performance and demonstrates that this instability arises from **latent patient heterogeneity**, not model limitations.



##  Key Idea
Survival prediction is not globally consistent — it is **conditional on underlying patient subgroups**.


## Approach
- Multimodal transformer (histopathology + RNA)
- Extract latent embeddings
- Unsupervised clustering (K-Means)
- Evaluate cluster stability (ARI)
- Train conditional survival models


## Results
- Global model: unstable (C-index 0.45–0.72)  
- Two latent clusters discovered (11% vs 29% events)  
- Significant survival separation (**p = 4.3e-05**)  
- Conditional models: **higher accuracy + lower variance**


## Project Website
[View Website](https://rayr07.github.io/latent-heterogeneity/)


## Author
**Rishika Ray**  
Manipal University Jaipur
