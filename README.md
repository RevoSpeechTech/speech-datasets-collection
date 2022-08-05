## Speech Datasets Collection

This is a curated list of open speech datasets for speech-related research (mainly for Automatic Speech Recognition).

Over **100** speech datasets are collected in this repository, and over **70** datasets can be downloaded directly without further application of registration.

**!Notice!:** this repository does not offer corresponding License of each dataset. Basically it's OK to use these datasets for research purpose only. Please make sure the License is suitable before using for commercial purpose.

### Data Overview

| **dataset acquisition** | **sup/unsup** | **All languages (hours)** | **Mandarin (hours)** | **English (hours)** |
| --- | --- | --- | --- | --- |
| download directly | supervised | 190k + | 2110+  | 34k + |
|  | unsupervised | 515k + | 1360 + | 68k + |
|  | total | 705k + | 3470 + | 102k + |
| need application | supervised | 52k + | 16740 + | 50k + |
|  | unsupervised | 60k + | 12400 + | 57k + |
|  | total | 112k + | 29140 + | 107k + |
| total | supervised | 242k + | 18850 + | 84k + |
|  | unsupervised | 575k + | 13760 + | 125k + |
|  | total | 817k + | 32610 + | 209k + |

- **Mandarin** here includes Mandarin-English CS corpora.


### References

