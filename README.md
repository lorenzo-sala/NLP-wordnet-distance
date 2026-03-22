# NLP Projects — WordNet, N-grams & FrameNet

A collection of three NLP projects developed with NLTK and spaCy, exploring
semantic similarity, language modeling, and lexical resource mapping.

## Projects

### 1. Semantic Distance based on WordNet
Computation of semantic similarity between word pairs using multiple
WordNet-based metrics: Wu-Palmer (WUP), Leacock-Chodorow (LC), and
shortest path distance. Results compared across metrics to analyze
their behavior on different semantic relationships.

`NLTK` `WordNet` `semantic similarity`

### 2. Modeling Social Media and Literary Language with N-grams
N-gram language models trained on tweets from public personalities,
used for next-token prediction. Explores the statistical properties
of informal vs. literary language through bigram and trigram models.

`NLTK` `N-grams` `language modeling` `next-token prediction`

### 3. FrameNet to WordNet Mapping
Manual annotation and semi-automatic mapping between FrameNet frames
and WordNet synsets, exploring the alignment between two major
English lexical resources.

`spaCy` `FrameNet` `WordNet` `lexical resources`

## Tools

`Python` `NLTK` `spaCy` `Jupyter Notebook`

## Requirements
```bash
pip install nltk spacy
python -m nltk.downloader wordnet framenet_v17
python -m spacy download en_core_web_sm
```
