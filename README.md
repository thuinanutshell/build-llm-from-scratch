# Build An LLM From Scratch

This repo follows the instructions from Raschka S. - Build A Large Language Model - 2025. I will add additional resources for each section.

### Definition

- Large Lanaguage Models (LLMs) are basically neural network trained on large amounts of publicly available text data.
- LLMs consists of hundreds to billions of parameters (weights) in the network optimized during training.

### Transformer Architecture (TA)

- TA consists of two submodules: encoder and decoder
- The encoder compresses a high-dimensional input which is text into a smaller dimensional representation (vectors) of the input.
- The decoder takes the encoded vectors to generate the output.
- In between the encoder and the decoder, there are many connected layers called _self-attention mechanism_, which allows the model to weight the importance of tokens in accordance to each other (context!)
