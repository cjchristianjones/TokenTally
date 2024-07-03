# TokenTally
A Google web extension that estimates token counts of selected text under different popular tokenzing algorithms.

### Tokenizing Algorithms
# Tokenization Algorithms and Associated Models

| Tokenization Algorithm | Description | Notable Models/Libraries |
|------------------------|-------------|--------------------------|
| Byte-Pair Encoding (BPE) | Iteratively merges most frequent pair of bytes or characters | - GPT-2, GPT-3 (OpenAI) <br> - RoBERTa (Facebook) <br> - XLM (Facebook) |
| WordPiece | Similar to BPE, but uses likelihood instead of frequency | - BERT (Google) <br> - DistilBERT (Hugging Face) <br> - ALBERT (Google) |
| SentencePiece | Treats the input as a sequence of Unicode characters | - XLNet (Google) <br> - ALBERT (Google) <br> - T5 (Google) |
| Unigram Language Model | Iteratively removes subtokens to maximize likelihood of the training data | - ALBERT (Google) <br> - Some versions of SentencePiece |
| Byte-level BPE | BPE applied to byte sequences instead of unicode characters | - GPT-2, GPT-3 (OpenAI) <br> - CLIP (OpenAI) |
| Character-level | Splits text into individual characters | - Some RNN models <br> - Early NLP models |
| Word-level | Splits text on whitespace and punctuation | - Word2Vec <br> - GloVe |
| Tiktoken | OpenAI's fast BPE tokenizer implementation | - ChatGPT <br> - GPT-3.5, GPT-4 (OpenAI) |
