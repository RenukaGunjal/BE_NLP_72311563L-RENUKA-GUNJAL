1. Problem Statement (Easy)

  To implement a Transformer model from scratch using the PyTorch library and understand how attention-based models work in NLP tasks.

 2. Explanation (Simple Words)

  A Transformer is a deep learning model used in NLP that works using attention mechanism instead of RNN or LSTM.
  
  🔹 Steps involved:
  Embedding
  Convert words into vectors (numbers)
  Positional Encoding
  Add position information to words (since Transformer doesn’t read sequentially like RNN)
  Multi-Head Attention
  Model focuses on different parts of the sentence at the same time
  Feed Forward Network
  Further processes the output of attention
  Add & Normalize
  Improves stability and performance
  Encoder & Decoder
  Encoder → understands input
  Decoder → generates output

3. Conclusion

The Transformer model uses attention mechanisms to process text efficiently and in parallel. It overcomes the limitations of RNNs and is widely used in modern NLP tasks like translation, chatbots, and text generation.
