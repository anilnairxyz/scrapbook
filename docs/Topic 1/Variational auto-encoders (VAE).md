### Motivation for latent variable models ###

Capture latent features in a complex dataset
Latent variables $z$ correspond to high level features
$p(x | z)$ is easier to compute than $p(x)$ and we could identify features using $p(z|x)$
Use NN to model 

!!! note "Phasellus posuere in sem ut cursus"

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

Unsupervised representation learning
Shallow LV model - Mixture of gaussians
where the feature $\mathbf{z}$ is simply a categorical variable 

$$
\Large \mathbf{z} \sim categorical(1, ...., K)
$$

while $\mathbf{x}$ is a mixture of gaussians

$$
\Large p(\mathbf{x | z} = k) = \mathcal{N}(\mu_k, \Sigma_k)
$$

Can use unsupervised clustering to extract latent features $z$
Can combine simple models to form more complex models

