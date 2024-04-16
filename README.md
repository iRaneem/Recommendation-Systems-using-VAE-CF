# Recommendation Systems using (VAE-CF)

In this project, we have explored the research paper titled [Variational Autoencoders for Collaborative Filtering](https://arxiv.org/pdf/1802.05814v1.pdf) and implemented its findings. We aim to further improve upon the proposed methodology to contribute to the advancement of personalized recommendations and push the boundaries of existing techniques.

**Objective:**  
The objective of this project is to leverage Variational Autoencoders (VAEs) for Collaborative Filtering (CF) in recommendation systems. Collaborative filtering predicts user preferences by discovering and utilizing similarity patterns across users and items. By extending VAEs to CF, we can overcome the limitations of linear factor models and explore non-linear probabilistic models, enabling us to handle large-scale recommendation datasets.

**Methodology:**  
We propose a generative model with a multinomial conditional likelihood, which has been widely used in language modeling and economics but receives less attention in the recommender systems literature. We leverage Bayesian inference for parameter estimation and introduce a different regularization parameter to achieve competitive performance. Additionally, we establish information-theoretic connections to maximum entropy discrimination and the information bottleneck principle. Through empirical experiments, we compare the proposed approach with state-of-the-art baselines, including neural network approaches, on real-world datasets. We also conduct extended experiments to compare the multinomial likelihood with other commonly used likelihood functions in the latent factor collaborative filtering literature.

**Contributions:**  
By implementing the findings of the research paper and enhancing the proposed methodology, we aim to make the following contributions:
- Advancement of personalized recommendations in recommendation systems.
- Pushing the boundaries of existing techniques in collaborative filtering.
- Evaluation and comparison of different likelihood functions in the context of latent factor models.
- Identification of the benefits and drawbacks of employing a principled Bayesian inference approach.
- Characterization of settings where the Bayesian approach provides the most significant improvements.

We believe that our implementation and enhancements will contribute to the field of recommendation systems and drive further research in the area of personalized recommendations.

To access the original research paper, please click [here](https://arxiv.org/pdf/1802.05814v1.pdf).
