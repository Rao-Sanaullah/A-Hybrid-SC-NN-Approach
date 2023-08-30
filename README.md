# A-Hybrid-SC-NN-Approach

In this article, we propose a novel standalone hybrid Spiking-Convolutional Neural Network (SC-NN) model for advancing Computer Vision. Our approach uses the unique capabilities of SNNs, such as event-based computation and temporal processing, along with the strong representation learning abilities of CNNs, to generate high-quality results. 

The hybrid approach aims to create a more comprehensive and biologically inspired model that can effectively handle complex inpainting tasks. Therefore, The fusion of SNN and CNN architectures enables the model to capture both the local and temporal aspects of visual data, potentially leading to improved performance and more efficient processing in tasks such as image inpainting.

The attached Figure (a) computes the membrane potential, generates spikes when the potential crosses the threshold, resets potential, and produces output. Also, Figure (b) demonstrates the equivalent circuit model of the LIF neural model.

![LIF Model](https://github.com/Rao-Sanaullah/A-Hybrid-SC-NN-Approach/blob/main/lif.png)

In the attached Figure, the test images containing a missing or corrupted region and the model attempt to restore the missing part of the image using the hybrid SC-NN approach.

![Test Image](https://github.com/Rao-Sanaullah/A-Hybrid-SC-NN-Approach/blob/main/2.png)




References:

[1]- Lsdir dataset: A large-scale dataset for images. https://data.vision.ee.ethz.ch/yawli/index.html. Accessed on 2013-07-12.


For any help, please contact

Sanaullah (sanaullah@hsbi.de)
