# Encoder-Decoder-Transformer

 We will use **[PyTorch](https://pytorch.org/) + [Lightning](https://www.lightning.ai/)** to create and optimize an encoder-decoder transformer, like the one shown in the picture below.

<img src="https://github.com/StatQuest/signa/blob/main/chapter_12/images/enc_dec_transformer.png?raw=1" alt="an encoder-decoder neural network" style="width: 800px;">


- **[Code a Position Encoder Class From Scratch!!!](#position)** The position encoder class will give the encoder and the decoder a way to keep track of the order of the input tokens in the encoder and the decoder.

- **[Code an Attention Class From Scratch!!!](#attention)** The attention class will allow us to keep track of how words in the input and output are related to each other

- **[Code an Encoder Class From Scratch!!!](#encoder)** The encoder will process the input.

- **[Code a Decoder Class From Scratch!!!](#decoder)** The decoder will generate the output.

- **[Code a Transformer Class From Scratch!!!](#transformer)** The transformer class will connect all the pieces, the position encoder, attention, the encoder and the decoder.

- **[Train the Transformer!!!](#train)** We'll train the transformer to translate simple English phrases into Spanish.

- **[Use the Trained Transformer!!!](#use)** Finally we'll use the transformer to translate simple English phrases into Spanish.
