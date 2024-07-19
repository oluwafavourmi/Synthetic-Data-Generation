# Synthetic-Data-Generation
# For experiments conducted in the 'synthetic_data.ipynb' note book:



##### In conclusion to this particular experiment differnt latent space values were used to test the Variational AutoEncoder in synthetic data generation and all experiments were passed through a vanilla AutoEncoder, using the encoder part of the vanilla AutoEncoder to visualize the synthetic data generated. The following were observed:

#####    1. In the original dataset, Majority  has an acsending structure, something of a postive corrrelation
![original plot of the dataset](https://github.com/oluwafavourmi/Synthetic-Data-Generation/blob/main/plots/original-LR.png)

#####    2. In the Generated Dataset of Latent Space = 2, we see also a slightly positive correlated data
![generated data latent space = 2](https://github.com/oluwafavourmi/Synthetic-Data-Generation/blob/main/plots/Latent%3D2.png)

#####    3. The Data Generated when the Latent Space = 20 is also similar to when it is = 2, but a bit converged than when the Latent Space = 2
![generated data latent space = 20](https://github.com/oluwafavourmi/Synthetic-Data-Generation/blob/main/plots/Latent%3D20.png)

#####    4. When the Latent Value was set to 50, we could see a highly positively correlated dataset, which is not close to what we're looking for.
![generated data latent space = 50](https://github.com/oluwafavourmi/Synthetic-Data-Generation/blob/main/plots/Latent%3D50.png)

#####    5. At 100, the Generated data lacks clear direction.
![generated data latent space = 100](https://github.com/oluwafavourmi/Synthetic-Data-Generation/blob/main/plots/Latent%3D100.png)

##### P.S This is still an ongoing project, updates can come in any moment
link to this repository: https://github.com/oluwafavourmi/Synthetic-Data-Generation