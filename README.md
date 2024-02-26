# a-simple-DDPM

Study notes on the diffusion model, including derivation of mathematical formulas and code implementation. A simple Unet model was created and trained using the CIFAR10 dataset. The model undergoes a forward noise addition and a reverse noise reduction process.

## CIFAR10
<p align = 'center'>
<img src = img/cifar10.png width = "500" height = "500" />
</p>

## forward diffusion
The process of gradually introducing noise into the original image until it becomes white noise.
<p align = 'center'>
<img src = img/forward_diffusion.png />
</p>

## result
The process of restoring an image from white noise.
<p align = 'center'>
<img src = img/infer_result1.png width = "600" height = "150" />
</p>
<p align = 'center'>
<img src = img/infer_result2.png width = "600" height = "150" />
</p>
Due to the inherent blurriness of the training set, the generated images are not very clear.
