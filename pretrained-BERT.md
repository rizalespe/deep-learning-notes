# BERT Mountain
1. BERT, paper: https://arxiv.org/abs/1810.04805
2. Transformer, paper: https://arxiv.org/abs/1706.03762
3. Attention, paper: https://arxiv.org/abs/1409.0473
4. Encoder-Decoder & Bi-LSTM
5. RNN & LSTM

nb: _RNN & LSTM is the most basic_

# Pretrained representation
- Context-free:
  - Word2vec
  - Glove
- Contextual
  - Unidirectional
  - Bidirectional
    - BERT (Bidirectional Encoder Representation from Transformer)

# BERT's Vocabulary
- BERT is pre-trained and the vocabulary is fixed
- To handling unknown token (token that does not exist in vocabulary), BERT breakdown the word into subwords. Ex: "embedding"--> em, bed, ding   

# Coding Tutorial
- BERT Tokenization https://albertauyeung.github.io/2020/06/19/bert-tokenization.html
- Multi-task coding tutorial https://github.com/ThilinaRajapakse/simpletransformers
- Fine-tuning BERT model for sentence-pairs classification https://github.com/NadirEM/nlp-notebooks/blob/master/Fine_tune_ALBERT_sentence_pair_classification.ipynb
- How to Code BERT Using PyTorch – Tutorial With Examples https://neptune.ai/blog/how-to-code-bert-using-pytorch-tutorial

# Blog arcticle
- BERT Explaination (https://www.kdnuggets.com/2018/12/bert-sota-nlp-model-explained.html)
- How to decode (https://huggingface.co/blog/how-to-generate)
- Various decoding strategies (https://huggingface.co/blog/how-to-generate)
