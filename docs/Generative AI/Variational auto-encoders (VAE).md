## Motivation for latent variable models ##

1. Capture latent features in a complex dataset
2. Latent variables $z$ correspond to high level features
### Motivation for latent variable models ###

Capture latent features in a complex dataset
Latent variables $z$ correspond to high level features
$p(x | z)$ is easier to compute than $p(x)$ and we could identify features using $p(z|x)$
Use NN to model 

???+ question "Phasellus posuere in sem ut cursus"

    - Unsupervised representation learning
    - Shallow LV model - Mixture of gaussians

where the feature $\mathbf{z}$ is simply a categorical variable 

$$
\mathbf{z} \sim categorical(1, ...., K)
$$

while $\mathbf{x}$ is a mixture of gaussians

$$
p(\mathbf{x | z} = k) = \mathcal{N}(\mu_k, \Sigma_k)
$$

Can use unsupervised clustering to extract latent features $z$
Can combine simple models to form more complex models

