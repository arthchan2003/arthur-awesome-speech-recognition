# arthur-awesome-speech-recognition

(Work in Progress)

Here is a collection of my own reading in speech recognition and related topics.

## Speech Recognizers

### wav2vec2-related papers

The five most important ones which everyeone should read -

- [wav2vec 2.0: A Framework for Self-Supervised Learning of Speech Representations (Baevski et al., 2020)](https://arxiv.org/abs/2006.11477).

- [Unsupervised Cross-lingual Representation Learning for Speech Recognition (Conneau et al., 2020)](https://arxiv.org/abs/2006.13979).

- [Self-training and Pre-training are Complementary for Speech Recognition (Xu et al., 2020)](https://arxiv.org/abs/2010.11430).

- [Robust wav2vec 2.0: Analyzing Domain Shift in Self-Supervised Pre-Training (Hsu, et al., 2021)](https://arxiv.org/abs/2104.01027).

- [Simple and Effective Zero-shot Cross-lingual Phoneme Recognition (Xu et al., 2021)](https://arxiv.org/abs/2109.11680).

The models

- [Published by Meta](https://github.com/facebookresearch/fairseq/tree/main/examples/wav2vec#wav2vec-20)

Later development

- [XLS-R: Self-supervised Cross-lingual Speech Representation Learning at Scale](https://arxiv.org/abs/2111.09296) [(The repo)](https://github.com/facebookresearch/fairseq/tree/main/examples/wav2vec/xlsr)

- [W2v-BERT: Combining Contrastive Learning and Masked Language Modeling for Self-Supervised Speech Pre-Training](https://arxiv.org/abs/2108.06209)

- [Seamless M4T: Massively Multilingual & Multimodal Machine Translation](https://arxiv.org/abs/2308.11596)

### Whisper

The original paper
- [Robust Speech Recognition via Large-Scale Weak Supervision (Redford, 2022)](https://arxiv.org/abs/2212.04356)

Open Whisper-style Speech Model (OWSM)
- [Reproducing Whisper-Style Training Using an Open-Source Toolkit and Publicly Available Data (Peng, 2023)](https://arxiv.org/abs/2309.13876) - An impressive effort from CMU WavLab to replicate Whisper enc-dec style training.
- [OWSM v3.1: Better and Faster Open Whisper-Style Speech Models based on E-Branchformer (Peng, 2024)](https://arxiv.org/abs/2401.16658)

## Speech Datasets

### Some general websites
- [Open SLR](https://www.openslr.org/resources.php) Collections of free speech dataset.
- [LDC](https://catalog.ldc.upenn.edu/) OG of language resources. Fees for non-members can be hefty.

### Individual Datasets grouped by languages

Multilingual

- [Babel](https://en.wikipedia.org/wiki/BABEL_Speech_Corpus) (Where is it now?)
- [Voxpopuli](https://github.com/facebookresearch/voxpopuli) Collected from 2009-2020 European Parliament event recordings. >400k hours of data. ([Paper](https://aclanthology.org/2021.acl-long.80/))
- [Multilingual LibriSpeech (MLS)](https://www.openslr.org/) A multilingual version of libri-light.  It's still heavily tilted towards English, but it also contains significant amount of German, Spanish and 6 other languages. ([Paper](https://arxiv.org/pdf/2012.03411))
- [Common Voice](https://commonvoice.mozilla.org/en/datasets) A multilingual dataset.  When you test on CV, remember that there are multiple versions of the dataset.  On HuggingFace, also know that some of these databases are gated. (i.e. required login)

English-only

- [Librispeech](https://www.openslr.org/12) One of the golden benchmarks in ASR.  ([Paper](https://www.danielpovey.com/files/2015_icassp_librispeech.pdf))
- [Libri-Light](https://github.com/facebookresearch/libri-light) In a sense, it is the extension of Librispeech but with 60k hour of unlabelled data. wav2vec2's models prefixed with -Lv60 are speech representation, for example, are all pre-trained with this dataset. ([Paper](https://arxiv.org/abs/1912.07875))

Portuguese

- [CORAA](https://github.com/nilc-nlp/CORAA) 290.77 hours of spontaneous speech. ([Paper](https://arxiv.org/abs/2110.15731))
- [The BP Dataset](https://github.com/lucasgris/wav2vec4bp) 400 hours. ([Paper](https://arxiv.org/abs/2107.11414))

Cantonese
- CommonVoice and MLS both have subsets on Cantonese
- [MDCC Dataset](https://github.com/HLTCHKUST/cantonese-asr) (The [Paper](https://arxiv.org/pdf/2201.02419.pdf) is also a survey on different Cantonese dataset.)

### Conferences 
- [ICSA Archive](https://www.isca-archive.org/index.html) If you want to search for all Interspeech conference papers. (Or Eurospeech/ICSLP if you still remember them...)
- [ICASSP](https://dblp.org/db/conf/icassp/index.html) Another OG yearly conference on speech.  Sad. Not all the paper are archived. So you may need to try your luck to see if the authors put them on archive.

The two are specific to speech.  These days peeps love to publish on AAAI and NeurIPS.  You know where to find them already. 

### Journals
- [IEEE/ACM Transactions on Audio, Speech, and Language Processing](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=6570655) It used to be called IEEE Transactions on Audio, Speech, Processing, or "ASP" in short.  Now it's called "ASLP" I guess.

### AI-related groups I admin (and browse daily)
- Plug - I admin AIDL [Facebook](https://www.facebook.com/groups/DeepNetGroup) and [LinkedIn](https://www.linkedin.com/groups/12846050/).
