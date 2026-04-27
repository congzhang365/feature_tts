This is a repository for the project of 

## Integrating Human Linguistic Insights into AI: Theory-Driven Representation for Multilingual Text-to-Speech 

by Cong Zhang<sup>1</sup>, Huinan Zeng<sup>2</sup>, Huang Liu<sup>3</sup>, Jiewen Zheng<sup>3</sup>

<sup>1</sup> Speech and Language Sciences, Newcastle University;
<sup>2</sup>Faculty of Linguistics, Philology and Phonetics, University of Oxford, Oxford, UK;
<sup>3</sup> Shengrurenxin Ltd., Beijing, China



### Abstract

This paper explores the integration of human linguistic insights into multilingual text-to-speech (TTS) systems by evaluating the Featurally Underspecified Lexicon (FUL) as a theory-driven input representation. Unlike data-intensive end-to-end models, FUL offers a compact, interpretable feature set grounded in phonological principles, enabling scalable and equitable TTS development for low-resource languages. We provided a mapping between language-specific phones to FUL feature vectors via a SAMPA intermediate and incorporate these features into a modified FastSpeech architecture. Experiments were conducted to test their capability of generating native, non-native, and code-mixed speech in English and Mandarin. We ran an experiment with a small dataset and one with a larger dataset, which showed that TTS with FUL features as input could produce intelligible native speech with as little as 8 hours of training data; with 100 hours of training data, intelligible speech could be generated for a language which was not in the training data. The approach further supports code-mixed synthesis while preserving consistent timbre and interpretable phonetic control. These results highlight the potential of theory-driven representations for building efficient, scalable, and linguistically informed TTS systems, demonstrating that phonological features can function as both analytical tools and practical inputs for speech technology.

**Keywords**: phonological feature, text-to-speech, multilingual TTS, non-native speech, FUL model



### Demo

Visit https://congzhang365.github.io/feature_tts/ for demo audio.



### Historical version:

```
Zhang, C., Zeng, H., Liu, H., Zheng, J. (2021) Applying Feature Underspecified Lexicon Phonological Features in Multilingual Text-to-Speech. 
Retrived from https://arxiv.org/abs/2204.07228.
```

or use the following BibTex:

```

@misc{https://doi.org/10.48550/arxiv.2204.07228,
  doi = {10.48550/ARXIV.2204.07228},
  
  url = {https://arxiv.org/abs/2204.07228},
  
  author = {Zhang, Cong and Zeng, Huinan and Liu, Huang and Zheng, Jiewen},
  
  title = {Applying Feature Underspecified Lexicon Phonological Features in Multilingual Text-to-Speech},
  
  publisher = {arXiv},
  
  year = {2022},
  
  copyright = {Creative Commons Attribution 4.0 International}
}

```

