## Open Korean Corpora: A Living Document for Korean NLP Dataset Curation



![image](./image.png)

### Overview
- Korean, a language with 80M users is often overlooked in NLP research
- The availability of public datasets and tasks has hindered investigation
- Even the publicly available datasets are not always accompanied by English documentation and have poor discoverability
- Our work attempts to tackle this problem by curating a living document of open resources for the Korean language

### PACLIC 2023

We will participate in [PACLIC 37](https://paclic2023.github.io/) and will present our paper "**Revisiting Korean Corpus Studies through  Technological Advances**". If you visit PolyU@HK 3 December, please drop by!

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
- **docu** - Does the corpus have any documentation on the usage?
- **paper** - Does the corpus have a related article?
- **int'l** - Does the corpus have a internationally available publication?

#### License
For *License*, we check the followings:
- Commercially available (**all**), academic use only (**academic**), unknown (**unk**)
- Redistribution is available with/without modification (rd/no for **rd** and binary for **mod-x**), unknown (**unk**)

#### Other Attributes
- In *Typical Usage*, we note the area of intended use of the dataset.
- In *Providers*, we note if the dataset is provided by universities or institutes (Academia), companies or the research group thereof (Industry), or something combined, as Competition purpose.
- In *Volume*, (w) denotes words, (s) denotes sentences, (p) denotes pairs (either document or sentence pairs), (d) denotes dialogues, (h) denotes hours, and (u) denotes speech utterances.
- In *Goal*, Eval is noted if the purpose is suggested as an evaluation.
- In *Lang*, we note all the languages that the dataset handles.

#### View at a Glance
The table below describes the open Korean corpora investigated so far. To be updated along with our survey or PR. You can visit [Here](https://github.com/songys/AwesomeKorean_Data) for the Korean description, and more information regarding government-driven database. We removed the hyperlink for pages not working.


1. *Benchmark studies*

| No | Dataset | Typical Usage | Provider | Docu. | License | Redist. | mod-x | Volume | Goal | Lang. | Year |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BM-1 | [KLUE](https://klue-benchmark.com/) | Benchmark studies | Industry | int'l | all | rd | 0 | DP - 15K (s), DST - 10K (d), MRC - 29K (p), NER - 31K (s), NLI - 30K (p), RE - 48K (s), STS - 13K (p), TC - 64K (s)   | Eval | ko | 2021 |
| BM-2 | [KoBEST](https://huggingface.co/datasets/skt/kobest_v1) | Benchmark studies | Industry | int'l | all | rd | 0 | BoolQ - 6K (p), COPA - 5K (s), KB-WiC - 6K (s), KB-HellaSwag - 3K (p & s), SentiNeg - 4K (s) | Eval | ko | 2022 |


2. *Parsing and tagging*

| No | Dataset | Typical Usage | Provider | Docu. | License | Redist. | mod-x | Volume | Goal | Lang. | Year |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| PT-1 | KAIST Morpho-Syntactically Annotated Corpus | Morphological analysis | Academia | paper | academic | no | 0 | 70M (w) | - | ko | 1999 |
| PT-2 | [OpenKorPOS](https://github.com/openkorpos/openkorpos) | Morphological analysis | Academia | int'l | all | rd | 0 | 55M (w) | - | ko | 2022 |
| PT-3 | KAIST Korean Tree-Tagging Corpus | Tree parsing | Academia | int'l | academic | no | 0 | 30K (s) | - | ko | 1994 |
| PT-4 | [UD Korean KAIST](https://github.com/emorynlp/ud-korean) | Dependency parsing | Academia | int'l | academic | no | 1 | 27K (s) | - | ko | 2018 |
| PT-5 | [PKT-UD](https://github.com/emorynlp/ud-korean) | Dependency parsing | Academia | int'l | academic | no | 0 | 5K (s) | - | ko | 2018 |
| PT-6 | [KMOU NER](https://github.com/kmounlp/NER) | NER | Academia | paper | academic | rd | 0 | 24K (s) | - | ko | 2019 |
| PT-7 | [AIR x NAVER NER](http://air.changwon.ac.kr/?page_id=10) | NER | Competition | docu | academic | no | 0 | 90K (s) | - | ko | 2018 |
| PT-8 | [AIR x NAVER SRL](http://air.changwon.ac.kr/?page_id=14) | SRL | Competition | docu | academic | no | 0 | 35K (s) | - | ko | 2018 |
| PT-9 | [KoNEC & KoNNEC](https://github.com/korean-named-entity/konne) | NER | Academia | docu | academic | no | 0 | 26K(s) | - | ko | 2022 |


3. *Entailment, sentence similarity, and paraphrase*

| No | Dataset | Typical Usage | Provider | Docu. | License | Redist. | mod-x | Volume | Goal | Lang. | Year |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| ESP-1 | [Question Pair](https://github.com/songys/Question_pair) | Paraphrase detection | Academia | docu | all | rd | 0 | 10K (p) | - | ko | 2018 |
| ESP-2 | [KorNLI](https://github.com/kakaobrain/KorNLUDatasets) | NLI | Industry | int'l | all | rd | 0 | 1,000K (p) | - | ko | 2020 |
| ESP-3 | [KorSTS](https://github.com/kakaobrain/KorNLUDatasets) | STS | Industry | int'l | all | rd | 0 | 8,500K (p) | - | ko | 2020 |
| ESP-4 | [ParaKQC](https://github.com/warnikchow/ParaKQC) | Paraphrase detection | Academia | int'l | all | rd | 0 | 540K (p) | - | ko | 2020 |
| ESP-5 | [StyleKQC](https://github.com/cynthia/stylekqc) | Paraphrase detection | Academia | int'l | all | rd | 0 | 30K(s) | - | ko | 2021 |
| ESP-6 | [Korean Smile Style Dataset](https://github.com/smilegate-ai/korean_smile_style_dataset) | Paraphrase detection | Industry | docu | academic | rd | 0 | 2,5K(d) | - | ko | 2022 |


4. *Intention understanding, sentiment analysis, and offensive language detection*

| No | Dataset | Typical Usage | Provider | Docu. | License | Redist. | mod-x | Volume | Goal | Lang. | Year |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| ISO-1 | [3i4K](https://github.com/warnikchow/3i4k) | Speech act classification | Academia | int'l | all | rd | 0 | 55K / 6K (s) | - | ko | 2019 |
| ISO-2 | [NSMC](https://github.com/e9t/nsmc) | Sentiment analysis | Academia | docu | all | rd | 0 | 150K / 50K (s) | - | ko | 2015 |
| ISO-3 | [Kocasm](https://github.com/SpellOnYou/korean-sarcasm) | Sentiment analysis | Academia | docu | all | rd | 0 | 9K (s) | - | ko | 2019 |
| ISO-4 | [BEEP!](https://github.com/kocohub/korean-hate-speech) | Hate speech detection | Academia | int'l | all | rd | 0 | 8K / 0.5K / 1K (s) | - | ko | 2020 |
| ISO-5 | [APEACH](https://github.com/jason9693/APEACH) | Hate speech detection | Academia | int'l | all | rd | 0 | 4K | Eval | ko | 2022 |
| ISO-6 | [Unsmile](https://github.com/smilegate-ai/korean_unsmile_dataset) | Hate speech detection | Industry | docu | academic | rd | 0 | 19K | - | ko | 2022 |
| ISO-7 | [HateScore](https://github.com/sgunderscore/hatescore-korean-hate-speech) | Hate speech detection | Academia | int'l | academic | rd | 1 | 35K | - | ko | 2022 |
| ISO-8 | [KOLD](https://github.com/boychaboy/kold) | Hate speech detection | Academia | int'l | all | rd | 0 | 40K | - | ko | 2022 |
| ISO-9 | [K-MHaS](https://github.com/adlnlp/K-MHaS) | Hate speech detection | Academia | int'l | all | rd | 0 | 109K | - | ko | 2022 |
| ISO-10 | [KODOLI](https://github.com/cardy20/KODOLI) | Hate speech detection | Academia | int'l | all | rd | 0 | 38K | - | ko | 2023 |
| ISO-11 | [DKTC](https://github.com/tunib-ai/DKTC) | Hate speech detection | Industry | docu | academic | rd | 0 | 1.5K | - | ko | 2022 |


5. *QA and dialogue*

| No | Dataset | Typical Usage | Provider | Docu. | License | Redist. | mod-x | Volume | Goal | Lang. | Year |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| QAD-1 | [KorQuAD 1.0](https://korquad.github.io/) | QA | Industry | int'l | all | rd | 1 | 60K / 5K / 4K (p) | - | ko | 2018 |
| QAD-2 | [KorQuAD 2.0](https://korquad.github.io/)    | QA | Industry | paper | all | rd | 1 | 80K / 10K / 10K (p) | - | ko | 2019 |
| QAD-3 | [HuLiC](https://github.com/smilegate-ai/HuLiC) | Dialog | Industry | docu | academic | rd | 0 | 115K | - | ko | 2022 |
| QAD-4 | [OPELA](https://github.com/smilegate-ai/OPELA) | Dialog | Industry | int'l | academic | rd | 0 | 560K (d) | - | ko | 2022 |
| QAD-5 | [CareCall](https://github.com/naver-ai/carecall-corpus/tree/main) | Dialog | Industry | int'l | academic | rd | 0 | 10K | - | ko | 2022 |


6. *Summarization, Translation, and Transliteration*

| No | Dataset | Typical Usage | Provider | Docu. | License | Redist. | mod-x | Volume | Goal | Lang. | Year |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| STT-1 | [Sci-news-sum-kr](https://github.com/theeluwin/sci-news-sum-kr-50) | Summarization | Academia | docu | academic | rd | 0 | 50K (p) | Eval | ko | 2016 |
| STT-2 | [sae4K](https://github.com/warnikchow/sae4k) | Summarization | Academia | int'l | all | rd | 0 | 50K (p) | - | ko | 2020 |
| STT-3 | [Korean Parallel Corpora](https://github.com/jungyeul/korean-parallel-corpora) | MT | Academia | int'l | all | rd | 1 | 100K (p) | - | ko, en | 2016 |
| STT-4 | KAIST Translation Evaluation Set | MT | Academia | docu | academic | no | 0 | 3K (p) | Eval | ko, en | 2000 |
| STT-5 | KAIST Chinese-Korean Multilingual Corpus | MT | Academia | docu | academic | no | 0 | 60K (p) | - | ko, zh | 2000 |
| STT-6 | [Transliteration Dataset](https://github.com/muik/transliteration) | Transliteration | Academia | docu | all | rd | 0 | 35K (p) | - | ko, en | 2016 |
| STT-7 | KAIST Transliteration Evaluation Set | Transliteration | Academia | docu | academic | no | 0 | 7K (p) | Eval | ko, en | 2000 |


7. *Korean in multilingual corpora*

| No | Dataset | Typical Usage | Provider | Docu. | License | Redist. | mod-x | Volume | Goal | Lang. | Year |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| KM-1 | [SIGMORPHON G2P](https://sigmorphon.github.io/sharedtasks/2020/task1/) | G2P conversion | Competition | int'l | all | rd | 0 | 3.6K/ 0.45K / 0.45K (p) | - | ko, en, hy, bg, fr, ka, hi, hu, is, lt, el | 2020 |
| KM-2 | [PAWS-X](https://github.com/google-research-datasets/paws/tree/master/pawsx) | Paraphrase detection | Industry | int'l | all | rd | 0 | 5K / 2K / 2K (p) | - | ko, fr, es, de, zh, ja | 2019 |
| KM-3 | [TyDi-QA](https://github.com/google-research-datasets/tydiqa) | QA | Industry | int'l | all | rd | 0 | 11K / 1,7K / 1,7K (p) | - | ko, en, ar, bn, fi, ja, id, sw, ru, te, th | 2020 |
| KM-4 | [XPersona](https://github.com/HLTCHKUST/Xpersona) | Dialog | Academia | int'l | all | rd | 0 | 0.3K(d) / 4.7K (s) | - | ko, en, it, fr, id, zh, ja | 2020 |
| KM-5 | [MultiCoNER](https://multiconer.github.io/multiconer_1/dataset) | NER | Competition | int'l | all | rd | 0 | 178K / 2.6K (s) | - | ko, bn, de, en, es, fa, hi, nl, ru, tr, zh, multi, mix | 2022 |
| KM-6 | [Multilingual Tweet Intimacy Analysis](https://codalab.lisn.upsaclay.fr/competitions/7096#participate) | Sentiment analysis | Competition | int'l | unk | unk | 0 | 2K (instances) | - | ko, en, fr, es, it, pt, nl, zh, hi, ar | 2022 |
| KM-7 | [IWSLT 2023](https://iwslt.org/2023/formality) | MT | Competition | int'l | all | rd | 0 | 3K (p) | - | ko, en, vi, pt, ru | 2023 |


8. *Speech corpora*

| No | Dataset | Typical Usage | Provider | Docu. | License | Redist. | mod-x | Volume | Goal | Lang. | Year |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| SL-1 | [KSS](https://github.com/Kyubyong/kss) | ASR | Academia | docu | academic | rd | 0 | 12+ (h) / 13K (u) / 1 speaker | - | ko | 2018 |
| SL-2 | [Zeroth](https://github.com/goodatlas/zeroth) | ASR | Industry | docu | all | rd | 0 | 51+ (h) / 27K (s) / 46K (u) / 181 speakers | - | ko | 2017 |
| SL-3 | [ClovaCall](https://github.com/clovaai/ClovaCall) | ASR | Industry | int'l | academic | no | 0 | 80+ (h) / 60K (u) / 11K speakers | - | ko | 2020 |
| SL-4 | [Pansori-TedXKR](https://github.com/yc9701/pansori-tedxkr-corpus) | ASR | Academia | int'l | academic | rd | 1 | 3+ (h) / 3K (u) / 41 speakers | - | ko | 2018 |
| SL-5 | [ProSem](https://github.com/warnikchow/prosem) | SLU | Academia | int'l | all | rd | 0 | 6+ (h) / 3,500 (s) / 7K (u) / 2 speakers | - | ko | 2019 |
| SL-6 | [kosp2e](https://github.com/warnikchow/kosp2e) | Speech translation | Industry | int'l | academic | rd | 0 | 39K(u) | - | ko, en | 2021 |
| SL-7 | [jejueo (JSS](https://arxiv.org/pdf/1911.12071.pdf) & JIT) | Other topics | Industry | int'l | all | rd | 0 | 10K (JSS), 170K (JIT) | - | ko | 2020 |


9. *Other topics*

| No | Dataset | Typical Usage | Provider | Docu. | License | Redist. | mod-x | Volume | Goal | Lang. | Year |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| ETC-1 | [KoCHET](https://github.com/Gyeongmin47/KoCHET-A-Korean-Cultural-Heritage-corpus-for-Entity-related-Tasks) | Other topics | Academia | int'l | academic | rd | 0 | NER 112K, RE 39K, ET 113K | - | ko | 2022 |
| ETC-2 | [KommonGen](https://github.com/nlpai-lab) | Other topics | Academia | docu | all | rd | 0 | 79K(s) | - | ko | 2021 |
| ETC-3 | [LBox Open](https://github.com/lbox-kr/lbox-open) | Other topics | Academia | int'l | academic | rd | 0 | 150K | - | ko | 2022 |
| ETC-4 | [K2NLG](https://github.com/machinereading/K2NLG) | Other topics | Academia | int'l | academic | rd | 0 | 4K(s) | - | ko | 2020 |
| ETC-5 | [Korean Ambiguity Data](https://github.com/bareun-nlp/korean-ambiguity-data) | Other topics | Academia | int'l | all | rd | 0 | 35K | - | ko | 2023 |
| ETC-6 | [Korean GEC dataset](https://github.com/soyoung97/Standard_Korean_GEC) | Other topics | Academia | int'l | academic | rd | 0 | 155K(s pair) | - | ko | 2022 |

### Citation

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
