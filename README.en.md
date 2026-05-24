# Bachelor's Thesis in Mathematics: The Transformers

This repository contains the Bachelor's Thesis in Mathematics, whose goal is to build a rigorous and comprehensive understanding of transformers — the architecture that revolutionised modern artificial intelligence.

## About the thesis

The thesis starts from the foundations of neural networks and progressively advances to a detailed explanation of the transformer architecture and its applications in Natural Language Processing (NLP).

### Chapter overview

1. **Introduction** — Historical journey from Turing's Test and the perceptron to the publication of *Attention Is All You Need* (2017), which introduced the transformer and gave rise to models such as GPT, BERT and Gemini.

2. **Neural Networks** — Mathematical formalisation of neural networks: activation vectors, weight matrices, activation functions, loss function, and the Softmax and LayerNorm functions that are key building blocks of the transformer.

3. **The Transformer** — Detailed analysis of the architecture: the self-attention mechanism, the query/key/value matrices (Q, K, V), multi-head attention, and the full architecture with residual connections and layer normalisation.

4. **Natural Language Processing** — How transformers process text: tokenisation (BPE algorithm), embeddings, and the three main architectural variants — encoder (BERT), decoder (GPT), and encoder-decoder — including masked self-attention and cross-attention.

5. **Implementation** — A full English-to-Spanish translator built from scratch in Python and PyTorch using an encoder-decoder architecture, trained on the OPUS100 corpus of one million sentence pairs.

## Resources

- The source code for the implemented translator is available at [github.com/skaczylo/Transformer-Translator](https://github.com/skaczylo/Transformer-Translator).
- The thesis is written in LaTeX using the TeXiS template.
