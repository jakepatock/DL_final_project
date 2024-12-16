# DL_final_project
## Crossing Modalities: Integrating NLP Architectural Innovations into Vision Transformers
### Abstract
Since its proposal in 2017, the Natural Language
Processing (NLP) sequence transformer architecture has become
a staple in the Machine Learning world. Its brilliant yet
simplistic approach of replacing convolutional or recurrent-based
architectures with an attention-based architecture expanded the
computational ability to analyze more significant inputs and out-
puts such as images, audio, and video. In this paper, we analyze
the efficiency and expressiveness of five proposed architecture
advancements of the original visual transformer (ViT): Root
Mean Square Layer Normalization (RMS Norm), Gated Linear
Unit (GLUs), Expanded Activation, ReZero, and Rotary. Also,
four hybrid models using said advancements were benchmarked
on a simple image classification task using Imagenette, a smaller
10-class subset of the ImageNet dataset containing approximately
10,000 images, chosen due to computational constraints. The
ViTs were evaluated using the macro average precision (MAP)
metric in relation to the MAP score of the original transformer
architecture. The best model (Hybrid 2 using GLUs, rotary
positional encoding, and RMS Norms) resulted in an increase
8.51% MAP over the baseline model from simple architectural
modification alone. Given the widespread usage of PyTorch and
TensorFlow for NLP tasks, we utilized both frameworks during
model building and training.
