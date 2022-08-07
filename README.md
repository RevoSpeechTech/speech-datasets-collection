# Speech Datasets Collection
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/RevoSpeechTech/speech-datasets-collection/issues) [![HitCount](https://hits.dwyl.com/revospeech/speech-datasets-collection.svg?style=flat-square)](http://hits.dwyl.com/RevoSpeechTech/speech-datasets-collection)

> Contributions for more speech datasets are welcome!
> You can issue [here](https://github.com/RevoSpeechTech/speech-datasets-collection/issues) with new speech datasets, and the list of datasets in the **main** branch will be updated **weekly** (usually on weekends).


This is a curated list of open speech datasets for speech-related research (mainly for Automatic Speech Recognition).

Over **100** speech datasets are collected in this repository, and more than **70** datasets can be downloaded directly without further application or registration.

**Notice:**
1. This repository does not show corresponding License of each dataset. Basically it's OK to use these datasets for research purpose only. Please make sure the License is suitable before using for commercial purpose.
2. Some small-scale speech corpora are not shown here for concision.

---

### 1. Data Overview

| **Dataset Acquisition** | **Sup/Unsup** | **All Languages (Hours)** | **Mandarin (Hours)** | **English (Hours)** |
| :---: | :---: |:---: | :---: | :---: |
| download directly | supervised | 190k + | 2110 +  | 34k + |
| download directly | unsupervised | 515k + | 1360 + | 68k + |
| download directly | total | 705k + | 3470 + | 102k + |
| need application | supervised | 52k + | 16740 + | 50k + |
| need application | unsupervised | 60k + | 12400 + | 57k + |
| need application | total | 112k + | 29140 + | 107k + |
| total | supervised | 242k + | 18850 + | 84k + |
| total | unsupervised | 575k + | 13760 + | 125k + |
| total | total | 817k + | 32610 + | 209k + |

- **Mandarin** here includes Mandarin-English CS corpora.
- **Sup** means supervised speech corpus with high-quality transcription.
- **Unsup** means unsupervised or weakly-supervised speech corpus.


### 2. List of ASR corpora

#### a. datasets can be downloaded directly
| **Index** | **Name** | **Language** | **Type/Domain** | **Paper Link** | **Data Link** | **Size (Hours)** |
| :---: | :---: | :---: | :---: | :---: | :---: | :--- |
| 1 | Librispeech | English | Reading | [[paper]](https://www.danielpovey.com/files/2015_icassp_librispeech.pdf) | [[dataset]](https://www.openslr.org/12/) | 960 |
| 2 | TED_LIUM v1 | English | Talks | [[paper]](http://www.lrec-conf.org/proceedings/lrec2012/pdf/698_Paper.pdf) | [[dataset]](https://www.openslr.org/19/) | 118 |
| 3 | TED_LIUM v2 | English | Talks | [[paper]](http://www.lrec-conf.org/proceedings/lrec2014/pdf/1104_Paper.pdf) | [[dataset]](https://www.openslr.org/19) | 207 |
| 4 | TED_LIUM v3 | English | Talks | [[paper]](https://arxiv.org/pdf/1805.04699.pdf) | [[dataset]](https://www.openslr.org/51) | 452 |
| 5 | MLS | Multilingual | Reading | [[paper]](https://arxiv.org/pdf/2012.03411.pdf) | [[dataset]](https://www.openslr.org/94) | 50k + |
| 6 | thchs30 | Mandarin | Reading | [[paper]](https://arxiv.org/pdf/1512.01882.pdf) | [[dataset]](https://www.openslr.org/18/) | 35 |
| 7 | ST-CMDS | Mandarin | Commands | - | [[dataset]](https://www.openslr.org/38/) | 100 |
| 8 | aishell | Mandarin | Recording | [[paper]](https://arxiv.org/pdf/1709.05522.pdf) | [[dataset]](https://www.openslr.org/33/) | 178 |
| 9 | aishell-3 | Mandarin | Recording | [[paper]](https://arxiv.org/pdf/2010.11567.pdf) | [[dataset]](http://www.openslr.org/93/) | 85 |
| 10 | aishell-4 | Mandarin | Meeting | [[paper]](https://arxiv.org/pdf/2104.03603.pdf) | [[dataset]](http://www.openslr.org/111/) | 120 |
| 11 | aishell-eval | Mandarin | Misc | - | [[dataset]](https://aishelltech.com/aishell_2018_eval) | 80 + |
| 12 | Primewords | Mandarin | Recording | - | [[dataset]](https://www.openslr.org/47/) | 100 |
| 13 | aidatatang_200zh | Mandarin | Record | - | [[dataset]](https://www.openslr.org/62/) | 200 |
| 14 | MagicData | Mandarin | Recording | - | [[dataset]](https://www.openslr.org/68/) | 755 |
| 15 | MagicData-RAMC | Mandarin | Conversational | [[paper]](https://arxiv.org/pdf/2203.16844.pdf) | [[dataset]](https://openslr.org/123/) | 180 |
| 16 | Heavy Accent Corpus | Mandarin | Conversational | - | [[dataset]](https://magichub.com/datasets/mandarin-heavy-accent-conversational-speech-corpus/) | 58 + |
| 17 | AliMeeting | Mandarin | Meeting | [[paper]](https://arxiv.org/pdf/2202.03647.pdf) | [[dataset]](https://www.openslr.org/119/) | 120 |
| 18 | CN-Celeb | Mandarin | Misc | [[paper]](http://cnceleb.org/static/CN-Celeb_A_Challenging_Chinese_Speaker_Recognition_Dataset.pdf) | [[dataset]](https://www.openslr.org/82/) | unsup(274) |
| 19 | CN-Celeb2 | Mandarin | Misc | [[paper]](http://aishell-cnsrc.oss-cn-hangzhou.aliyuncs.com/CN-Celeb_Multi-Genre_Speaker_Recognition.pdf) | [[dataset]](https://www.openslr.org/82/) | unsup(1090) |
| 20 | The People's Speech | English | Misc | [[paper]](https://arxiv.org/pdf/2111.09344.pdf) | [[dataset]](https://mlcommons.org/en/peoples-speech/) | 30000 |
| 21 | Multilingual TEDx | Multilingual | Talks | [[paper]](https://arxiv.org/pdf/2102.01757.pdf) | [[dataset]](http://www.openslr.org/100) | 760 + |
| 22 | VoxPopuli | Multilingual | Misc | [[paper]](https://arxiv.org/pdf/2101.00390.pdf) | [[dataset]](https://github.com/facebookresearch/voxpopuli) | sup(1.8k)+unsup(400k)=400k + |
| 23 | Libri-Light | English | Reading | [[paper]](https://arxiv.org/pdf/1912.07875.pdf) | [[dataset]](https://github.com/facebookresearch/libri-light/tree/main/data_preparation) | unsup(60k) |
| 24 | Common Voice (Multilingual) | Multilingual | Recording | [[paper]](https://arxiv.org/pdf/1912.06670.pdf) | [[dataset]](https://commonvoice.mozilla.org/) | v9.0: sup(15k)+unsup(5k)=20k |
| 25 | Common Voice (English)| English | Recording | [[paper]](https://arxiv.org/pdf/1912.06670.pdf) | [[dataset]](https://commonvoice.mozilla.org/en/datasets) | v9.0: sup(2200)+unsup(700)=2900+ |
| 26 | JTubeSpeech | Japanese | Misc | [[paper]](https://arxiv.org/pdf/2112.09323.pdf) | [[dataset]](https://github.com/sarulab-speech/jtubespeech) | 1300 |
| 27 | ai4bharat NPTEL2020 | English(Indian) | Lectures | - | [[dataset]](https://github.com/AI4Bharat/NPTEL2020-Indian-English-Speech-Dataset) | weaksup(15.7k) |
| 28 | open_stt | Russian | Misc | - | [[dataset]](https://github.com/snakers4/open_stt) | 20k + |
| 29 | ASCEND | Mandarin-English CS | Conversational | [[paper]](https://arxiv.org/pdf/2112.06223.pdf) | [[dataset]](https://huggingface.co/datasets/CAiRE/ASCEND) | 10 + |
| 30 | Crowd-Sourced Speech | Multilingual | Recording | [[paper]](https://www.isca-speech.org/archive/pdfs/sltu_2018/kjartansson18_sltu.pdf) | [[dataset]](https://github.com/coqui-ai/open-speech-corpora/blob/150d316869c7ba468efd1f7b473555b0c76cc5e6/README.md?plain=1#L80) | 1200 + |
| 31 | Spoken Wikipedia | Multilingual | Recording | [[paper]](https://arne.chark.eu/static/spoken-wp-corpus-collection.pdf) | [[dataset]](https://corpora.uni-hamburg.de/hzsk/de/islandora/object/spoken-corpus:swc-2.0#additional-files) | 1000 + |
| 32 | MuST-C | Multilingual | Talks | [[paper]](https://aclanthology.org/N19-1202.pdf) | [[dataset]](https://ict.fbk.eu/must-c-release-v1-2/) | 6000 + |
| 33 | M-AILABS | Multilingual | Reading | - | [[dataset]](https://www.caito.de/2019/01/03/the-m-ailabs-speech-dataset/) | 1000 |
| 34 | CMU Wilderness | Multilingual | Misc | [[paper]](http://www.cs.cmu.edu/~awb/papers/2019_Black_ICASSP.pdf) | [[dataset]](https://github.com/festvox/datasets-CMU_Wilderness) | unsup(14k) |
| 35 | Gram_Vaani | Hindi | Recording | [[paper]](https://arxiv.org/pdf/2203.16973.pdf) [[code]](https://github.com/anish9208/gramvaani_hindi_asr) | [[dataset]](https://www.openslr.org/118/) | unsup(1000)+sup(100) |
| 36 | VoxLingua107 | Multilingual | Misc | [[paper]](https://arxiv.org/pdf/2011.12998.pdf) | [[dataset]](http://bark.phon.ioc.ee/voxlingua107/) | unsup(6600 +) |
| 37 | Kazakh Corpus | Kazakh | Recording | [[paper]](https://arxiv.org/pdf/2009.10334.pdf) [[code]](https://github.com/IS2AI/ISSAI_SAIDA_Kazakh_ASR) | [[dataset]](https://www.openslr.org/102/) | 335 |
| 38 | Voxforge | English | Recording | - | [[dataset]](http://www.voxforge.org/home/downloads) | 130 |
| 39 | Tatoeba | English | Recording | - | [[dataset]](https://downloads.tatoeba.org/audio/) | 200 |
| 40 | IndicWav2Vec | Multilingual | Misc | [[paper]](https://arxiv.org/pdf/2111.03945.pdf) | [[dataset]](https://github.com/AI4Bharat/IndicWav2Vec/tree/main/data_prep_scripts/pret_scripts) | unsup(17k +) |
| 41 | VoxCeleb | English | Misc | [[paper]](https://www.robots.ox.ac.uk/~vgg/publications/2017/Nagrani17/nagrani17.pdf) | [[dataset]](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/vox1.html) | unsup(352) |
| 42 | VoxCeleb2 | English | Misc | [[paper]](https://www.robots.ox.ac.uk/~vgg/publications/2018/Chung18a/chung18a.pdf) | [[dataset]](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/vox2.html) | unsup(2442) |
| 43 | RuLibrispeech | Russian | Read | - | [[dataset]](https://www.openslr.org/96/) | 98 |
| 44 | MediaSpeech | Multilingual | Misc | [[paper]](https://arxiv.org/pdf/2103.16193.pdf) | [[dataset]](https://www.openslr.org/108/) | 40 |
| 45 | MUCS 2021 task1 | Multilingual | Misc | - | [[dataset]](https://www.openslr.org/103/) | 300 |
| 46 | MUCS 2021 task2 | Multilingual | Misc | - | [[dataset]](https://www.openslr.org/104/) | 150 |
| 47 | nicolingua-west-african | Multilingual | Misc | [[paper]](https://arxiv.org/pdf/2104.13083.pdf) | [[dataset]](https://www.openslr.org/105/) | 140 + |
| 48 | Samromur 21.05 | Samromur | Misc | [[code]](https://github.com/cadia-lvl/samromur-asr) | [[dataset]](https://www.openslr.org/112/) [[dataset]](https://www.openslr.org/116/)[[dataset]](https://www.openslr.org/117) | 145 |
| 49 | Puebla-Nahuatl | Puebla-Nahuatl | Misc | [[paper]](https://aclanthology.org/2021.americasnlp-1.7.pdf) | [[dataset]](https://www.openslr.org/92/) | 150 + |
| 50 | Golos | Russian | Misc | [[paper]](https://arxiv.org/pdf/2106.10161.pdf) | [[dataset]](https://www.openslr.org/114/) | 1240 |
| 51 | ParlaSpeech-HR | Croatian | Parliament | [[paper]](https://office.clarin.eu/v/CE-2021-1923-CLARIN2021_ConferenceProceedings.pdf) | [[dataset]](https://www.clarin.si/repository/xmlui/handle/11356/1494) | 1816 |
| 52 | Lyon Corpus | French | Recording | [[paper]](https://www.mq.edu.au/__data/assets/pdf_file/0006/910077/2008Demuth-and-Tremblay.pdf) | [[dataset]](https://phonbank.talkbank.org/access/French/Lyon.html) | 185 |
| 53 | Providence Corpus | English | Recording | [[paper]](https://d1wqtxts1xzle7.cloudfront.net/66484402/2006DemuthetalL_S-libre.pdf?1619046276=&response-content-disposition=inline%3B+filename%3DWord_minimality_Epenthesis_and_Coda_Lice.pdf&Expires=1652977685&Signature=d3EpWElGBNwVe6wvbA-Erk9bhbykEtwwSJN3JRcLRPU4dSB2iHz8FOjsYKf9YQVLQVHtNF-5L7EF325B7jWfaBXewazatJ9f-uC2qqQO~JPhD9GQgfTXims4pfu7cm1irdRT7fgYeqAbTT6xM9LMB0LdyMsevxB6tCJCX3IZwUdUaYsmNgm9iROxn7MZnr74gmQTekpRNK0AJFjpR261oYR5ORf8sgnpdVmjlbhlOTVraj12huOIvxEoIZ~QoFwA1mFSrLArBj83gdNVPvHpBFNoup4Dsejq1MbDOogFkoh~fW3C21xnjpM5PvUuq7SeT~gDgZQ~aZo14IS474pMtw__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA) | [[dataset]](https://phonbank.talkbank.org/access/Eng-NA/Providence.html) | 364 |
| 54 | CLARIN Spoken Corpora | Czech | Recording | - | [[dataset]](https://www.clarin.eu/resource-families/spoken-corpora) | 1120 + |
| 55 | Czech Parliament Plenary | Czech | Recording | - | [[dataset]](https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-3126) | 444 |
| 56 | (Youtube) Regional American Corpus | English (Accented) | Misc | [[paper]](http://cc.oulu.fi/~scoats/YouTube_Corpus_19a.pdf) | [[dataset]](https://github.com/stcoats/YouTube_Corpus) | 29k + |
| 57 | NISP Dataset | Multilingual | Recording | [[paper]](https://arxiv.org/pdf/2007.06021.pdf) | [[dataset]](https://github.com/iiscleap/NISP-Dataset?utm_source=catalyzex.com) | 56 + |
| 58 | Regional African American | English (Accented) | Recording | [[paper]](http://lingtools.uoregon.edu/coraal/userguide/CORAALUserGuide_current.pdf) | [[dataset]](http://lingtools.uoregon.edu/coraal/) | 130 + |
| 59 | Indonesian Unsup | Indonesian | Misc | - | [[dataset]](https://github.com/Wikidepia/indonesian_datasets/tree/master/speech/unsupervised) | unsup (3000+) |
| 60 | Librivox-Spanish | Spanish | Recording | - | [[dataset]](https://www.kaggle.com/datasets/carlfm01/120h-spanish-speech) | 120 |
| 61 | AVSpeech | English | Audio-Visual | [[paper]](https://arxiv.org/pdf/1804.03619.pdf) | [[dataset]](https://looking-to-listen.github.io/avspeech/download.html) | unsup(4700) |
| 62 | CMLR | Mandarin | Audio-Visual | [[paper]](https://arxiv.org/pdf/1908.04917.pdf) | [[dataset]](https://www.vipazoo.cn/CMLR.html) | 100 + |
| 63 | Speech Accent Archive | English | Accented | [[paper]](https://brill.com/view/book/edcoll/9789401206884/B9789401206884-s014.xml) | [[dataset]](http://accent.gmu.edu/browse_language.php) | TBC |
| 64 | BibleTTS | Multilingual | TTS | [[paper]](https://arxiv.org/pdf/2203.14456.pdf) | [[dataset]](https://masakhane-io.github.io/bibleTTS/) | 86 |
| 65 | NST-Norwegian | Norwegian | Recording | - | [[dataset]](https://www.nb.no/sprakbanken/en/resource-catalogue/oai-nb-no-sbr-54/) | 540 |
| 66 | NST-Danish | Danish | Recording | - | [[dataset]](https://www.nb.no/sprakbanken/en/resource-catalogue/oai-nb-no-sbr-55/) | 500 + |
| 67 | NST-Swedish | Swedish | Recording | - | [[dataset]](https://www.nb.no/sprakbanken/en/resource-catalogue/oai-nb-no-sbr-56/) | 300 + |
| 68 | NPSC | Norwegian | Parliament | [[paper]](http://www.lrec-conf.org/proceedings/lrec2022/pdf/2022.lrec-1.106.pdf) | [[dataset]](https://www.nb.no/sprakbanken/en/resource-catalogue/oai-nb-no-sbr-58/) | 140 |
| 69 | CI-AVSR | Cantonese | Audio-Visual | [[paper]](https://arxiv.org/pdf/2201.03804.pdf) | [[dataset]](https://github.com/HLTCHKUST/CI-AVSR) | 8 + |
| 70 | Aalto Finnish Parliament | Finnish | Parliament | [[paper]](https://arxiv.org/pdf/2203.14876.pdf) | [[dataset]](https://www.kielipankki.fi/corpora/fi-parliament-asr/) | 3100 + |
| 71 | UserLibri | English | Reading | [[paper]](https://arxiv.org/pdf/2207.00706.pdf) | [[dataset]](https://www.kaggle.com/datasets/google/userlibri) | - |
| 72 | Ukrainian Speech | Ukrainian | Misc | - | [[dataset]](https://github.com/egorsmkv/speech-recognition-uk#-datasets) | 1300+ |


#### b. datasets can be downloaded after application

| **Index** | **Name** | **Language** | **Type/Domain** | **Paper Link** | **Data Link** | **Size (Hours)** |
| :---: | :---: | :---: | :---: | :---: | :---: | :--- |
| 1 | Fisher | English | Conversational | [[paper]](http://www.lrec-conf.org/proceedings/lrec2004/pdf/767.pdf) | [[dataset]](https://catalog.ldc.upenn.edu/search) | 2000 |
| 2 | WenetSpeech | Mandarin | Misc | [[paper]](https://arxiv.org/pdf/2110.03370.pdf) | [[dataset]](https://www.openslr.org/121) | sup(10k)+weaksup(2.4k)+unsup(10k)=22.4k |
| 3 | aishell-2 | Mandarin | Recording | [[paper]](https://arxiv.org/pdf/1808.10583.pdf) | [[dataset]](https://www.aishelltech.com/aishell_2) | 1000 |
| 4 | aidatatang_1505zh | Mandarin | Recording | - | [[dataset]](https://www.datatang.com/opensource) | 1505 |
| 5 | SLT 2021 CSRC | Mandarin | Misc | [[paper]](https://arxiv.org/pdf/2011.06724.pdf) | [[dataset]](https://www.data-baker.com/csrc_challenge.html) | 400 |
| 6 | GigaSpeech | English | Misc | [[paper]](https://arxiv.org/pdf/2106.06909.pdf) | [[dataset]](https://github.com/SpeechColab/GigaSpeech) | sup(10k)+unsup(23k)=33k |
| 7 | SPGISpeech | English | Misc | [[paper]](https://arxiv.org/pdf/2104.02014.pdf) | [[dataset]](https://datasets.kensho.com/datasets/spgispeech) | 5000 |
| 8 | AESRC 2020 | English (accented) | Misc | [[paper]](https://arxiv.org/pdf/2102.10233.pdf) | [[dataset]](https://www.datatang.com/INTERSPEECH2020) | 160 |
| 9 | LaboroTVSpeech | Japanese | Misc | [[paper]](https://arxiv.org/pdf/2103.14736.pdf) | [[dataset]](https://laboro.ai/activity/column/engineer/eg-laboro-tv-corpus-jp/) | 2000 + |
| 10 | TAL_CSASR | Mandarin-English CS | Lectures | - | [[dataset]](https://ai.100tal.com/dataset) | 587 |
| 11 | ASRU 2019 ASR | Mandarin-English CS | Reading | - | [[dataset]](https://www.datatang.com/competition) | 700 + |
| 12 | SEAME | Mandarin-English CS | Recording | [[paper]](https://www.isca-speech.org/archive/pdfs/interspeech_2010/lyu10_interspeech.pdf) | [[dataset]](https://catalog.ldc.upenn.edu/LDC2015S04) | 196 |
| 13 | Fearless Steps | English | Misc | - | [[dataset]](https://fearless-steps.github.io/ChallengePhase3/#19k_Corpus_Access) | unsup(19k) |
| 14 | FTSpeech | Danish | Meeting | [[paper]](https://arxiv.org/pdf/2005.12368.pdf) | [[dataset]](https://ftspeech.github.io/) | 1800 + |
| 15 | KeSpeech | Mandarin | Recording | [[paper]](https://openreview.net/pdf?id=b3Zoeq2sCLq) | [[dataset]](https://github.com/KeSpeech/KeSpeech) | 1542 |
| 16 | KsponSpeech | Korean | Conversational | [[paper]](https://www.mdpi.com/2076-3417/10/19/6936) | [[dataset]](https://huggingface.co/datasets/cheulyop/ksponspeech) | 969 |
| 17 | RVTE database | Spanish | TV | [[paper]](https://catedrartve.unizar.es/reto2022/RTVE2022DB.pdf) | [[dataset]](https://catedrartve.unizar.es/rtvedatabase.html) | 800 + |
| 18 | DiDiSpeech | Mandarin | Recording | [[paper]](https://arxiv.org/pdf/2010.09275.pdf) | [[dataset]](https://github.com/athena-team/DiDiSpeech) | 800 |
| 19 | Babel | Multilingual | Telephone | [[paper]](https://eprints.whiterose.ac.uk/152840/8/Gales%20et%20al%202014.pdf) | [[dataset]](https://www.nist.gov/itl/iad/mig/openkws16-evaluation) | 1000 + |
| 20 | National Speech Corpus | English (Singapore) | Misc | [[paper]](https://www.isca-speech.org/archive_v0/Interspeech_2019/pdfs/1525.pdf) | [[dataset]](https://www.imda.gov.sg/programme-listing/digital-services-lab/national-speech-corpus) | 3000 + |
| 21 | MyST Children's Speech | English | Recording | - | [[dataset]](http://boulderlearning.com/request-the-myst-corpus/) | 393 |
| 22 | L2-ARCTIC | L2 English | Recording | [[paper]](https://www.isca-speech.org/archive_v0/Interspeech_2018/pdfs/1110.pdf) | [[dataset]](https://psi.engr.tamu.edu/l2-arctic-corpus/) | 20 + |
| 23 | JSpeech | Multilingual | Recording | [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8639658) | [[dataset]](https://github.com/miras-tech/jspeech) | 1332 + |
| 24 | LRS2-BBC | English | Audio-Visual | [[paper]](https://arxiv.org/pdf/1809.02108.pdf) | [[dataset]](https://www.robots.ox.ac.uk/~vgg/data/lip_reading/lrs2.html) | 220 + |
| 25 | LRS3-TED | English | Audio-Visual | [[paper]](https://arxiv.org/pdf/1809.00496.pdf) | [[dataset]](https://www.robots.ox.ac.uk/~vgg/data/lip_reading/lrs3.html) | 470 + |
| 26 | LRS3-Lang | Multilingual | Audio-Visual | - | [[dataset]](https://www.robots.ox.ac.uk/~vgg/data/lip_reading/lrs3-lang.html) | 1300 + |
| 27 | QASR | Arabic | Dialects | [[paper]](https://arxiv.org/pdf/2106.13000.pdf) | [[dataset]](https://arabicspeech.org/qasr/) | 2000 + |
| 28 | ADI (MGB-5) | Arabic | Dialects | [[paper]](https://swshon.github.io/pdf/ali_asru2019_mgb5.pdf) | [[dataset]](https://arabicspeech.org/mgb5/#adi17) | unsup (3000 +) |
| 29 | MGB-2 | Arabic | TV | [[paper]](https://arxiv.org/pdf/1609.05625.pdf) | [[dataset]](http://www.mgb-challenge.org/MGB-2.html) | 1200 + |
| 30 | 3MASSIV | Multilingual | Audio-Visual | [[paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Gupta_3MASSIV_Multilingual_Multimodal_and_Multi-Aspect_Dataset_of_Social_Media_Short_CVPR_2022_paper.pdf) | [[dataset]](https://github.com/ShareChatAI/3MASSIV) | sup(310)+unsup(600) |
| 31 | MDCC | Cantonese | Misc | [[paper]](https://arxiv.org/pdf/2201.02419.pdf) | [[dataset]](https://github.com/HLTCHKUST/cantonese-asr) | 73 + |
| 32 | Lahjoita Puhetta | Finnish | Misc | [[paper]](https://arxiv.org/pdf/2203.12906.pdf) | [[dataset]](https://github.com/aalto-speech/lahjoita-puhetta-resources) | sup(1600) + unsup(2000) |
| 33 | SDS-200 | Swiss German | Dialects | [[paper]](https://arxiv.org/pdf/2205.09501.pdf) | [[dataset]](https://swissnlp.org/datasets/) | 200 |
| 34 | Modality Corpus | Misc | Audio-Visual | [[paper]](https://link.springer.com/content/pdf/10.1007/s10844-016-0438-z.pdf) | [[dataset]](http://www.modality-corpus.org/) | 30 + |


### 3. References

- [https://github.com/coqui-ai/open-speech-corpora](https://github.com/coqui-ai/open-speech-corpora)
- [https://openslr.org/resources.php](https://openslr.org/resources.php)