# **CoCo-Ex**

CoCo-Ex is a tool for extracting concepts from texts and linking them to the ConceptNet knowledge graph, developed by Maria Becker, Katharina Korfhage and Anette Frank from the NLP Lab at Heidelberg University.  

---

## 📄 Overview

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

---

## 🚀 Usage

### 1. Entity Extraction

Run the following command:

```bash
python CoCo-Ex_entity_extraction.py "path/to/inputfile.csv" "path/to/outputfile.tsv"
