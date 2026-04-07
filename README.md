# **COCO-EX: A Tool for Linking Concepts from Texts to ConceptNet**

**Maria Becker, Katharina Korfhage, Anette Frank**  

[![Paper](https://img.shields.io/badge/Paper-EACL%202021-blue)](https://aclanthology.org/2021.eacl-demos.15/)  
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)  
![Python](https://img.shields.io/badge/Python-3.6%2F3.7-blue)  

---

## 📄 Paper

**COCO-EX: A Tool for Linking Concepts from Texts to ConceptNet**  
Proceedings of the **EACL 2021 System Demonstrations**

👉 https://aclanthology.org/2021.eacl-demos.15/  

---

## 📚 Citation

If you use **CoCo-Ex** in your research, please cite:

```bibtex
@inproceedings{becker-etal-2021-cocoex,
  title     = {COCO-EX: A Tool for Linking Concepts from Texts to ConceptNet},
  author    = {Becker, Maria and Korfhage, Katharina and Frank, Anette},
  booktitle = {Proceedings of the 16th Conference of the European Chapter of the Association for Computational Linguistics: System Demonstrations},
  year      = {2021},
  publisher = {Association for Computational Linguistics},
  url       = {https://aclanthology.org/2021.eacl-demos.15/}
}
```

---

## 📄 Overview

CoCo-Ex is a tool for extracting concepts from texts and linking them to the ConceptNet knowledge graph, developed by Maria Becker, Katharina Korfhage and Anette Frank from the NLP Lab at Heidelberg University.  

CoCo-Ex extracts meaningful concepts from natural language texts and maps them to conjunct concept nodes in ConceptNet, utilizing the maximum of relational information stored in the ConceptNet knowledge graph.  

It takes into account the challenging characteristics of ConceptNet, namely that nodes are represented as non-canonicalized, free-form text.  

A commonly used shortcut for mapping phrases from natural language text to ConceptNet is to apply string matching, but given the non-normalized nature of the concepts in ConceptNet, this can result in an incomplete and noisy mapping, and a lot of relational knowledge in ConceptNet gets lost.  

Instead, CoCo-Ex enables the extraction of meaningful, important rather than overspecific or uninformative concepts, and allows to assess more relational information stored in the knowledge graph.  

---

## 🎥 Demo

Check out our system demonstration video on YouTube:  
👉 https://www.youtube.com/watch?v=bgqVhE2vR9A&feature=youtu.be  

---

## 📬 Contact

For questions or comments:  
📧 maria.becker@gs.uni-heidelberg.de  

---

## 📜 License

This project is licensed under the terms of the **MIT License**.  

---

## ⚙️ Requirements

CoCo-Ex is written in Python and requires the following software components:

- Python 3.6 / 3.7  
- spacy 2.3.5  
- nltk 3.5  
- gensim 3.8.3  
- pandas 1.2  
- stanford parser 3.9.2  
