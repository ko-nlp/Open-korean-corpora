## Open Korean Corpora: A Living Document for Korean NLP Dataset Curation

### Overview
- Korean, a language with 80M users is often overlooked in NLP research
- The availability of public datasets and tasks has hindered investigation
- Even the publicly available datasets are not always accompanied by English documentation and have poor discoverability
- Our work attempts to tackle this problem by curating a living document of open resources for the Korean language

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


|No.|Dataset|Typical Usage|Provider|Docu.|License|Volume|Goal|Lang.|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|1|[KAIST Morpho-Syntactically Annotated Corpus](http://semanticweb.kaist.ac.kr/home/index.php/KAIST_Corpus)|Morphological analysis|Academia|art|acad/no|70M (w)| - |ko|
|2|[KAIST Korean Tree-Tagging Corpus](http://semanticweb.kaist.ac.kr/home/index.php/KAIST_Corpus)|Tree parsing|Academia|inter|acad/no|30K (s)|-|ko|
|3|[UD Korean KAIST](https://github.com/emorynlp/ud-korean)|Dependency parsing|Academia|inter|acad/no|27K (s)|-|ko|
|4|[PKT-UD](https://github.com/emorynlp/ud-korean)|Dependency parsing |Academia|inter|acad/no|5K (s)|-|ko|
|5|[KMOU NER](https://github.com/kmounlp/NER)| NER| Academia|art|acad/rd|24K (s)|-|ko|
|6|[AIR x NAVER NER](http://air.changwon.ac.kr/?page_id=10)| NER |Competition|doc|acad/no|90K (s)|-|ko|
|7|[AIR x NAVER SLR](http://air.changwon.ac.kr/?page_id=14)|SLR|Competition|doc|acad/no|35K (s)|-|ko|
|8|[Question Pair](https://github.com/songys/Question_pair)| Paraphrase detection|Academia|doc|com/rd|10K (p)|-|ko|
|9|[KorNLI](https://github.com/kakaobrain/KorNLUDatasets)|NLI|Industry|inter|com/rd |1,000K (p)|-|ko|
|10|[KorSTS](https://github.com/kakaobrain/KorNLUDatasets)|STS|Industry|inter|com/rd|8,500 (p)|-|ko |
|11|[ParaKQC](https://github.com/warnikchow/ParaKQC)|STS|Academia|inter|com/rd|540K (p)|-|ko|
|12|[NSMC](https://github.com/e9t/nsmc)|Sentiment analysis|Academia|doc|com/rd|150K / 50K (s)|-|ko|
|13|[BEEP!](https://github.com/kocohub/korean-hate-speech)|Hate speech detection|Academia|inter|com/rd |8K / 500 / 1,000 (s)|-|ko|
|14|[3i4K](https://github.com/warnikchow/3i4k)|Speech act classification |Academia |inter|com/rd |55K / 6K (s)|-|ko|
|15|[KorQuAD 1.0](https://korquad.github.io/)|QA|Industry|inter|com/rd (mod-x)|60K / 5K / 4K (p)|-|ko|
|16|[KorQuAD 2.0](https://korquad.github.io/)|QA|Industry|art|com/red (mod-x)|80K / 10K / 10K (p)|-|ko|
|17|[Sci-news-sum-kr](https://github.com/theeluwin/sci-news-sum-kr-50)|Summarization|Academia|doc|acad/rd|50 (p)|Eval|ko|
|18|[sae4K](https://github.com/warnikchow/sae4k)|Summarization|Academia|inter|com/rd|50K (p)|-|ko|Structured argument extraction for Korean|
|19|[Korean Parallel Corpora](https://github.com/jungyeul/korean-parallel-corpora)|MT|Academia|inter|com/red(mod-x)|97K (p)|-|ko, en|-|
|20|[KAIST Translation Evaluation Set](http://semanticweb.kaist.ac.kr/home/index.php/Evaluateset2) |MT| Academia|doc|acad/no|3K (p)|Eval|ko, en|
|21|[KAIST Chinese-Korean Multilingual Corpus](http://semanticweb.kaist.ac.kr/home/index.php/Corpus9) |MT |Academia|doc|acad/no|60K (p)|-|ko, zh|
|22|[Transliteration Dataset](https://github.com/muik/transliteration)|Transliteration|Academia |doc|com/rd |35K (p)|-| ko, en|
|23|[KAIST Transliteration Evaluation Set](http://semanticweb.kaist.ac.kr/home/index.php/Evaluateset3)|Transliteration|Academia|doc|acad/no|7K (p)|Eval|ko, en|
|24|[SIGMORPHON G2P](https://sigmorphon.github.io/sharedtasks/2020/task1/) |G2P conversion|Competition |doc|com/rd |3,600 / 450 / 450 (p) |-|ko, en, hy, bg, fr, ka, hi, hu, is, lt, el|
|25|[PAWS-X](https://github.com/google-research-datasets/paws/tree/master/pawsx) | Paraphrase detection |Industry|inter|com/rd |5K / 2K / 2K (p)|-|ko, fr, es, de, zh, ja|-|
|26|[TyDi-QA](https://github.com/google-research-datasets/tydiqa)|QA|Industry|inter|com/rd |11K / 1,698 / 1,722 (p)|-|ko, en, ar, bn, fi, ja, id, sw, ru, te, th|
|27|[XPersona](https://github.com/HLTCHKUST/Xpersona) |Dialog |Academia |INT [Doc](https://arxiv.org/abs/2003.07568) |com/rd |299 (d) / 4,684 (s)|- |ko, en, it, fr, id, zh, ja|
|28|[KSS](https://github.com/Kyubyong/kss) |ASR|Academia|doc|acad/rd|12+ (h) / 13K (u) / 1 speaker |-|ko |
|29|[Zeroth](https://github.com/goodatlas/zeroth) |ASR|Industry|doc|com/rd|51+ (h) / 27K (s) / 46K (u) / 181 speakers|-|ko|
|30|[ClovaCall](https://github.com/clovaai/ClovaCall)|ASR|Industry|inter|acad/no|80+ (h) / 60K (u)/ 11K speakers|-|ko|
|31|[Pansori-TedXKR](https://github.com/yc9701/pansori-tedxkr-corpus)|ASR|Academia|inter|acad/rd / (mod-x)|3+ (h) / 3K (u)/ 41 speakers|-|ko|
|32|[ProSem](https://github.com/warnikchow/prosem)|SLU|Academia|inter|com/rd|6+ (h) / 3,500 (s) / 7K (u) / 2 speakers|-|ko|

