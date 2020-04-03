# VAE-GAN Pegasus

**Aim**: Produce images of Pegasi from the CIFAR10 dataset.
**Chosen Network**: VAE-GAN
**Conclusion**: Due to the large intra-class variability, images were blurrier than expected. Having to interpolate between encodings/latent spaces meant the target feature (wings) were not as common. Nevertheless, the quality of results are better than the standard VAE (and was easier to train than a GAN).    

<p align="center">
  <b>Encoder Network</b>
</p>

![Encoder](/Encoder.png)

<br><br>

<p align="center">
  <b>Decoder Network</b>
</p>

![Decoder](/Decoder.png)

<br><br>

<p align="center">
  <b>Discriminator Network</b>
</p>

![Discriminator](/Discriminator.png)

<br><br>

<p align="center">
  <b>Complete Network</b>
</p>

![Network](/Network.png)

<br><br>

<p align="center">
  <b>Results</b>
</p>

![Results](/Batch.png)


