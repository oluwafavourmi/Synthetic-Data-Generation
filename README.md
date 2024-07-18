# Synthetic-Data-Generation
# For experiments conducted in the 'synthetic_data.ipynb' note book:

##### In conclusion to this particular experiment differnt latent space values were used to test the Variational AutoEncoder in synthetic data generation and all experiments were passed through a vanilla AutoEncoder, using the encoder part of the vanilla AutoEncoder to visualize the synthetic data generated. The following were observed:

#####    1. In the original dataset, Majority  has an acsending structure, something of a postive corrrelation
#####    2. In the Generated Dataset of Latent Space = 2, we see also a slightly positive correlated data
#####    3. The Data Generated when the Latent Space = 20 is also similar to when it is = 2, but a bit converged than when the Latent Space = 2
#####    4. When the Latent Value was set to 50, we could see a highly positively correlated dataset, which is not close to what we're looking for.
#####    5. At 100, the Generated data lacks clear direction.

##### P.S This is still an ongoing project, updates can come in any moment