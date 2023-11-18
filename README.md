## Open Korean Corpora: A Living Document for Korean NLP Dataset Curation



![image](./image.png)

### Overview
- Korean, a language with 80M users is often overlooked in NLP research
- The availability of public datasets and tasks has hindered investigation
- Even the publicly available datasets are not always accompanied by English documentation and have poor discoverability
- Our work attempts to tackle this problem by curating a living document of open resources for the Korean language

### NLP-OSS @ EMNLP 2020

We will be in the [live session](https://virtual.2020.emnlp.org/workshop_WS-9.html) and monitoring the [slide chat](https://emnlp2020.rocket.chat/channel/paper-nlposs-17) during EMNLP 2020. If you have any questions or would simply want to drop by to say hello, please drop by!

### Public Institutions
Multiple government-funded institutions create datasets for the Korean language
- National Institute of Korean Language (NIKL)
- Electronics and Telecommunications Research Institute (ETRI)
- NIA AI HUB
#### Generally, government funded datasets tend to be very restrictive at allowing access to non-Korean citizens
#### Thus, *Open Corpora* here denotes a freely accessible and downloadable (at least only with a simple sign-in) dataset

### Open Dataset for Korean NLP
Our work focuses on curating open Korean corpora under the following criteria:
- Documentation status
- License for use and distribution

#### Documentation and License
For documentation status *Docu.* the following holds.
- **doc** - Does the corpus have any documentation on the usage?
- **art** - Does the corpus have a related article?
- **inter** - Does the corpus have a internationally available publication?

#### License
For *License*, we check the followings:
- Commercially available (**com**), academic use only (**acad**), unknown (**unk**)
- Redistribution is available with/without modification (**rd** and **rd/mod-x**), neither (**no**), unknown (**unk**)

#### Other Attributes
- In *Providers*, we note if the dataset is provided by universities or institutes (Academia), companies or the research group thereof (Industry), or something combined, as Competition purpose.
- In *Volume*, (w) denotes words, (s) denotes sentences, (p) denotes pairs (either document or sentence pairs), (d) denotes dialogues, (h) denotes hours, and (u) denotes speech utterances.
- In *Goal*, Eval is noted if the purpose is suggested as an evaluation.

#### View at a Glance
The table below describes the open Korean corpora investigated so far. To be updated along with our survey or PR. You can visit [Here](https://github.com/songys/AwesomeKorean_Data) for the Korean description, and more information regarding government-driven database.



1. Benchmark studies

| No | Dataset | Typical Usage | Provider | Docu. | License | Redist. | mod-x | Volume | Goal | Lang. |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BM-1 | KLUE | Benchmark studies | Industry | int'l | all | rd | 0 | DP - 15K (s), DST - 10K (d), MRC - 29K (p), NER - 31K (s), NLI - 30K (p), RE - 48K (s), STS - 13K (p), TC - 64K (s)   | Eval | ko |
| BM-1 | KoBEST | Benchmark studies | Industry | int'l | all | rd | 0 | BoolQ - 6K (p), COPA - 5K (s), KB-WiC - 6K (s), KB-HellaSwag - 3K (p & s), SentiNeg - 4K (s) | Eval | ko |


2. Parsing and tagging   

| PT-1 | KAIST Morpho-Syntactically Annotated Corpus | Morphological analysis | Academia | paper | academic | no | 0 | 70M (w) | - | ko |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| PT-2 | OpenKorPOS | Morphological analysis | Academia | int'l | all | rd | 0 | 55M(w) | - | ko |
| PT-3 | KAIST Korean Tree-Tagging Corpus | Tree parsing | Academia | int'l | academic | no | 0 | 30K (s) | - | ko |
| PT-4 | UD Korean KAIST | Dependency parsing | Academia | int'l | academic | no | 1 | 27K (s) | - | ko |
| PT-5 | PKT-UD | Dependency parsing | Academia | int'l | academic | no | 0 | 5K (s) | - | ko |
| PT-6 | KMOU NER | NER | Academia | paper | academic | rd | 0 | 24K (s) | - | ko |
| PT-7 | AIR x NAVER NER | NER | Competition | docu | academic | no | 0 | 90K (s) | - | ko |
| PT-8 | AIR x NAVER SRL | SRL | Competition | docu | academic | no | 0 | 35K (s) | - | ko |
| PT-9 | KoNEC & KoNNEC | NER | Academia | docu | academic | no | 0 | 26K(s) | - | ko |


3. Entailment, sentence similarity, and paraphrase

| No | Dataset | Typical Usage | Provider | Docu. | License | Redist. | mod-x | Volume | Goal | Lang. |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| ESP-1 | Question Pair | Paraphrase detection | Academia | docu | all | rd | 0 | 10K (p) | - | ko |
| ESP-2 | KorNLI | NLI | Industry | int'l | all | rd | 0 | 1,000K (p) | - | ko |
| ESP-3 | KorSTS | STS | Industry | int'l | all | rd | 0 | 8,500K (p) | - | ko |
| ESP-4 | ParaKQC | Paraphrase detection | Academia | int'l | all | rd | 0 | 540K (p) | - | ko |
| ESP-5 | StyleKQC | Paraphrase detection | Academia | int'l | all | rd | 0 | 30K(s) | - | ko |
| ESP-6 | Korean Smile Style Dataset | Paraphrase detection | Industry | docu | academic | rd | 0 | 2,5K(d) | - | ko |


4. Intention understanding, sentiment analysis, and offensive language detection

| No | Dataset | Typical Usage | Provider | Docu. | License | Redist. | mod-x | Volume | Goal | Lang. |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| ISO-1 | 3i4K | Speech act classification | Academia | int'l | all | rd | 0 | 55K / 6K (s) | - | ko |
| ISO-2 | NSMC | Sentiment analysis | Academia | docu | all | rd | 0 | 150K / 50K (s) | - | ko |
| ISO-3 | Kocasm | Sentiment analysis | Academia | docu | all | rd | 0 | 9K (s) | - | ko |
| ISO-4 | BEEP! | Hate speech detection | Academia | int'l | all | rd | 0 | 8K / 0.5K / 1K (s) | - | ko |
| ISO-5 | APEACH | Hate speech detection | Academia | int'l | all | rd | 0 | 4K | Eval | ko |
| ISO-6 | Unsmile | Hate speech detection | Industry | docu | academic | rd | 0 | 19K | - | ko |
| ISO-7 | HateScore | Hate speech detection | Academia | int'l | academic | rd | 1 | 35K | - | ko |
| ISO-8 | KOLD | Hate speech detection | Academia | int'l | all | rd | 0 | 40K | - | ko |
| ISO-9 | K-MHaS | Hate speech detection | Academia | int'l | all | rd | 0 | 109K | - | ko |
| ISO-9 | KODOLI | Hate speech detection | Academia | int'l | all | rd | 0 | 38K | - | ko |
| ISO-10 | DKTC | Hate speech detection | Industry | docu | academic | rd | 0 | 1.5K | - | ko |


5. QA and dialogue

| No | Dataset | Typical Usage | Provider | Docu. | License | Redist. | mod-x | Volume | Goal | Lang. |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| QAD-1 | KorQuAD 1.0 | QA | Industry | int'l | all | rd | 1 | 60K / 5K / 4K (p) | - | ko |
| QAD-2 | KorQuAD 2.0 | QA | Industry | paper | all | rd | 1 | 80K / 10K / 10K (p) | - | ko |
| QAD-3 | HuLiC | Dialog | Industry | docu | academic | rd | 0 | 115K |  | ko |
| QAD-4 | OPELA | Dialog | Industry | int'l | academic | rd | 0 | 560K (d) |  | ko |
| QAD-5 | CareCall | Dialog | Industry | int'l | academic | rd | 0 | 10K | - | ko |


6. Summarization, Translation, and Transliteration

| No | Dataset | Typical Usage | Provider | Docu. | License | Redist. | mod-x | Volume | Goal | Lang. |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| STT-1 | Sci-news-sum-kr | Summarization | Academia | docu | academic | rd | 0 | 50K (p) | Eval | ko |
| STT-2 | sae4K | Summarization | Academia | int'l | all | rd | 0 | 50K (p) | - | ko |
| STT-3 | Korean Parallel Corpora | MT | Academia | int'l | all | rd | 1 | 100K (p) | - | ko, en |
| STT-4 | KAIST Translation Evaluation Set | MT | Academia | docu | academic | no | 0 | 3K (p) | Eval | ko, en |
| STT-5 | KAIST Chinese-Korean Multilingual Corpus | MT | Academia | docu | academic | no | 0 | 60K (p) | - | ko, zh |
| STT-6 | Transliteration Dataset | Transliteration | Academia | docu | all | rd | 0 | 35K (p) | - | ko, en |
| STT-7 | KAIST Transliteration Evaluation Set | Transliteration | Academia | docu | academic | no | 0 | 7K (p) | Eval | ko, en |


7. Korean in multilingual corpora

| No | Dataset | Typical Usage | Provider | Docu. | License | Redist. | mod-x | Volume | Goal | Lang. |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| KM-1 | SIGMORPHON G2P | G2P conversion | Competition | int'l | all | rd | 0 | 3.6K/ 0.45K / 0.45K (p) | - | ko, en, hy, bg, fr, ka, hi, hu, is, lt, el |
| KM-2 | PAWS-X | Paraphrase detection | Industry | int'l | all | rd | 0 | 5K / 2K / 2K (p) | - | ko, fr, es, de, zh, ja |
| KM-3 | TyDi-QA | QA | Industry | int'l | all | rd | 0 | 11K / 1,7K / 1,7K(p) | - | ko, en, ar, bn, fi, ja, id, sw, ru, te, th |
| KM-4 | XPersona | Dialog | Academia | int'l | all | rd | 0 | 0.3K(d) / 4.7K (s) | - | ko, en, it, fr, id, zh, ja |
| KM-5 | MultiCoNER | NER | Competition | int'l | all | rd | 0 | 178K / 2.6K (s) | - | ko, bn, de, en, es, fa, hi, nl, ru, tr, zh, multi, mix |
| KM-6 | Multilingual Tweet Intimacy Analysis | Sentiment analysis | Competition | int'l | unk | unk | 0 | 2K(instances) | - | ko, en, fr, es, it, pt, nl, zh, hi, ar |
| KM-7 | IWSLT 2023 | MT | Competition | int'l | all | rd | 0 | 3K (p) | - | ko, en, vi, pt, ru |


8. Speech corpora

| No | Dataset | Typical Usage | Provider | Docu. | License | Redist. | mod-x | Volume | Goal | Lang. |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| SL-1 | KSS | ASR | Academia | docu | academic | rd | 0 | 12+ (h) / 13K (u) / 1 speaker | - | ko |
| SL-1 | Zeroth | ASR | Industry | docu | all | rd | 0 | 51+ (h) / 27K (s) / 46K (u) / 181 speakers | - | ko |
| SL-3 | ClovaCall | ASR | Industry | int'l | academic | no | 0 | 80+ (h) / 60K (u) / 11K speakers | - | ko |
| SL-4 | Pansori-TedXKR | ASR | Academia | int'l | academic | rd | 1 | 3+ (h) / 3K (u) / 41 speakers | - | ko |
| SL-5 | ProSem | SLU | Academia | int'l | all | rd | 0 | 6+ (h) / 3,500 (s) / 7K (u) / 2 speakers | - | ko |
| SL-6 | kosp2e | Speech translation | Industry | int'l | academic | rd | 0 | 39K(u) | - | ko, en |
| SL-7 | jejueo (JSS & JIT) | Other topics | Industry | int'l | all | rd | 0 | 10K (JSS), 170K (JIT) | - | ko |


9. Other topics

| No | Dataset | Typical Usage | Provider | Docu. | License | Redist. | mod-x | Volume | Goal | Lang. |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| ETC-1 | KoCHET | Other topics | Academia | int'l | academic | rd | 0 | NER 112K, RE 39K, ET 113K | - | ko |
| ETC-2 | KommonGen | Other topics | Academia | docu | all | rd | 0 | 79K(s) | - | ko |
| ETC-3 | LBox Open | Other topics | Academia | int'l | academic | rd | 0 | 150K | - | ko |
| ETC-4 | K2NLG | Other topics | Academia | int'l | academic | rd | 0 | 4K(s) | - | ko |
| ETC-5 | Korean Ambiguity Data | Other topics | Academia | int'l | all | rd | 0 | 35K | - | ko |
| ETC-6 | Korean GEC dataset | Other topics | Academia | int'l | academic | rd | 0 | 155K(s pair) | - | ko |


### Citing

To cite our work, please use the following: (Also available as `cho-etal-2020-open` in anthology.bib)

    @inproceedings{cho-etal-2020-open,
        title = "Open {K}orean Corpora: A Practical Report",
        author = "Cho, Won Ik  and
          Moon, Sangwhan  and
          Song, Youngsook",
        booktitle = "Proceedings of Second Workshop for NLP Open Source Software (NLP-OSS)",
        month = nov,
        year = "2020",
        address = "Online",
        publisher = "Association for Computational Linguistics",
        url = "https://www.aclweb.org/anthology/2020.nlposs-1.12",
        pages = "85--93",
        abstract = "Korean is often referred to as a low-resource language in the research community. While this claim is partially true, it is also because the availability of resources is inadequately advertised and curated. This work curates and reviews a list of Korean corpora, first describing institution-level resource development, then further iterate through a list of current open datasets for different types of tasks. We then propose a direction on how open-source dataset construction and releases should be done for less-resourced languages to promote research.",
    }

### Contributing

Please read the [contributor guidelines](CONTRIBUTING.md) before sending a pull request.
