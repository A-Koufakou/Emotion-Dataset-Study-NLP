**This README contains brief descriptions and links for recent datasets labeled with emotions (presented since 2018)**

**Affect in Tweets**
- Authors: Saif Mohammad, Felipe Bravo-Marquez, Mohammad Salameh, and Svetlana Kiritchenko.
- Size: ~11,000 English tweets
- Description: Part of the SemEval 2018 task 1. Contains tweets from 2016-17 with different query terms.
- Labels: each record could be neutral, or one or more of the following: anger, disgust, fear, joy, sadness, surprise, trust, anticipation, optimism, pessimism
- Link to paper: [https://aclanthology.org/S18-1001/](https://aclanthology.org/S18-1001/)
- Link to dataset: [https://competitions.codalab.org/competitions/17751](https://competitions.codalab.org/competitions/17751)

**AraEmoCorpus**
- Description: collected 5.5 million Arabic tweets during the COVID-19 pandemic.
- Labels: They automatically labeled a subset of the tweets with Ekman, using a hybrid of rule-based and neural network techniques. 

**CARER**
- Authors: Elvis Saravia, Hsien-Chi Toby Liu, Yen-Hao Huang, Junlin Wu, and Yi-Shin Chen.
- Size: total was 416,809 tweets. Sample we used for our experiments: 62,522
- Description: Saravia et al. (2018) collected tweets with a set of hashtags they constructed, e.g. #depressed, #grief for sadness, or #fear, #worried for fear.
- Labels: anger, fear, joy, sadness, surprise, love
- Link to paper: [https://aclanthology.org/D18-1404/](https://aclanthology.org/D18-1404/)
- Link to dataset: [https://huggingface.co/datasets/dair-ai/emotion](https://huggingface.co/datasets/dair-ai/emotion)

**CEDR** 
- Decription: Created a corpus of Russian data collected from several sources: social network posts, texts from an online news agency, and tweets.
- Labels: Data were annotated by crowdsourcing workers with Ekman minus disgust (multi-label). 

**Covid-Worry**
- Authors: Bennett Kleinberg, Isabelle van der Vegt, and Maximilian Mozes
- Size: 5,350 survey responses from 3 years
- Description: Contains survey responses collected by (Kleinberg et al., 2020) in the UK first in 2020 and then 2021-22 (van der Vegt and Kleinberg, 2023). Participants wrote and self-rated the records.
- Labels: anger, anxiety, disgust, desire, fear, happiness, relaxation,  sadness
- Link to paper: [https://aclanthology.org/2020.nlpcovid19-acl.11/](https://aclanthology.org/2020.nlpcovid19-acl.11/)
- Link to dataset: [https://osf.io/awy7r/](https://osf.io/awy7r/)

**DENS**
- Authors: Liu et al.
- collected classic and modern English narratives from online sources (wattpad and Project Gutenberg). The 9,710 passages in DENS (Dataset for Emotions of Narrative Sequences) were annotated by Amazon Mechanical Turk workers with joy, sadness, anger, fear, anticipation, surprise, love, disgust, neutral.
- The data is available on request.

**EmoContext**
- Authors: Ankush Chatterjee, Kedhar Nath Narahari, Meghana Joshi, and Puneet Agrawal.
- Size: ~40,000 dialogues
- Description: Part of the SemEval 2019 task 3. Contains textual dialogue: a user utterance along with two turns of context.
- Labels: happy, sad, angry, neutral
- Link to paper: [https://aclanthology.org/S19-2005/](https://aclanthology.org/S19-2005/)
- Link to dataset: [https://competitions.codalab.org/competitions/19790](https://competitions.codalab.org/competitions/19790)

**EmoEvent**
- Authors: Flor Miriam Plaza del Arco, Carlo Strapparava, L. Alfonso Urena Lopez, and Maite Martin
- Size: 7,303 English tweets 
- Description: Contains tweets collected by (Plaza-del-Arco et al., 2020) related to events in 2019. The resulting tweets in English and in Spanish were annotated by Amazon MTurkers.
- Labels: anger, disgust, fear, joy, sadness, surprise, neutral
- Link to paper: [https://aclanthology.org/2020.lrec-1.186/](https://aclanthology.org/2020.lrec-1.186/)
- Link to dataset: [https://github.com/fmplaza/EmoEvent](https://github.com/fmplaza/EmoEvent)

**EmotionLines**
- Authors: Sheng-Yeh Chen, Chao-Chun Hsu, Chuan-Chun Kuo, Ting-Hao (Kenneth)Huang, Lun-Wei Ku
- Size: ~29,000 dialogues
- Description: Contains dialogue from TV scripts and Facebook Messenger.
- Labels: anger, disgust, fear, joy, sadness, surprise, neutral
- Link to paper: [https://aclanthology.org/L18-1252/](https://aclanthology.org/L18-1252/)
- Link to dataset: [https://doraemon.iis.sinica.edu.tw/emotionlines/index.html](https://doraemon.iis.sinica.edu.tw/emotionlines/index.html)

**enISEAR**
- Authors: Enrica Troiano, Sebastian Padó, Roman Klinger
- Size: 1,001 English questionnaire responses
- Description: Answers from a questionnaire where crowdsourced annotators gave a description of an event for which they felt a particular emotion. Uses a framework similar to earlier ISEAR (International Survey on Emotion Antecedents and Reactions)(Scherer and Wallbott, 1994).
- Labels: anger, disgust, fear, joy, sadness, surprise, shame/guilt
- Link to paper: [https://aclanthology.org/P19-1391/](https://aclanthology.org/P19-1391/)
- Link to dataset: [https://www.ims.uni-stuttgart.de/forschung/ressourcen/korpora/deisear/](https://www.ims.uni-stuttgart.de/forschung/ressourcen/korpora/deisear/)

**FB-Emo-SP**
- Authors: Tessore et al.
- collected Spanish comments and reactions from Facebook for popular news portals in Argentina in 2016-2019.
- Labels: distant supervision. They only kept comments with reactions love, haha, angry, and sad (these were actual reactions on Facebook). Out of these (over one million) comments, a sample of 247 comments were manually tagged by psychologists. 

**FEEL-IT**
- Authors: Bianchi et al.
- Description: Collected Italian tweets in 2020 without using specific terms.
- Labels: Two of the authors annotated about 2 thousand tweets with four emotions: anger, fear, joy, sadness.

**github-emotion-love**
- Authors: Mia Mohammad Imran, Yashasvi Jain, Preetha Chatterjee, Kostadin Damevski
- Size: 1,719 GitHub comments
- Description: This dataset by (Imran et al., 2022) contains GitHub comments on pull requests/issues for popular repositories. The comments were labeled by the authors.
- Labels: anger, fear, joy, sadness, surprise, love
- Link to paper: [https://dl.acm.org/doi/pdf/10.1145/3551349.3556925](https://dl.acm.org/doi/pdf/10.1145/3551349.3556925)
- Link to dataset: [https://huggingface.co/datasets/imranraad/github-emotion-love](https://huggingface.co/datasets/imranraad/github-emotion-love)

**GoEmotions**
- Authors: Dorottya Demszky, Dana Movshovitz-Attias, Jeongwoo Ko, Alan Cowen, Gaurav Nemade, Sujith Ravi
- Size: about 58K Reddit comments
- Description: Contains Reddit comments with fine-grained human annotations.
- Labels
  - 27 emotions + neutral. Revised from Cowen and Keltner.
  - Included Ekman mapping: anger, disgust, fear, joy, sadness, surprise, neutral
- Link to paper: [https://aclanthology.org/2020.acl-main.372/](https://aclanthology.org/2020.acl-main.372/)
- Link to dataset: [https://github.com/google-research/google-research/tree/master/goemotions](https://github.com/google-research/google-research/tree/master/goemotions)

**GoodNews** 
- Authors: Bostan et al.
- Collected English news headlines and annotated them via crowdsourcing (titled `GoodNewsEveryone' in the paper). Annotations were provided for emotions and their intensity, as well as semantic roles (experiencer, cause, target, cue) and reader perspective.
- Emotions were extended Plutchick: anger, annoyance, disgust, fear, guilt, joy, love, negative anticipation including pessimism, negative surprise, positive anticipation including optimism, positive surprise, pride, sadness, shame, and trust.

**StackOverflow - Gold Standard**
- Authors: Nicole Novielli, Fabio Calefato, Filippo Lanubile
- Size: 2,974 Stack Overflow posts
- Description: Novielli et al. (2018) collected Stack Overflow questions, answers, and comments. They were annotated by volunteers.
- Labels: anger, disgust, fear, joy, sadness, surprise, love
- Link to paper: [https://dl.acm.org/doi/pdf/10.1145/3196398.3196453](https://dl.acm.org/doi/pdf/10.1145/3196398.3196453)
- Link to dataset: [https://github.com/collab-uniba/EmotionDatasetMSR18](https://github.com/collab-uniba/EmotionDatasetMSR18)

**TweetEval**
- Authors: Francesco Barbieri, Jose Camacho-Collados, Leonardo Neves, Luis Espinosa-Anke
- Size: 5,052 tweets
- Description: A unified Twitter dataset with seven heterogeneous Twitter-specific classification tasks. Includes Affect in Tweets (Mohammad et al., 2018), only keeping single-label records.
- Labels: anger, joy, optimism, sadness
- Link to paper: [https://aclanthology.org/2020.findings-emnlp.148/](https://aclanthology.org/2020.findings-emnlp.148/)
- Link to dataset: [https://github.com/cardiffnlp/tweeteval/tree/main/datasets/emotion](https://github.com/cardiffnlp/tweeteval/tree/main/datasets/emotion)

**Universal Joy**
- Authors: Sotiris Lamprinidis, Federico Bianchi, Daniel Hardt, Dirk Hovy
- Size: total was 167,313 Facebook posts. Sample we used for our experiments: 50,195
- Description: Lamprinidis et al. (2021) presented a dataset with anonymized public Facebook posts collected in 2014 in 18 languages. The authors labeled the records.
- Labels: anger, anticipation, fear, joy, sadness
- Link to paper: [https://aclanthology.org/2021.wassa-1.7/](https://aclanthology.org/2021.wassa-1.7/)
- Link to dataset: [https://github.com/sotlampr/universal-joy](https://github.com/sotlampr/universal-joy)

**WASSA-21**
- Authors: Valentin Barriere, João Sedoc, Shabnam Tafreshi, and Salvatore Giorgi
- Size: 2,385 essays.
- Description: Part of the 11th Workshop on Computational Approaches to Subjectivity, Sentiment & Social Media Analysis. Contains essays written after reading news articles related to harm to an individual, nature, etc.
- Labels: anger, disgust, fear, joy, sadness, surprise, neutral
- Link to paper: [https://aclanthology.org/2021.wassa-1.10/](https://aclanthology.org/2021.wassa-1.10/)
- Link to dataset: [https://competitions.codalab.org/competitions/28713](https://competitions.codalab.org/competitions/28713)
