# CNN-RNN_Project
Fundamentals of CNN and RNN with keras &amp; tensorflow libs

# Objectives

## CNN part
- We are to implement a **multi-class image classifier** using CNNs
- Original images of **224 \* 224 pixel**, **15 different classes** (of vegetables)

- We should consider **2 input sizes** (grayscale images):
  - **31 \* 31 Pixels** - labelled `"a"` throughout this notebook
  - **128 \* 128 Pixels** - labelled `"b"` throughout this notebook
  
## RNN part
- Building a __next word predictor__, given a sequence of words
- We would try to __predict__ the next __10 words__ for each given input of words
- Find ways to __evaluate__ generated sequence of words (how meaningful / creative), using __seed_texts__ as benchmark
