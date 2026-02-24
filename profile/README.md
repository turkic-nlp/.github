<p align="center">
  <strong>NLP toolkit for 20+ Turkic languages</strong> — a pip-installable open-source Python library with adaptations for the low-resource, morphologically rich Turkic language family.
</p>

<p align="center">
  Maintained by <a href="https://sherzod-hakimov.github.io/">Sherzod Hakimov</a>
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-Apache%202.0-blue.svg" alt="License: Apache-2.0"></a>
  <a href="https://www.python.org/downloads/"><img src="https://img.shields.io/badge/python-3.9+-blue.svg" alt="Python 3.9+"></a>
  <img src="https://img.shields.io/badge/status-pre--alpha-orange.svg" alt="Status: Pre-Alpha">
  <img src="https://img.shields.io/badge/languages-24_Turkic-green.svg" alt="24 Turkic Languages">
</p>

## Citation

If you use TurkicNLP in your research, please cite:

```bibtex
@misc{hakimov2026turkicnlpnlptoolkit,
      title={TurkicNLP: An NLP Toolkit for Turkic Languages}, 
      author={Sherzod Hakimov},
      year={2026},
      eprint={2602.19174},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2602.19174}, 
}
```

## Features

- **24 Turkic languages** from Turkish to Sakha, Kazakh to Uyghur
- **Script-aware from the ground up** — Latin, Cyrillic, Perso-Arabic, Old Turkic Runic
- **Automatic script detection** and bidirectional transliteration
- **Morphology analyser** for ~20 Turkic languages
- **Universal dependencies integration** — pretrained tokenization, POS tagging, lemmatization, dependency parsing, and NER
- **Pretrained embeddings + translation backend** — get vectors for sentences and translate across many languages
- **License** - Apache-2.0

## Supported Languages and Components

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/f/fa/Turkic_Languages_distribution_map.png" alt="Distribution map of Turkic languages" width="700">
  <br>
  <em>Geographic distribution of Turkic languages (source: <a href="https://commons.wikimedia.org/wiki/File:Turkic_Languages_distribution_map.png">Wikimedia Commons</a>)</em>
</p>

## Open-source Library

[https://github.com/turkic-nlp/turkicnlp](https://github.com/turkic-nlp/turkicnlp)

## Code Samples

[https://github.com/turkic-nlp/turkic-nlp-code-samples](https://github.com/turkic-nlp/turkic-nlp-code-samples)


## Installation

```bash
pip install turkicnlp
```

To install all required dependencies at once:
```bash
pip install "turkicnlp[all]"
```

With optional dependencies:

```bash
pip install "turkicnlp[stanza]"        # Stanza/UD neural models
pip install "turkicnlp[all]"           # Everything: stanza, NLLB embeddings & translations
pip install "turkicnlp[dev]"           # Development tools
```

## More info 
[https://turkic-nlp.github.io/](https://turkic-nlp.github.io/)
