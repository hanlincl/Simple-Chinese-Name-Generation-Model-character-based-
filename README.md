# Simple-Chinese-Name-Generation-Model-character-based-
This project implements a character-based language model for generating Chinese names, specifically focusing on personal names used by the Han ethnicity, the largest ethnic group in China. The model is trained on the Chinese Names Corpus (1.2 million entries) curated by Wainshine (https://colab.research.google.com/drive/1JMLa53HDuA-i7ZBmqV7ZnA3c_fvtXnx-) and employs a Transformer-based character-level architecture, adapted from Karpathy’s code.

To evaluate the quality of generated names, three approaches are used:

1. Character frequency distribution comparison – to check how closely the generated names match real-world character usage patterns.

2. Perplexity measurement on the test set – to quantify the model’s predictive performance.

3. Sentiment analysis using SnowNLP – to assess the emotional or semantic tone of the names.

This project was conducted as part of the Natural Language Processing course by Thomas Simon Brochhagen at Universitat Pompeu Fabra (UPF) and was first uploaded on March 9th, 2026.

References:

[1]	Hou. C. H. (2023). 近四十年来汉语人名研究综述[A Review of Chinese Personal Name Research in the Past Four Decades] (Master’s Thesis, Sichuan International Studies University). https://doi.org/10.27348/d.cnki.gscwc.2023.000643.

[2]	Karpathy, Andrej. 2023. Let’s Build GPT: From Scratch, in Code, Spelled Out. Online tutorial and code notebook. https://colab.research.google.com/drive/1JMLa53HDuA-i7ZBmqV7ZnA3c_fvtXnx-

[3]	Wainshine. 2019. Chinese-Names-Corpus. GitHub repository. https://github.com/wainshine/Chinese-Names-Corpus
