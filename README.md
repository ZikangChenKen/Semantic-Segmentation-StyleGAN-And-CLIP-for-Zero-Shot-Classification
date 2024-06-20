# Semantic-Segmentation-StyleGAN-And-CLIP-for-Zero-Shot-Classification
Train a simple semantic segmentation network. Recall that in semantic segmentation, the algorithm must assign each pixel of an input image to one of K object classes.

Used StyleGAN2 for controlled image generation. Make sure to run the first 3 code cells of the StyleGAN section of the provided Colab notebook. The first cell installs StyleGAN2 and its dependencies. The second cell loads a pre-trained StyleGAN2 model for faces. The third cell provides you with some useful utility functions. Some preliminary code on how to generate synthetic faces using the utility functions is also provided in cell 4.

Used Contrastive Language-Image Pre-Training (CLIP) to perform zero-shot classification of images.
