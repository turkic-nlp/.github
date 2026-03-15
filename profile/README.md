<p align="center">
  <img src="https://sherzod-hakimov.github.io/images/cover.png" alt="TurkicNLP" width="180">
</p>

<h1 align="center">TurkicNLP</h1>

<p align="center">
  <b>Open-source NLP toolkit for 24 Turkic languages</b><br>
  From Turkish to Sakha, Kazakh to Uyghur — tokenization, morphology, POS tagging, dependency parsing, NER, transliteration, embeddings, and machine translation in one <code>pip install</code>.
</p>

<p align="center">
  <a href="https://arxiv.org/abs/2602.19174"><img src="https://img.shields.io/badge/arXiv-2602.19174-b31b1b.svg" alt="arXiv"></a>
  <a href="https://github.com/turkic-nlp/turkicnlp"><img src="https://img.shields.io/badge/License-Apache%202.0-blue.svg" alt="License"></a>
  <img src="https://img.shields.io/badge/languages-24_Turkic-green.svg" alt="24 Languages">
  <img src="https://img.shields.io/badge/scripts-Latin_%7C_Cyrillic_%7C_Arabic_%7C_Runic-purple.svg" alt="4 Script Families">
</p>

---

**Why TurkicNLP?** Over 200 million people speak a Turkic language, yet most lack basic NLP tools. TurkicNLP bridges this gap with a unified Python library covering 6 language branches — Oghuz, Kipchak, Karluk, Siberian, Oghur, and Arghu — plus historical languages like Ottoman Turkish and Old Turkic runic inscriptions.

### Highlights

- **Morphological analysis** via rule-based FSTs (~20 languages) and neural models (21 languages)
- **Multi-script support** — automatic detection and bidirectional transliteration (Cyrillic ↔ Latin, Arabic ↔ Latin, Runic → Latin)
- **Neural pipelines** — POS tagging, lemmatization, dependency parsing, and NER models
- **Embeddings & translation** — sentence vectors and machine translation
- **Morpheme tokenizer** — hybrid neural+FST segmentation with labeled morphemes for 16 languages

### Quick start

```bash
pip install "turkicnlp[all]"
```

```python
import turkicnlp
turkicnlp.download("kaz")
nlp = turkicnlp.Pipeline("kaz", processors=["tokenize", "pos", "lemma", "depparse"])
doc = nlp("Мен мектепке бардым")
```

### Explore

| | |
|---|---|
| **Library** | [turkic-nlp/turkicnlp](https://github.com/turkic-nlp/turkicnlp) |
| **Code samples** | [turkic-nlp/turkic-nlp-code-samples](https://github.com/turkic-nlp/turkic-nlp-code-samples) |
| **Paper** | [arXiv:2602.19174](https://arxiv.org/abs/2602.19174) |
| **Website** | [turkic-nlp.github.io](https://turkic-nlp.github.io/) |

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/f/fa/Turkic_Languages_distribution_map.png" alt="Turkic languages map" width="600">
  <br>
  <em>Turkic languages span from Turkey to Siberia, China to the Balkans</em>
</p>

---

<p align="center">
  Maintained by <a href="https://sherzod-hakimov.github.io/">Sherzod Hakimov</a> · Contributions welcome
</p>
