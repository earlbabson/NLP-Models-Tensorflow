# NLP-Models-Tensorflow

Gathers machine learning and tensorflow deep learning models for NLP problems.

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRkJOooEC5KxVQCKsPLNx-ayYxHOZZVS_gNW8lyCr-dvCv5-dZXlA" align="right" width="20%">

![alt text](https://img.shields.io/badge/total%20models-202--models-blue.svg)

## Table of contents
  * [Text classification](https://github.com/huseinzol05/NLP-Models-Tensorflow#text-classification)
  * [Chatbot](https://github.com/huseinzol05/NLP-Models-Tensorflow#chatbot)
  * [Neural Machine Translation](https://github.com/huseinzol05/NLP-Models-Tensorflow#neural-machine-translation-english-to-vietnam)
  * [Embedded](https://github.com/huseinzol05/NLP-Models-Tensorflow#embedded)
  * [Entity-Tagging](https://github.com/huseinzol05/NLP-Models-Tensorflow#entity-tagging)
  * [POS-Tagging](https://github.com/huseinzol05/NLP-Models-Tensorflow#pos-tagging)
  * [Question-Answers](https://github.com/huseinzol05/NLP-Models-Tensorflow#question-answers)
  * [Summarization](https://github.com/huseinzol05/NLP-Models-Tensorflow#summarization)
  * [Stemming](https://github.com/huseinzol05/NLP-Models-Tensorflow#stemming)
  * [Generator](https://github.com/huseinzol05/NLP-Models-Tensorflow#generator)
  * [OCR (optical character recognition)](https://github.com/huseinzol05/NLP-Models-Tensorflow#ocr)
  * [Speech to Text](https://github.com/huseinzol05/NLP-Models-Tensorflow#speech-to-text)
  * [Text Similarity](https://github.com/huseinzol05/NLP-Models-Tensorflow#text-similarity)
  * [Miscellaneous](https://github.com/huseinzol05/NLP-Models-Tensorflow#Miscellaneous)
  * [Attention](https://github.com/huseinzol05/NLP-Models-Tensorflow#attention)

### Text classification

1. Basic cell RNN
2. Bidirectional RNN
3. LSTM cell RNN
4. GRU cell RNN
5. LSTM RNN + Conv2D
6. K-max Conv1d
7. LSTM RNN + Conv1D + Highway
8. LSTM RNN with Attention
9. Neural Turing Machine
10. Seq2Seq
11. Bidirectional Transformers
12. Dynamic Memory Network

<details><summary>Complete list (58 notebooks)</summary>

1. Basic cell RNN
2. Basic cell RNN + Hinge
3. Basic cell RNN + Huber
4. Basic cell Bidirectional RNN
5. Basic cell Bidirectional RNN + Hinge
6. Basic cell Bidirectional RNN + Huber
7. LSTM cell RNN
8. LSTM cell RNN + Hinge
9. LSTM cell RNN + Huber
10. LSTM cell Bidirectional RNN
11. LSTM cell Bidirectional RNN + Huber
12. LSTM cell RNN + Dropout + L2
13. GRU cell RNN
14. GRU cell RNN + Hinge
15. GRU cell RNN + Huber
16. GRU cell Bidirectional RNN
17. GRU cell Bidirectional RNN + Hinge
18. GRU cell Bidirectional RNN + Huber
19. LSTM RNN + Conv2D
20. K-max Conv1d
21. LSTM RNN + Conv1D + Highway
22. LSTM RNN + Basic Attention
23. LSTM Dilated RNN
24. Layer-Norm LSTM cell RNN
25. Only Attention Neural Network
26. Multihead-Attention Neural Network
27. Neural Turing Machine
28. LSTM Seq2Seq
29. LSTM Seq2Seq + Luong Attention
30. LSTM Seq2Seq + Bahdanau Attention
31. LSTM Seq2Seq + Beam Decoder
32. LSTM Bidirectional Seq2Seq
33. Pointer Net
34. LSTM cell RNN + Bahdanau Attention
35. LSTM cell RNN + Luong Attention
36. LSTM cell RNN + Stack Bahdanau Luong Attention
37. LSTM cell Bidirectional RNN + backward Bahdanau + forward Luong
38. Bytenet
39. Fast-slow LSTM
40. Siamese Network
41. LSTM Seq2Seq + tf.estimator
42. Capsule layers + RNN LSTM
43. Capsule layers + LSTM Seq2Seq
44. Capsule layers + LSTM Bidirectional Seq2Seq
45. Nested LSTM
46. LSTM Seq2Seq + Highway
47. Triplet loss + LSTM
48. DNC (Differentiable Neural Computer)
49. ConvLSTM
50. Temporal Convd Net
51. Batch-all Triplet-loss + LSTM
52. Fast-text
53. Gated Convolution Network
54. Simple Recurrent Unit
55. LSTM Hierarchical Attention Network
56. Bidirectional Transformers
57. Dynamic Memory Network
58. Entity Network

</details>

### Chatbot

1. Seq2Seq-manual
2. Seq2Seq-API Greedy
3. Bidirectional Seq2Seq-manual
4. Bidirectional Seq2Seq-API Greedy
5. Bidirectional Seq2Seq-manual + backward Bahdanau + forward Luong
6. Bidirectional Seq2Seq-API + backward Bahdanau + forward Luong + Stack Bahdanau Luong Attention + Beam Decoder
7. Bytenet
8. Capsule layers + LSTM Seq2Seq-API + Luong Attention + Beam Decoder

<details><summary>Complete list (40 notebooks)</summary>

1. Basic cell Seq2Seq-manual
2. LSTM Seq2Seq-manual
3. GRU Seq2Seq-manual
4. Basic cell Seq2Seq-API Greedy
5. LSTM Seq2Seq-API Greedy
6. GRU Seq2Seq-API Greedy
7. Basic cell Bidirectional Seq2Seq-manual
8. LSTM Bidirectional Seq2Seq-manual
9. GRU Bidirectional Seq2Seq-manual
10. Basic cell Bidirectional Seq2Seq-API Greedy
11. LSTM Bidirectional Seq2Seq-API Greedy
12. GRU Bidirectional Seq2Seq-API Greedy
13. Basic cell Seq2Seq-manual + Luong Attention
14. LSTM Seq2Seq-manual + Luong Attention
15. GRU Seq2Seq-manual + Luong Attention
16. Basic cell Seq2Seq-manual + Bahdanau Attention
17. LSTM Seq2Seq-manual + Bahdanau Attention
18. GRU Seq2Seq-manual + Bahdanau Attention
19. LSTM Bidirectional Seq2Seq-manual + Luong Attention
20. GRU Bidirectional Seq2Seq-manual + Luong Attention
21. LSTM Bidirectional Seq2Seq-manual + Bahdanau Attention
22. GRU Bidirectional Seq2Seq-manual + Bahdanau Attention
23. LSTM Bidirectional Seq2Seq-manual + backward Bahdanau + forward Luong
24. GRU Bidirectional Seq2Seq-manual + backward Bahdanau + forward Luong
25. LSTM Seq2Seq-API Greedy + Luong Attention
26. GRU Seq2Seq-API Greedy + Luong Attention
27. LSTM Seq2Seq-API Greedy + Bahdanau Attention
28. GRU Seq2Seq-API Greedy + Bahdanau Attention
29. LSTM Seq2Seq-API Beam Decoder
30. GRU Seq2Seq-API Beam Decoder
31. LSTM Bidirectional Seq2Seq-API + Luong Attention + Beam Decoder
32. GRU Bidirectional Seq2Seq-API + Luong Attention + Beam Decoder
33. LSTM Bidirectional Seq2Seq-API + backward Bahdanau + forward Luong + Stack Bahdanau Luong Attention + Beam Decoder
34. GRU Bidirectional Seq2Seq-API + backward Bahdanau + forward Luong + Stack Bahdanau Luong Attention + Beam Decoder
35. Bytenet
36. LSTM Seq2Seq + tf.estimator
37. Capsule layers + LSTM Seq2Seq-API Greedy
38. Capsule layers + LSTM Seq2Seq-API + Luong Attention + Beam Decoder
39. LSTM Bidirectional Seq2Seq-API + backward Bahdanau + forward Luong + Stack Bahdanau Luong Attention + Beam Decoder + Dropout + L2
40. DNC Seq2Seq

</details>

### Neural Machine Translation (English to Vietnam)

1. Seq2Seq-manual
2. Seq2Seq-API Greedy
3. Bidirectional Seq2Seq-manual
4. Bidirectional Seq2Seq-API Greedy
5. Bidirectional Seq2Seq-manual + backward Bahdanau + forward Luong
6. Bidirectional Seq2Seq-API + backward Bahdanau + forward Luong + Stack Bahdanau Luong Attention + Beam Decoder
7. Bytenet

<details><summary>Complete list (36 notebooks)</summary>

1. Basic cell Seq2Seq-manual
2. LSTM Seq2Seq-manual
3. GRU Seq2Seq-manual
4. Basic cell Seq2Seq-API Greedy
5. LSTM Seq2Seq-API Greedy
6. GRU Seq2Seq-API Greedy
7. Basic cell Bidirectional Seq2Seq-manual
8. LSTM Bidirectional Seq2Seq-manual
9. GRU Bidirectional Seq2Seq-manual
10. Basic cell Bidirectional Seq2Seq-API Greedy
11. LSTM Bidirectional Seq2Seq-API Greedy
12. GRU Bidirectional Seq2Seq-API Greedy
13. Basic cell Seq2Seq-manual + Luong Attention
14. LSTM Seq2Seq-manual + Luong Attention
15. GRU Seq2Seq-manual + Luong Attention
16. Basic cell Seq2Seq-manual + Bahdanau Attention
17. LSTM Seq2Seq-manual + Bahdanau Attention
18. GRU Seq2Seq-manual + Bahdanau Attention
19. LSTM Bidirectional Seq2Seq-manual + Luong Attention
20. GRU Bidirectional Seq2Seq-manual + Luong Attention
21. LSTM Bidirectional Seq2Seq-manual + Bahdanau Attention
22. GRU Bidirectional Seq2Seq-manual + Bahdanau Attention
23. LSTM Bidirectional Seq2Seq-manual + backward Bahdanau + forward Luong
24. GRU Bidirectional Seq2Seq-manual + backward Bahdanau + forward Luong
25. LSTM Seq2Seq-API Greedy + Luong Attention
26. GRU Seq2Seq-API Greedy + Luong Attention
27. LSTM Seq2Seq-API Greedy + Bahdanau Attention
28. GRU Seq2Seq-API Greedy + Bahdanau Attention
29. LSTM Seq2Seq-API Beam Decoder
30. GRU Seq2Seq-API Beam Decoder
31. LSTM Bidirectional Seq2Seq-API + Luong Attention + Beam Decoder
32. GRU Bidirectional Seq2Seq-API + Luong Attention + Beam Decoder
33. LSTM Bidirectional Seq2Seq-API + backward Bahdanau + forward Luong + Stack Bahdanau Luong Attention + Beam Decoder
34. GRU Bidirectional Seq2Seq-API + backward Bahdanau + forward Luong + Stack Bahdanau Luong Attention + Beam Decoder
35. Bytenet
36. LSTM Seq2Seq + tf.estimator

</details>

### Embedded

1. Word Vector using CBOW sample softmax
2. Word Vector using CBOW noise contrastive estimation
3. Word Vector using skipgram sample softmax
4. Word Vector using skipgram noise contrastive estimation
5. Lda2Vec Tensorflow
6. Supervised Embedded
7. Triplet-loss + LSTM
8. LSTM Auto-Encoder
9. Batch-All Triplet-loss LSTM

### POS-Tagging

1. GRU Bidirectional + CRF
2. LSTM Bidirectional + CRF
3. LSTM Seq2Seq-manual
4. CNN + CRF

### Entity-Tagging

1. LSTM Bidirectional + Char embedded + Static + CRF
2. LSTM Bidirectional + Char embedded + Dynamic + CRF

### Question-Answers

1. End-to-End + Basic
2. End-to-End + GRU
3. End-to-End + LSTM

### Stemming

1. LSTM + Seq2Seq + Beam
2. GRU + Seq2Seq + Beam
3. LSTM + BiRNN + Seq2Seq + Beam
4. GRU + BiRNN + Seq2Seq + Beam
5. DNC + Seq2Seq + Greedy

### Summarization

1. LSTM Seq2Seq
2. LSTM Seq2Seq + Luong Attention
3. LSTM Seq2Seq + Beam Decoder
4. LSTM Bidirectional + Luong Attention + Beam Decoder
5. Skip-thought Vector

### OCR (optical character recognition)

1. CNN + LSTM RNN

### Speech to Text

1. Tacotron
2. Bidirectional RNN + Greedy CTC
3. Bidirectional RNN + Beam CTC
4. Seq2Seq + Bahdanau Attention + Beam CTC
5. Seq2Seq + Luong Attention + Beam CTC
6. Bidirectional RNN + Attention + Beam CTC

### Generator

1. Character-wise RNN + LSTM
2. Character-wise RNN + Beam search

### Text Similarity

1. Character wise similarity + LSTM + Bidirectional
2. Word wise similarity + LSTM + Bidirectional
3. Character wise similarity Triplet loss + LSTM
4. Word wise similarity Triplet loss + LSTM

### Attention

1. Bahdanau
2. Luong
3. Hierarchical
4. Additive
5. Soft
6. Attention-over-Attention
7. Bahdanau API
8. Luong API

### Miscellaneous

1. Attention heatmap on Bahdanau Attention
2. Attention heatmap on Luong Attention

### Not-deep-learning

1. Markov chatbot
2. Decomposition summarization (3 notebooks)
