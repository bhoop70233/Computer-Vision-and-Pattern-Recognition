# computer vision -Research-Paper


| S.No  |  Research Papers | Abstract| Link   |
|---|---|---| ---|
|1.|SceneCraft: Layout-Guided 3D Scene Generation |The creation of complex 3D scenes tailored to user specifications has been a tedious and challenging task with traditional 3D modeling tools. Although some pioneering methods have achieved automatic text-to-3D generation, they are generally limited to small-scale scenes with restricted control over the shape and texture. We introduce SceneCraft, a novel method for generating detailed indoor scenes that adhere to textual descriptions and spatial layout preferences provided by users. Central to our method is a rendering-based technique, which converts 3D semanticlayouts into multi-view 2D proxy maps. Furthermore, we design a semantic and depth conditioned diffusion model to generate multi-view images, which are used to learn a neural radiance field (NeRF) as the final scene representation. Without the constraints of panorama image generation, we surpass previous methods in supporting complicated indoor space generation beyond a single room, even as complicated as a whole multi-bedroom apartment with irregular shapes and layouts. Through experimental analysis, we demonstrate that our method significantly outperforms existing approaches in complex indoor scene generation with diverse textures, consistent geometry, and realistic visual quality.|[✍️](https://arxiv.org/pdf/2410.09049)|

|2.|Learning Representations and Generative Models for 3D Point Clouds|Three-dimensional geometric data offer an excellent domain for studying representation learning and generative modeling. In this paper, we look at geometric data represented as point clouds. We introduce a deep AutoEncoder (AE) network with state-of-the-art reconstruction quality and generalization ability. The learned representations outperform existing methods on 3D recognition tasks and enable shape editing via simple algebraic manipulations, such as semantic part editing, shape analogies and shape interpolation, as well as shape completion. We perform a thorough study of different generative models including GANs operating on the raw point clouds, significantly improved GANs trained in the fixed latent space of our AEs, and Gaussian Mixture Models (GMMs). To quantitatively evaluate generative models we introduce measures of sample fidelity and diversity based on matchings between sets of point clouds. Interestingly, our evaluation of generalization, fidelity and diversity reveals that GMMs trained in the latent space of our AEs yield the best results overall.|[✍️](https://arxiv.org/pdf/1707.02392)|

|3.|Do GANs actually learn the distribution? An empirical study|Do GANS (Generative Adversarial Nets) actually learn the target distribution? The foundational paper of (Goodfellow et al 2014) suggested they do, if they were given “sufficiently large” deep nets, sample size, and computation time. A recent theoretical analysis in Arora et al (to appear at ICML 2017) raised doubts whether the same holds when discriminator has finite size. It showed that the training objective can approach its optimum value even if the generated distribution has very low support —in other words, the training objective is unable to prevent mode collapse. The current note reports experiments suggesting that such problems are not merely theoretical. It presents empirical evidence that well-known GANs approaches do learn distributions of fairly low support, and thus presumably are not learning the target distribution. The main technical contribution is a new proposed test, based upon the famous birthday paradox, for estimating the support size of the generated distribution.|[✍️](https://arxiv.org/pdf/1706.08224)|