- [https://github.com/coqui-ai/open-speech-corpora](https://github.com/coqui-ai/open-speech-corpora)
- [https://openslr.org/resources.php](https://openslr.org/resources.php)


### List of ASR corpora
| **index** | **Name** | **Language** | **Type** | **Paper Link** | **Data Link** | **Direct Download** | **Size (Hours)** |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Librispeech | English | Read | [[paper]](https://www.danielpovey.com/files/2015_icassp_librispeech.pdf) | [[dataset]](https://www.openslr.org/12/) | Y | 960 |
| 2 | TED_LIUM v1 | English | Talk | [[paper]](http://www.lrec-conf.org/proceedings/lrec2012/pdf/698_Paper.pdf) | [[dataset]](https://www.openslr.org/19/) | Y | 118 |
| 3 | TED_LIUM v2 | English | Talk | [[paper]](http://www.lrec-conf.org/proceedings/lrec2014/pdf/1104_Paper.pdf) | [[dataset]](https://www.openslr.org/19) | Y | 207 |
| 4 | TED_LIUM v3 | English | Talk | [[paper]](https://arxiv.org/pdf/1805.04699.pdf) | [[dataset]](https://www.openslr.org/51) | Y | 452 |
| 5 | MLS | Multilingual | Read | [[paper]](https://arxiv.org/pdf/2012.03411.pdf) | [[dataset]](https://www.openslr.org/94) | Y | 50k + |
| 6 | thchs30 | Mandarin | Record | [[paper]](https://arxiv.org/pdf/1512.01882.pdf) | [[dataset]](https://www.openslr.org/18/) | Y | 35 |
| 7 | ST-CMDS | Mandarin | Record | - | [[dataset]](https://www.openslr.org/38/) | Y | 100 |
| 8 | aishell | Mandarin | Record | [[paper]](https://arxiv.org/pdf/1709.05522.pdf) | [[dataset]](https://www.openslr.org/33/) | Y | 178 |
| 9 | aishell-3 | Mandarin | Record | [[paper]](https://arxiv.org/pdf/2010.11567.pdf) | [[dataset]](http://www.openslr.org/93/) | Y | 85 |
| 10 | aishell-4 | Mandarin | Conference | [[paper]](https://arxiv.org/pdf/2104.03603.pdf) | [[dataset]](http://www.openslr.org/111/) | Y | 120 |
| 11 | aishell-eval | Mandarin | Misc | - | [[dataset]](https://www.aishelltech.com/aishell_eval) | Y | 80 + |
| 12 | Primewords | Mandarin | Record | - | [[dataset]](https://www.openslr.org/47/) | Y | 100 |
| 13 | aidatatang_200zh | Mandarin | Record | - | [[dataset]](https://www.openslr.org/62/) | Y | 200 |
| 14 | MagicData | Mandarin | Record | - | [[dataset]](https://www.openslr.org/68/) | Y | 755 |
| 15 | MagicData-RAMC | Mandarin | Record | [[paper]](https://arxiv.org/pdf/2203.16844.pdf) | [[dataset]](https://arxiv.org/pdf/2203.16844.pdf) | Y | 180 |
| 16 | Heavy Accent Corpus | Mandarin | Conversational | - | [[dataset]](https://magichub.com/datasets/mandarin-heavy-accent-conversational-speech-corpus/) | Y | 58 + |
| 17 | AliMeeting | Mandarin | Meeting | [[paper]](https://arxiv.org/pdf/2202.03647.pdf) | [[dataset]](https://www.openslr.org/119/) | Y | 120 |
| 18 | CN-Celeb | Mandarin | Misc | [[paper]](http://cnceleb.org/static/CN-Celeb_A_Challenging_Chinese_Speaker_Recognition_Dataset.pdf) | [[dataset]](https://www.openslr.org/82/) | Y | unsup(274) |
| 19 | CN-Celeb2 | Mandarin | Misc | [[paper]](http://aishell-cnsrc.oss-cn-hangzhou.aliyuncs.com/CN-Celeb_Multi-Genre_Speaker_Recognition.pdf) | [[dataset]](https://www.openslr.org/82/) | Y | unsup(1090) |
| 20 | The People's Speech | English | Misc | [[paper]](https://arxiv.org/pdf/2111.09344.pdf) | [[dataset]](https://mlcommons.org/en/peoples-speech/) | Y | 30000 |
| 21 | Multilingual TEDx | Multilingual | Talk | [[paper]](https://arxiv.org/pdf/2102.01757.pdf) | [[dataset]](http://www.openslr.org/100) | Y | 760 + |
| 22 | VoxPopuli | Multilingual | Meeting | [[paper]](https://arxiv.org/pdf/2101.00390.pdf) | [[dataset]](https://github.com/facebookresearch/voxpopuli) | Y | sup(17.3k)+unsup(384k)=400k + |
| 23 | Libri-Light | English | Read | [[paper]](https://arxiv.org/pdf/1912.07875.pdf) | [[dataset]](https://github.com/facebookresearch/libri-light/tree/main/data_preparation) | Y | unsup(60k) |
| 24 | Common Voice | Multilingual | Record | [[paper]](https://arxiv.org/pdf/1912.06670.pdf) | [[dataset]](https://commonvoice.mozilla.org/) | Y | v9.0: sup(15k)+unsup(5k)=20k |
| 25 | Common Voice | English | Record | [[paper]](https://arxiv.org/pdf/1912.06670.pdf) | [[dataset]](https://commonvoice.mozilla.org/en/datasets) | Y | v9.0: sup(2200)+unsup(700)=2900+ |
| 26 | JTubeSpeech | Japanese | Misc | [[paper]](https://arxiv.org/pdf/2112.09323.pdf) | [[dataset]](https://github.com/sarulab-speech/jtubespeech) | Y | 1300 |
| 27 | ai4bharat NPTEL2020 | English(Indian) | Lecture | - | [[dataset]](https://github.com/AI4Bharat/NPTEL2020-Indian-English-Speech-Dataset) | Y | weaksup(15.7k) |
| 28 | open_stt | Russian | Misc | - | [[dataset]](https://github.com/snakers4/open_stt) | Y | 20k + |
| 29 | ASCEND | Mandarin-English CS | Dialogue | [[paper]](https://arxiv.org/pdf/2112.06223.pdf) | [[dataset]](https://huggingface.co/datasets/CAiRE/ASCEND) | Y | 10 + |
| 30 | Crowd-Sourced Speech | Multilingual | Record | [[paper]](https://www.isca-speech.org/archive/pdfs/sltu_2018/kjartansson18_sltu.pdf) | [[dataset]](https://github.com/coqui-ai/open-speech-corpora/blob/150d316869c7ba468efd1f7b473555b0c76cc5e6/README.md?plain=1#L80) | Y | 1200 + |
| 31 | Spoken Wikipedia | Multilingual | Record | [[paper]](https://arne.chark.eu/static/spoken-wp-corpus-collection.pdf) | [[dataset]](https://corpora.uni-hamburg.de/hzsk/de/islandora/object/spoken-corpus:swc-2.0#additional-files) | Y | 1000 + |
| 32 | MuST-C | Multilingual | Talk | [[paper]](https://aclanthology.org/N19-1202.pdf) | [[dataset]](https://ict.fbk.eu/must-c-release-v1-2/) | Y | 6000 + |
| 33 | M-AILABS | Multilingual | Read | - | [[dataset]](https://www.caito.de/2019/01/03/the-m-ailabs-speech-dataset/) | Y | 1000 |
| 34 | CMU Wilderness | Multilingual | Misc | [[paper]](http://www.cs.cmu.edu/~awb/papers/2019_Black_ICASSP.pdf) | [[dataset]](https://github.com/festvox/datasets-CMU_Wilderness) | Y | unsup(14k) |
| 35 | Gram_Vaani | Hindi | Record | [[paper]](https://arxiv.org/pdf/2203.16973.pdf) [[code]](https://github.com/anish9208/gramvaani_hindi_asr) | [[dataset]](https://www.openslr.org/118/) | Y | unsup(1000)+sup(100) |
| 36 | VoxLingua107 | Multilingual | Misc | [[paper]](https://arxiv.org/pdf/2011.12998.pdf) | [[dataset]](http://bark.phon.ioc.ee/voxlingua107/) | Y | unsup(6600 +) |
| 37 | Kazakh Corpus | Kazakh | Record | [[paper]](https://arxiv.org/pdf/2009.10334.pdf) [[code]](https://github.com/IS2AI/ISSAI_SAIDA_Kazakh_ASR) | [[dataset]](https://www.openslr.org/102/) | Y | 335 |
| 38 | Voxforge | English | Record | - | [[dataset]](http://www.voxforge.org/home/downloads) | Y | 130 |
| 39 | Tatoeba | English | Record | - | [[dataset]](https://downloads.tatoeba.org/audio/) | Y | 200 |
| 40 | IndicWav2Vec | Multilingual | Misc | [[paper]](https://arxiv.org/pdf/2111.03945.pdf) | [[dataset]](https://github.com/AI4Bharat/IndicWav2Vec/tree/main/data_prep_scripts/pret_scripts) | Y | unsup(17k +) |
| 41 | VoxCeleb | English | Misc | [[paper]](https://www.robots.ox.ac.uk/~vgg/publications/2017/Nagrani17/nagrani17.pdf) | [[dataset]](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/vox1.html) | Y | unsup(352) |
| 42 | VoxCeleb2 | English | Misc | [[paper]](https://www.robots.ox.ac.uk/~vgg/publications/2018/Chung18a/chung18a.pdf) | [[dataset]](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/vox2.html) | Y | unsup(2442) |
| 43 | RuLibrispeech | Russian | Read | - | [[dataset]](https://www.openslr.org/96/) | Y | 98 |
| 44 | MediaSpeech | Multilingual | Misc | [[paper]](https://arxiv.org/pdf/2103.16193.pdf) | [[dataset]](https://www.openslr.org/108/) | Y | 40 |
| 45 | MUCS 2021 task1 | Multilingual | Misc | - | [[dataset]](https://www.openslr.org/103/) | Y | 300 |
| 46 | MUCS 2021 task2 | Multilingual | Misc | - | [[dataset]](https://www.openslr.org/104/) | Y | 150 |
| 47 | nicolingua-west-african | Multilingual | Misc | [[paper]](https://arxiv.org/pdf/2104.13083.pdf) | [[dataset]](https://www.openslr.org/105/) | Y | 140 + |
| 48 | Samromur 21.05 | Samromur | Misc | [[code]](https://github.com/cadia-lvl/samromur-asr) | [[dataset]](https://www.openslr.org/112/) [[dataset]](https://www.openslr.org/116/)[[dataset]](https://www.openslr.org/117) | Y | 145 |
| 49 | Puebla-Nahuatl | Puebla-Nahuatl | Misc | [[paper]](https://aclanthology.org/2021.americasnlp-1.7.pdf) | [[dataset]](https://www.openslr.org/92/) | Y | 150 + |
| 50 | Golos | Russian | Misc | [[paper]](https://arxiv.org/pdf/2106.10161.pdf) | [[dataset]](https://www.openslr.org/114/) | Y | 1240 |
| 51 | ParlaSpeech-HR | Croatian | Parliament | [[paper]](https://office.clarin.eu/v/CE-2021-1923-CLARIN2021_ConferenceProceedings.pdf) | [[dataset]](https://www.clarin.si/repository/xmlui/handle/11356/1494) | Y | 1816 |
| 52 | Lyon Corpus | French | Record | [[paper]](https://www.mq.edu.au/__data/assets/pdf_file/0006/910077/2008Demuth-and-Tremblay.pdf) | [[dataset]](https://phonbank.talkbank.org/access/French/Lyon.html) | Y | 185 |
| 53 | Providence Corpus | English | Record | [[paper]](https://d1wqtxts1xzle7.cloudfront.net/66484402/2006DemuthetalL_S-libre.pdf?1619046276=&response-content-disposition=inline%3B+filename%3DWord_minimality_Epenthesis_and_Coda_Lice.pdf&Expires=1652977685&Signature=d3EpWElGBNwVe6wvbA-Erk9bhbykEtwwSJN3JRcLRPU4dSB2iHz8FOjsYKf9YQVLQVHtNF-5L7EF325B7jWfaBXewazatJ9f-uC2qqQO~JPhD9GQgfTXims4pfu7cm1irdRT7fgYeqAbTT6xM9LMB0LdyMsevxB6tCJCX3IZwUdUaYsmNgm9iROxn7MZnr74gmQTekpRNK0AJFjpR261oYR5ORf8sgnpdVmjlbhlOTVraj12huOIvxEoIZ~QoFwA1mFSrLArBj83gdNVPvHpBFNoup4Dsejq1MbDOogFkoh~fW3C21xnjpM5PvUuq7SeT~gDgZQ~aZo14IS474pMtw__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA) | [[dataset]](https://phonbank.talkbank.org/access/Eng-NA/Providence.html) | Y | 364 |
| 54 | CLARIN Spoken Corpora | Czech | Record | - | [[dataset]](https://www.clarin.eu/resource-families/spoken-corpora) | Y | 1120 + |
| 55 | Czech Parliament Plenary | Czech | Record | - | [[dataset]](https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-3126) | Y | 444 |
| 56 | Regional American Corpus | English (Accented) | Misc | [[paper]](http://cc.oulu.fi/~scoats/YouTube_Corpus_19a.pdf) | [[dataset]](https://github.com/stcoats/YouTube_Corpus) | Y | 29k + |
| 57 | NISP Dataset | Multilingual | Record | [[paper]](https://arxiv.org/pdf/2007.06021.pdf) | [[dataset]](https://github.com/iiscleap/NISP-Dataset?utm_source=catalyzex.com) | Y | 56 + |
| 58 | Regional African American | English (Accented) | Record | [[paper]](http://lingtools.uoregon.edu/coraal/userguide/CORAALUserGuide_current.pdf) | [[dataset]](http://lingtools.uoregon.edu/coraal/) | Y | 130 + |
| 59 | Indonesian Unsup | Indonesian | Misc | - | [[dataset]](https://github.com/Wikidepia/indonesian_datasets/tree/master/speech/unsupervised) | Y | unsup (3000+) |
| 60 | Librivox-Spanish | Spanish | Record | - | [[dataset]](https://www.kaggle.com/datasets/carlfm01/120h-spanish-speech) | Y | 120 |
| 61 | AVSpeech | English | Audio-Visual | [[paper]](https://arxiv.org/pdf/1804.03619.pdf) | [[dataset]](https://looking-to-listen.github.io/avspeech/download.html) | Y | unsup(4700) |
| 62 | CMLR | Mandarin | Audio-Visual | [[paper]](https://arxiv.org/pdf/1908.04917.pdf) | [[dataset]](https://www.vipazoo.cn/CMLR.html) | Y | 100 + |
| 63 | Speech Accent Archive | English | Accented | [[paper]](https://brill.com/view/book/edcoll/9789401206884/B9789401206884-s014.xml) | [[dataset]](http://accent.gmu.edu/browse_language.php) | Y | TBC |
| 64 | BibleTTS | Multilingual | TTS | [[paper]](https://arxiv.org/pdf/2203.14456.pdf) | [[dataset]](https://masakhane-io.github.io/bibleTTS/) | Y | 86 |
| 65 | NST-Norwegian | Norwegian | Record | - | [[dataset]](https://www.nb.no/sprakbanken/en/resource-catalogue/oai-nb-no-sbr-54/) | Y | 540 |
| 66 | NST-Danish | Danish | Record | - | [[dataset]](https://www.nb.no/sprakbanken/en/resource-catalogue/oai-nb-no-sbr-55/) | Y | 500 + |
| 67 | NST-Swedish | Swedish | Record | - | [[dataset]](https://www.nb.no/sprakbanken/en/resource-catalogue/oai-nb-no-sbr-56/) | Y | 300 + |
| 68 | NPSC | Norwegian | Parliament | [[paper]](http://www.lrec-conf.org/proceedings/lrec2022/pdf/2022.lrec-1.106.pdf) | [[dataset]](https://www.nb.no/sprakbanken/en/resource-catalogue/oai-nb-no-sbr-58/) | Y | 140 |
| 69 | CI-AVSR | Cantonese | Audio-Visual | [[paper]](https://arxiv.org/pdf/2201.03804.pdf) | [[dataset]](https://github.com/HLTCHKUST/CI-AVSR) | Y | 8 + |
| 70 | Aalto Finnish Parliament | Finnish | Parliament | [[paper]](https://arxiv.org/pdf/2203.14876.pdf) | [[dataset]](https://www.kielipankki.fi/corpora/fi-parliament-asr/) | Y | 3100 + |
| 71 | UserLibri | English | Record | [[paper]](https://arxiv.org/pdf/2207.00706.pdf) | [[dataset]](https://www.kaggle.com/datasets/google/userlibri) | Y | - |
| 72 | Fisher | English | Conversational | [[paper]](http://www.lrec-conf.org/proceedings/lrec2004/pdf/767.pdf) | [[dataset]](https://catalog.ldc.upenn.edu/search) | N (Apply) | 2000 |
| 73 | WenetSpeech | Mandarin | Misc | [[paper]](https://arxiv.org/pdf/2110.03370.pdf) | [[dataset]](https://www.openslr.org/121) | N (Apply) | sup(10k)+weaksup(2.4k)+unsup(10k)=22.4k |
| 74 | aishell-2 | Mandarin | Record | [[paper]](https://arxiv.org/pdf/1808.10583.pdf) | [[dataset]](https://www.aishelltech.com/aishell_2) | N (Apply) | 1000 |
| 75 | aidatatang_1505zh | Mandarin | Record | - | [[dataset]](https://www.datatang.com/opensource) | N (Apply) | 1505 |
| 76 | SLT 2021 CSRC | Mandarin | Misc | [[paper]](https://arxiv.org/pdf/2011.06724.pdf) | [[dataset]](https://www.data-baker.com/csrc_challenge.html) | N (Apply) | 400 |
| 77 | GigaSpeech | English | Misc | [[paper]](https://arxiv.org/pdf/2106.06909.pdf) | [[dataset]](https://github.com/SpeechColab/GigaSpeech) | N (Apply) | sup(10k)+unsup(23k)=33k |
| 78 | SPGISpeech | English | Misc | [[paper]](https://arxiv.org/pdf/2104.02014.pdf) | [[dataset]](https://datasets.kensho.com/datasets/spgispeech) | N (Apply) | 5000 |
| 79 | AESRC 2020 | English (accented) | Misc | [[paper]](https://arxiv.org/pdf/2102.10233.pdf) | [[dataset]](https://www.datatang.com/INTERSPEECH2020) | N (Apply) | 160 |
| 80 | LaboroTVSpeech | Japanese | Misc | [[paper]](https://arxiv.org/pdf/2103.14736.pdf) | [[dataset]](https://laboro.ai/activity/column/engineer/eg-laboro-tv-corpus-jp/) | N (Apply) | 2000 + |
| 81 | TAL_CSASR | Mandarin-English CS | Lecture | - | [[dataset]](https://ai.100tal.com/dataset) | N (Apply) | 587 |
| 82 | ASRU 2019 ASR | Mandarin-English CS | Read | - | [[dataset]](https://www.datatang.com/competition) | N (Apply) | 700 + |
| 83 | SEAME | Mandarin-English CS | Record | [[paper]](https://www.isca-speech.org/archive/pdfs/interspeech_2010/lyu10_interspeech.pdf) | [[dataset]](https://catalog.ldc.upenn.edu/LDC2015S04) | N (Apply) | 196 |
| 84 | Fearless Steps | English | Misc | - | [[dataset]](https://fearless-steps.github.io/ChallengePhase3/#19k_Corpus_Access) | N (Apply) | unsup(19k) |
| 85 | FTSpeech | Danish | Meeting | [[paper]](https://arxiv.org/pdf/2005.12368.pdf) | [[dataset]](https://ftspeech.github.io/) | N (Apply) | 1800 + |
| 86 | KeSpeech | Mandarin | Record | [[paper]](https://openreview.net/pdf?id=b3Zoeq2sCLq) | [[dataset]](https://github.com/KeSpeech/KeSpeech) | N (Apply) | 1542 |
| 87 | KsponSpeech | Korean | Dialogue | [[paper]](https://www.mdpi.com/2076-3417/10/19/6936) | [[dataset]](https://aihub.or.kr/aidata/105/download) | N (Apply) | 969 |
| 88 | RVTE database | Spanish | TV show | [[paper]](https://catedrartve.unizar.es/reto2022/RTVE2022DB.pdf) | [[dataset]](https://catedrartve.unizar.es/rtvedatabase.html) | N (Apply) | 800 + |
| 89 | DiDiSpeech | Mandarin | Record | [[paper]](https://arxiv.org/pdf/2010.09275.pdf) | [[dataset]](https://outreach.didichuxing.com/research/opendata/) | N (Apply) | 800 |
| 90 | Babel | Multilingual | Telephone | [[paper]](https://eprints.whiterose.ac.uk/152840/8/Gales%20et%20al%202014.pdf) | [[dataset]](https://www.nist.gov/itl/iad/mig/openkws16-evaluation) | N (Apply) | 1000 + |
| 91 | National Speech Corpus | English (Singapore) | Misc | [[paper]](https://www.isca-speech.org/archive_v0/Interspeech_2019/pdfs/1525.pdf) | [[dataset]](https://www.imda.gov.sg/programme-listing/digital-services-lab/national-speech-corpus) | N (Apply) | 3000 + |
| 92 | MyST Children's Speech | English | Record | - | [[dataset]](http://boulderlearning.com/request-the-myst-corpus/) | N (Apply) | 393 |
| 93 | L2-ARCTIC | L2 English | Record | [[paper]](https://www.isca-speech.org/archive_v0/Interspeech_2018/pdfs/1110.pdf) | [[dataset]](https://psi.engr.tamu.edu/l2-arctic-corpus/) | N (Apply) | 20 + |
| 94 | JSpeech | Multilingual | Record | [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8639658) | [[dataset]](https://github.com/miras-tech/jspeech) | N (Apply) | 1332 + |
| 95 | LRS2-BBC | English | Audio-Visual | [[paper]](https://arxiv.org/pdf/1809.02108.pdf) | [[dataset]](https://www.robots.ox.ac.uk/~vgg/data/lip_reading/lrs2.html) | N (Apply) | 220 + |
| 96 | LRS3-TED | English | Audio-Visual | [[paper]](https://arxiv.org/pdf/1809.00496.pdf) | [[dataset]](https://www.robots.ox.ac.uk/~vgg/data/lip_reading/lrs3.html) | N (Apply) | 470 + |
| 97 | LRS3-Lang | Multilingual | Audio-Visual | - | [[dataset]](https://www.robots.ox.ac.uk/~vgg/data/lip_reading/lrs3-lang.html) | N (Apply) | 1300 + |
| 98 | QASR | Arabic | Dialects | [[paper]](https://arxiv.org/pdf/2106.13000.pdf) | [[dataset]](https://arabicspeech.org/qasr/) | N (Apply) | 2000 + |
| 99 | ADI (MGB-5) | Arabic | Dialects | [[paper]](https://swshon.github.io/pdf/ali_asru2019_mgb5.pdf) | [[dataset]](https://arabicspeech.org/mgb5/#adi17) | N (Apply) | unsup (3000 +) |
| 100 | MGB-2 | Arabic | TV | [[paper]](https://arxiv.org/pdf/1609.05625.pdf) | [[dataset]](http://www.mgb-challenge.org/MGB-2.html) | N (Apply) | 1200 + |
| 101 | 3MASSIV | Multilingual | Audio-Visual | [[paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Gupta_3MASSIV_Multilingual_Multimodal_and_Multi-Aspect_Dataset_of_Social_Media_Short_CVPR_2022_paper.pdf) | [[dataset]](https://github.com/ShareChatAI/3MASSIV) | N (Apply) | sup(310)+unsup(600) |
| 102 | MDCC | Cantonese | Misc | [[paper]](https://arxiv.org/pdf/2201.02419.pdf) | [[dataset]](https://github.com/HLTCHKUST/cantonese-asr) | N (Apply) | 73 + |
| 103 | Lahjoita Puhetta | Finnish | Misc | [[paper]](https://arxiv.org/pdf/2203.12906.pdf) | [[dataset]](https://github.com/aalto-speech/lahjoita-puhetta-resources) | N (Apply) | sup(1600) + unsup(2000) |
| 104 | SDS-200 | Swiss German | Dialects | [[paper]](https://arxiv.org/pdf/2205.09501.pdf) | [[dataset]](https://swissnlp.org/datasets/) | N (Apply) | 200 |
| 105 | Modality Corpus | Misc | Audio-Visual | [[paper]](https://link.springer.com/content/pdf/10.1007/s10844-016-0438-z.pdf) | [[dataset]](http://www.modality-corpus.org/) | N (Apply) | 30 + |

