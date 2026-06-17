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
- **int'l** - Does the corpus have an internationally available article or document, including a paper, blog post, GitHub README, or technical report?
- **dom.** - Does the corpus have only domestic documentation available?
- **none** - Does the corpus lack an official description?

#### License
For *License*, we check the followings:
- Commercially available (**all**), academic use only (**academic**), unknown (**unk**)
- Redistribution is available with/without modification (**rd**), unavailable (**none**), unknown (**unk**)

#### Other Attributes
- In *Typical Usage*, we note the area of intended use of the dataset.
- In *Providers*, we note if the dataset is provided by universities or institutes (Academia), companies or the research group thereof (Industry), or something combined, as Competition purpose.
- In *Volume*, (w) denotes words, (s) denotes sentences, (p) denotes pairs (either document or sentence pairs), (d) denotes dialogues, (h) denotes hours, and (u) denotes speech utterances.
- In *Goal*, Eval is noted if the purpose is suggested as an evaluation.
- In *Lang*, we note all the languages that the dataset handles.

#### View at a Glance
The table below describes the open Korean corpora investigated so far.
This is the Jun. 2026 version (third edition) reflected in our updated survey manuscript.
You can visit [Here](https://github.com/songys/AwesomeKorean_Data) for related dataset notes and more information regarding government-driven databases.
We removed the hyperlink for pages not working.


1. *Benchmark studies*

| No | Dataset | Typical Usage | Provider | Docu. | License | Redist. | mod-x | Volume | Goal | Lang. | Year |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BM-1 | [KLUE](https://klue-benchmark.com/) | Benchmark studies | Industry | int'l | all | rd | 0 | DP - 15K (s), DST - 10K (d), MRC - 29K (p), NER - 31K (s), NLI - 31K (p), RE - 48K (s), STS - 12K (p), TC - 63K (s) | Eval | ko | 2021 |
| BM-2 | [KoBEST](https://huggingface.co/datasets/skt/kobest_v1) | Benchmark studies | Industry | int'l | all | rd | 0 | BoolQ - 5.8K (p), COPA - 4.6K, KB-WiC - 5.2K (p), KB-HellaSwag - 3K, SentiNeg - 4.8K | Eval | ko | 2022 |
| BM-3 | [Ko-H5/Open-Ko-LLM](https://huggingface.co/spaces/upstage/open-ko-llm-leaderboard) | LLM benchmark | Industry | int'l | all | rd | 0 | Ko-ARC, Ko-HellaSwag, Ko-MMLU, Ko-TruthfulQA, Ko-CommonGen v2; Season 2 tasks | Eval | ko | 2024 |
| BM-4 | [HAE-RAE Bench](https://huggingface.co/datasets/HAERAE-HUB/HAE_RAE_BENCH_1.1) | LLM benchmark | Academia | int'l | all | rd | 0 | 1.5K questions, 6 tasks | Eval | ko | 2024 |
| BM-5 | [KMMLU](https://huggingface.co/datasets/HAERAE-HUB/KMMLU) | LLM benchmark | Academia | int'l | all | rd | 0 | 35K MCQs, 45 subjects | Eval | ko | 2024 |
| BM-6 | [KULTURE Bench](https://github.com/wangxiaonan-git/KULTUREBench) | Cultural benchmark | Academia | int'l | academic | unk | 0 | - | Eval | ko | 2024 |
| BM-7 | [KMMLU-Redux](https://huggingface.co/datasets/LGAI-EXAONE/KMMLU-Redux) / [KMMLU-Pro](https://huggingface.co/datasets/LGAI-EXAONE/KMMLU-Pro) | LLM benchmark | Industry | int'l | all | rd | 1 | 2.6K / 2.8K problems | Eval | ko | 2025 |
| BM-8 | [KoBALT](https://huggingface.co/datasets/snunlp/KoBALT-700) | Linguistic benchmark | Academia | int'l | academic | rd | 1 | 700 MCQs | Eval | ko | 2025 |


2. *Parsing and tagging*

| No | Dataset | Typical Usage | Provider | Docu. | License | Redist. | mod-x | Volume | Goal | Lang. | Year |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| PT-1 | [UD Korean KAIST](https://github.com/emorynlp/ud-korean) | Dependency parsing | Academia | int'l | academic | none | 0 | 27K (s) | - | ko | 2018 |
| PT-2 | [PKT-UD](https://github.com/emorynlp/ud-korean) | Dependency parsing | Academia | int'l | academic | none | 0 | 5K (s) | - | ko | 2018 |
| PT-3 | [AIR x NAVER NER/SRL](https://github.com/naver/nlp-challenge) | NER, SRL | Competition | dom. | academic | none | 0 | NER - 90K (s), SRL - 35K (s) | - | ko | 2018 |
| PT-4 | [KMOU NER](https://github.com/kmounlp/NER) | NER | Academia | dom. | academic | rd | 0 | 24K (s) | - | ko | 2019 |
| PT-5 | [OpenKorPOS](https://github.com/openkorpos) | POS tagging | Academia | int'l | all | rd | 0 | 55M (w) | - | ko | 2022 |
| PT-6 | [KoNEC & KoNNEC](https://github.com/korean-named-entity/konne) | NER | Academia | dom. | all | rd | 0 | 26K (s) | - | ko | 2022 |


3. *Entailment, sentence similarity, and paraphrase*

| No | Dataset | Typical Usage | Provider | Docu. | License | Redist. | mod-x | Volume | Goal | Lang. | Year |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| ESP-1 | [Question Pair](https://github.com/songys/Question_pair) | Paraphrase detection | Academia | dom. | all | rd | 0 | 10K (p) | - | ko | 2018 |
| ESP-2 | Korean PPDB | Paraphrase database | Academia | int'l | unk | unk | 0 | - | - | ko, ja | 2019 |
| ESP-3 | [KorNLI/KorSTS](https://github.com/kakaobrain/KorNLUDatasets) | NLI, STS | Industry | int'l | all | rd | 0 | KorNLI - 940K train (p), KorSTS - 5.7K train (p) | - | ko | 2020 |
| ESP-4 | [ParaKQC](https://github.com/warnikchow/ParaKQC) | Paraphrase detection | Academia | int'l | all | rd | 0 | 540K (p) | - | ko | 2020 |
| ESP-5 | [StyleKQC](https://github.com/cynthia/stylekqc) | Style transfer, paraphrase detection | Academia | int'l | all | rd | 0 | 30K (s) | - | ko | 2022 |
| ESP-6 | [Korean Smile Style Dataset](https://github.com/smilegate-ai/korean_smile_style_dataset) | Style transfer | Industry | dom. | academic | rd | 0 | 2.5K (d) | - | ko | 2022 |
| ESP-7 | [KoSEnd](https://github.com/seungukyu/KoSEnd) | Linguistic evaluation | Academia | int'l | academic | unk | 0 | - | Eval | ko | 2025 |


4. *Intention understanding and sentiment analysis*

| No | Dataset | Typical Usage | Provider | Docu. | License | Redist. | mod-x | Volume | Goal | Lang. | Year |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| IS-1 | [NSMC](https://github.com/e9t/nsmc) | Sentiment analysis | Academia | int'l | all | rd | 0 | 200K (s) | - | ko | 2015 |
| IS-2 | [3i4K](https://github.com/warnikchow/3i4k) | Speech act classification | Academia | int'l | all | rd | 0 | 61K (s) | - | ko | 2018 |
| IS-3 | [Kocasm](https://github.com/SpellOnYou/korean-sarcasm) | Sarcasm detection | Academia | dom. | all | rd | 0 | 9K (s) | - | ko | 2019 |
| IS-4 | [KMRE](https://github.com/passing2961/KMRE) | Emotion classification | Academia | int'l | all | rd | 0 | - | - | ko | 2020 |
| IS-5 | [ToM-Diary](https://github.com/humanfactorspsych/covid19-tom-empathy-diary) | Theory of mind analysis | Academia | dom. | academic | rd | 1 | 18K diaries, 74K (s) | - | ko | 2021 |
| IS-6 | [KEmoFact](https://www.nature.com/articles/s41598-023-45992-8) | Emotion factor extraction | Academia | int'l | unk | unk | 0 | - | - | ko | 2023 |
| IS-7 | [KPC-cF](https://anonymous.4open.science/r/KPC-cF-21E8) | Aspect-based sentiment classification | Academia | int'l | academic | rd | 0 | Kor-SemEval, KR3 | - | ko | 2024 |
| IS-8 | [KoCoSa](https://github.com/Yu-billie/KoCoSa_sarcasm_detection) | Sarcasm detection | Academia | int'l | all | rd | 0 | 12.8K (d) | - | ko | 2024 |
| IS-9 | [KOTE](https://github.com/searle-j/KOTE) | Emotion classification | Academia | int'l | academic | rd | 1 | 50K comments, 250K annotations | - | ko | 2024 |
| IS-10 | [CARBD-Ko](https://arxiv.org/abs/2402.15046) | Aspect-based sentiment classification | Academia | int'l | academic | unk | 0 | - | Eval | ko | 2024 |
| IS-11 | [KPoEM](https://github.com/AKS-DHLAB/KPoEM) | Emotion detection | Academia | int'l | all | rd | 0 | - | - | ko | 2025 |


5. *Offensive language detection, fairness and bias*

| No | Dataset | Typical Usage | Provider | Docu. | License | Redist. | mod-x | Volume | Goal | Lang. | Year |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| OFB-1 | [BEEP!](https://github.com/kocohub/korean-hate-speech) | Hate speech detection | Academia | int'l | all | rd | 0 | 9.4K (s) | - | ko | 2020 |
| OFB-2 | [APEACH](https://github.com/jason9693/APEACH) | Hate speech detection | Academia | int'l | all | rd | 0 | 4K (s) | Eval | ko | 2022 |
| OFB-3 | [Korean Unsmile Dataset](https://github.com/smilegate-ai/korean_unsmile_dataset) | Hate speech detection | Industry | dom. | academic | rd | 1 | 19K (s) | - | ko | 2022 |
| OFB-4 | [HateScore](https://github.com/sgunderscore/hatescore-korean-hate-speech) | Hate speech detection | Academia | int'l | academic | rd | 0 | 35K (s) | - | ko | 2022 |
| OFB-5 | [KOLD](https://github.com/boychaboy/KOLD) | Offensive language detection | Academia | int'l | all | rd | 0 | 40K (s) | - | ko | 2022 |
| OFB-6 | [K-MHaS](https://github.com/adlnlp/K-MHaS) | Hate speech detection | Academia | int'l | all | rd | 0 | 109K (s) | - | ko | 2022 |
| OFB-7 | [DKTC](https://github.com/tunib-ai/DKTC) | Threatening conversation detection | Industry | dom. | academic | rd | 0 | 4.5K (d) | - | ko | 2022 |
| OFB-8 | [KODOLI](https://github.com/cardy20/KODOLI) | Offensive language detection | Academia | int'l | all | rd | 0 | 38K (s) | - | ko | 2023 |
| OFB-9 | [KoMultiText](https://github.com/Dasol-Choi/KoMultiText) | Bias and profanity detection | Academia | int'l | all | rd | 0 | 150K comments | - | ko | 2023 |
| OFB-10 | [K-HATERS](https://github.com/ssu-humane/K-HATERS) | Offensive language detection | Academia | int'l | all | rd | 0 | 192K comments | - | ko | 2023 |
| OFB-11 | [KoSBi](https://github.com/naver-ai/korean-safety-benchmarks) | Social bias detection | Industry | int'l | all | rd | 0 | 34K (p) | - | ko | 2023 |
| OFB-12 | [SQuARe](https://github.com/naver-ai/korean-safety-benchmarks) | Safe response generation | Industry | int'l | all | rd | 0 | 49K questions, 88K responses | - | ko | 2023 |
| OFB-13 | [KoBBQ](https://github.com/naver-ai/KoBBQ) | Bias benchmark | Industry | int'l | all | rd | 0 | 76K samples | Eval | ko | 2024 |
| OFB-14 | [KCDD](https://sites.google.com/view/kcdd) | Violence classification | Academia | int'l | academic | none | 0 | 22K (d) | - | ko | 2024 |
| OFB-15 | [LifeTox](https://huggingface.co/datasets/mbkim/LifeTox) | Implicit toxicity detection | Academia | int'l | academic | unk | 0 | - | - | ko | 2024 |


6. *QA and dialogue*

| No | Dataset | Typical Usage | Provider | Docu. | License | Redist. | mod-x | Volume | Goal | Lang. | Year |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| QAD-1 | [KorQuAD 1.0, 2.0](https://korquad.github.io/) | QA | Industry | int'l | all | rd | 1 | 70K / 100K questions | Eval | ko | 2019 |
| QAD-2 | [KorWikiTQ](https://github.com/LG-NLP/KorWikiTableQuestions) | Table QA | Industry | int'l | all | rd | 0 | - | - | ko | 2022 |
| QAD-3 | [HuLiC](https://github.com/smilegate-ai/HuLiC) | Dialog | Industry | dom. | academic | rd | 0 | 115K turns | - | ko | 2022 |
| QAD-4 | [OPELA](https://github.com/smilegate-ai/OPELA) | Dialog | Industry | int'l | academic | rd | 0 | 600 (d) | - | ko | 2022 |
| QAD-5 | [CareCall](https://github.com/naver-ai/carecall-corpus) | Dialog | Industry | int'l | academic | rd | 0 | 10K (d) | - | ko | 2022 |
| QAD-6 | [CLIcK](https://github.com/rladmstn1714/CLIcK) | Cultural QA | Academia | int'l | all | rd | 0 | 2K QA pairs | Eval | ko | 2024 |
| QAD-7 | [KoDialogBench](https://github.com/sb-jang/kodialogbench) | Dialogue benchmark | Academia | int'l | all | rd | 0 | 83K examples | Eval | ko | 2024 |
| QAD-8 | [KorNAT](https://huggingface.co/datasets/datumo/KorNAT) | Social value QA | Industry | int'l | academic | rd | 0 | 10K questions | Eval | ko | 2024 |
| QAD-9 | [K-MMBench](https://huggingface.co/datasets/NCSOFT/K-MMBench) | Vision-language QA | Industry | int'l | academic | rd | 1 | 4.3K questions | Eval | ko | 2024 |
| QAD-10 | [K-Viscuit](https://github.com/ddehun/k-viscuit) | VQA | Academia | int'l | academic | unk | 0 | - | Eval | ko | 2025 |
| QAD-11 | [KoSimpleQA](https://huggingface.co/datasets/bzantium/KoSimpleQA) | Factual QA | Academia | int'l | academic | unk | 0 | 1K questions | Eval | ko | 2025 |
| QAD-12 | [KoPIQA](https://huggingface.co/datasets/HAERAE-HUB/Ko-PIQA) | Physical commonsense QA | Academia | int'l | academic | unk | 0 | 441 QA pairs | Eval | ko | 2025 |


7. *Summarization, Translation, and Transliteration*

| No | Dataset | Typical Usage | Provider | Docu. | License | Redist. | mod-x | Volume | Goal | Lang. | Year |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| STT-1 | [Sci-news-sum-kr](https://github.com/theeluwin/sci-news-sum-kr-50) | Summarization | Academia | dom. | academic | rd | 0 | 50 (p) | Eval | ko | 2016 |
| STT-2 | [Korean Parallel Corpora](https://github.com/jungyeul/korean-parallel-corpora) | MT | Academia | int'l | academic | rd | 1 | 100K (p) | - | ko, en | 2016 |
| STT-3 | [Transliteration Dataset](https://github.com/muik/transliteration) | Transliteration | Academia | dom. | all | rd | 0 | 35K (p) | - | ko, en | 2016 |
| STT-4 | [sae4K](https://github.com/warnikchow/sae4k) | Summarization | Academia | int'l | all | rd | 0 | 50K (p) | - | ko | 2019 |
| STT-5 | [OPUS-MT ko-en](https://huggingface.co/Helsinki-NLP/opus-mt-ko-en) | MT | Academia | int'l | all | rd | 0 | Tatoeba Challenge test sets | - | ko, en | 2020 |
| STT-6 | [Naver News Summary](https://huggingface.co/datasets/daekeun-ml/naver-news-summarization-ko) | Summarization | Academia | none | all | rd | 0 | - | - | ko | 2022 |
| STT-7 | [KoreaScience Summary](https://huggingface.co/datasets/nglaura/koreascience-summarization) | Summarization | Academia | int'l | all | rd | 0 | - | - | ko | 2023 |
| STT-8 | [SSL](https://github.com/SSL-Sign-Language/Korean-Disaster-Safety-Information-Sign-Language-Translation-Benchmark-Dataset) | Sign language translation | Academia | int'l | all | unk | 0 | - | Eval | ko | 2024 |
| STT-9 | [KPC](https://github.com/HandongSF/KoreanUnificationParallelCorpus) | MT | Academia | int'l | academic | rd | 1 | 131K (p) | - | ko | 2024 |
| STT-10 | [KNOTICED](https://github.com/sugyeonge/KNOTICED) | MT error detection | Academia | int'l | academic | unk | 0 | - | Eval | ko, en | 2024 |


8. *Korean in multilingual corpora*

| No | Dataset | Typical Usage | Provider | Docu. | License | Redist. | mod-x | Volume | Goal | Lang. | Year |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| KM-1 | [PAWS-X](https://github.com/google-research-datasets/paws/tree/master/pawsx) | Paraphrase detection | Industry | int'l | all | rd | 0 | 5K / 2K / 2K (p) | - | ko, fr, es, de, zh, ja | 2019 |
| KM-2 | [SIGMORPHON G2P](https://sigmorphon.github.io/sharedtasks/2020/task1/) | G2P conversion | Competition | int'l | all | rd | 0 | 3.6K / 0.45K / 0.45K (p) | - | ko, en, hy, bg, fr, ka, hi, hu, is, lt, el | 2020 |
| KM-3 | [TyDi-QA](https://github.com/google-research-datasets/tydiqa) | QA | Industry | int'l | all | rd | 0 | 11K / 1.7K / 1.7K (p) | - | ko, en, ar, bn, fi, ja, id, sw, ru, te, th | 2020 |
| KM-4 | [XPersona](https://github.com/HLTCHKUST/Xpersona) | Dialog | Academia | int'l | all | rd | 0 | 0.3K (d) / 4.7K (s) | - | ko, en, it, fr, id, zh, ja | 2020 |
| KM-5 | [XL-Sum](https://github.com/csebuetnlp/xl-sum) | Summarization | Academia | int'l | all | rd | 0 | - | - | ko, multi | 2021 |
| KM-6 | [MultiCoNER](https://registry.opendata.aws/multiconer/) | NER | Competition | int'l | all | rd | 0 | 178K / 2.6K (s) | - | ko, multi | 2022 |
| KM-7 | [MINT](https://sites.google.com/umich.edu/semeval-2023-tweet-intimacy/home) | Sentiment analysis | Competition | int'l | unk | unk | 0 | 2K train/test, 0.5K zero-shot | - | ko, en, fr, es, it, pt, nl, zh, hi, ar | 2022 |
| KM-8 | [MASSIVE](https://github.com/alexa/massive) | NLU | Industry | int'l | all | rd | 0 | 1M examples | - | ko, multi | 2023 |
| KM-9 | [IWSLT 2023](https://iwslt.org/2023/formality) | MT | Competition | int'l | all | rd | 0 | 3K (p) | - | ko, en, vi, pt, ru | 2023 |


9. *Speech corpora*

| No | Dataset | Typical Usage | Provider | Docu. | License | Redist. | mod-x | Volume | Goal | Lang. | Year |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| SL-1 | [KSS](https://www.kaggle.com/bryanpark/korean-single-speaker-speech-dataset) | ASR, TTS | Academia | int'l | academic | rd | 0 | 12K (u), 1 speaker | - | ko | 2018 |
| SL-2 | [Zeroth](https://github.com/goodatlas/zeroth) | ASR | Industry | int'l | all | rd | 0 | 50+ (h) | - | ko | 2018 |
| SL-3 | [Pansori-TEDxKR](https://github.com/yc9701/pansori-tedxkr-corpus) | ASR | Academia | int'l | academic | rd | 1 | 3+ (h) | - | ko | 2018 |
| SL-4 | [ProSem](https://github.com/warnikchow/prosem) | SLU | Academia | int'l | all | rd | 0 | 7.1K (u), 2 speakers | - | ko | 2019 |
| SL-5 | [ClovaCall](https://github.com/clovaai/ClovaCall) | ASR | Industry | int'l | academic | none | 0 | 80+ (h) | - | ko | 2020 |
| SL-6 | [JIT/JSS](https://github.com/kakaobrain/jejueo) | ASR, TTS | Industry | int'l | all | rd | 0 | 10K (JSS), 170K (JIT) | - | ko | 2020 |
| SL-7 | [kosp2e](https://github.com/warnikchow/kosp2e) | Speech translation | Academia | int'l | academic | rd | 0 | 30K (u) | - | ko, en | 2021 |
| SL-8 | [OLKAVS](https://arxiv.org/abs/2301.06375) | Audio-visual speech recognition | Academia | int'l | all | rd | 0 | 1,150 (h) audio, 5,750 (h) video | - | ko | 2024 |
| SL-9 | [KMSAV](https://onlinelibrary.wiley.com/doi/10.4218/etrij.2022-0487) | Audio-visual speech recognition | Academia | int'l | academic | rd | 1 | 150 (h) transcribed, 2,000+ (h) untranscribed | - | ko | 2024 |


10. *Other topics*

| No | Dataset | Typical Usage | Provider | Docu. | License | Redist. | mod-x | Volume | Goal | Lang. | Year |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| ETC-1 | [K2NLG](https://github.com/machinereading/K2NLG-Dataset) | Data-to-text generation | Academia | dom. | academic | rd | 0 | 4K (s) | - | ko | 2020 |
| ETC-2 | [KommonGen](https://github.com/nlpai-lab/KommonGen) | Common sense generation | Academia | int'l | all | rd | 0 | 43K train, 2K test | - | ko | 2021 |
| ETC-3 | [KoCHET](https://github.com/Gyeongmin47/KoCHET-A-Korean-Cultural-Heritage-corpus-for-Entity-related-Tasks) | Cultural heritage entity tasks | Academia | int'l | academic | unk | 0 | NER 112K, RE 39K, ET 113K | - | ko | 2022 |
| ETC-4 | [LBox Open](https://github.com/lbox-kr/lbox-open) | Legal language understanding | Academia | int'l | academic | rd | 0 | 150K precedents | - | ko | 2022 |
| ETC-5 | [Korean GEC dataset](https://github.com/soyoung97/standard_korean_gec) | GEC | Academia | int'l | academic | rd | 0 | 155K (s pair) | - | ko | 2022 |
| ETC-6 | [Korean Ambiguity Dataset](https://github.com/bareun-nlp/korean-ambiguity-data) | Word sense disambiguation | Academia | int'l | all | rd | 0 | 35K (s), 8.2K surface forms | - | ko | 2023 |
| ETC-7 | [KorMedMCQA](https://huggingface.co/datasets/sean0042/KorMedMCQA) | Medical QA | Academia | int'l | academic | rd | 1 | 7.5K questions | Eval | ko | 2024 |
| ETC-8 | [KBMC](https://arxiv.org/abs/2403.16158) | Medical NER | Academia | int'l | academic | unk | 0 | - | - | ko | 2024 |
| ETC-9 | [ESG-Kor](https://aclanthology.org/2024.findings-emnlp.387/) | ESG information extraction | Academia | int'l | academic | rd | 0 | 119K (s) | - | ko | 2024 |
| ETC-10 | [KBL](https://github.com/lbox-kr/kbl) | Legal language understanding | Academia | int'l | academic | rd | 0 | 3.3K exam examples, 150K precedents | Eval | ko | 2024 |
| ETC-11 | [FunctionChat-Bench](https://github.com/kakao/FunctionChat-Bench) | Function calling benchmark | Industry | int'l | all | rd | 0 | - | Eval | ko | 2024 |
| ETC-12 | [KCL](https://github.com/lbox-kr/kcl) | Legal reasoning | Academia | int'l | academic | rd | 1 | 283 MCQA, 169 essay questions | Eval | ko | 2025 |
| ETC-13 | [KorMedLawQA](https://huggingface.co/datasets/snuh/KorMedLawQA) | Medical law QA | Academia | int'l | academic | rd | 0 | - | Eval | ko | 2025 |

### Citation

To cite our work, please use the following. Use the ACL Anthology version, or the [arXiv version](https://arxiv.org/abs/2012.15621) (v3, revised in Jun. 2026, reflecting this third edition).

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

    @article{cho2026open,
        title = "Open {K}orean Corpora: A Practical Report",
        author = "Cho, Won Ik and Moon, Sangwhan and Song, Youngsook",
        journal = "arXiv preprint arXiv:2012.15621",
        year = "2026",
        note = "v3, revised 9 Jun. 2026",
        url = "https://arxiv.org/abs/2012.15621",
    }

### Contributing

Please read the [contributor guidelines](CONTRIBUTING.md) before sending a pull request.
