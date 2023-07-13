# lambdal/stable-diffusion-image-variation Cog model

This is an implementation of the model [lambdal/stable-diffusion-image-variation](https://replicate.com/lambdal/stable-diffusion-image-variation) as a Cog model. [Cog packages machine learning models as standard containers.](https://github.com/replicate/cog)

First, download the pre-trained weights:

    cog build -t sd-image-variation

Then, you can run predictions:

    cog predict -i input_image=@demo.jpg
