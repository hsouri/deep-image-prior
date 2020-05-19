 # Deep Learning Based Denoiser for ImagesRendered by Monte Carlo Sampling
 
 Note: The code is forked from https://dmitryulyanov.github.io/deep_image_prior. Please follow the instructions given in the link for installation and details of the code.

In this code, we design a denoiser for images rendered by Monte Carlo sampling, based on the approach introduced in "Deep Image Prior". We build on top of their design a new single image denoiser which works best for denoising the images rendered by Monte Carlo sampling. We try to benefit from additional features provided by Monte Carlo sampling such as normals, depth and etc. to improve the performance of denoiser. Our result show that using the features provided by the MC renderer in addition to a random matrix as the input of the neural networks often improve the quality of the denoised images. For more information please refer to the report. 

Note: Our implemtation is in the "the MonteCarlo-denoiser.ipynb" script. The denoised results are in the "Results-MonteCarloDenoising" folder.
