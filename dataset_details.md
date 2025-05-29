**This README contains brief descriptions and links for recent datasets labeled with emotions (presented since 2018)**

**Affect in Tweets**
- Authors: Saif Mohammad, Felipe Bravo-Marquez, Mohammad Salameh, and Svetlana Kiritchenko.
- Description: Part of the SemEval 2018 task 1. Contains tweets from 2016-17 with different query terms, ~11,000 English tweets.
- Labels: each record could be neutral, or one or more of the following: anger, disgust, fear, joy, sadness, surprise, trust, anticipation, optimism, pessimism
- Link to paper: [https://aclanthology.org/S18-1001/](https://aclanthology.org/S18-1001/)
- [https://competitions.codalab.org/competitions/17751](https://competitions.codalab.org/competitions/17751)

**AraEmoCorpus**
- Authors: Al-Laith, A., & Alenezi, M. (2021)
- Description: collected 5.5 million Arabic tweets during the COVID-19 pandemic.
- Labels: They automatically labeled a subset of the tweets with Ekman, using a hybrid of rule-based and neural network techniques.
- https://github.com/yemen2016/COVID-19-Arabic-Emotion-Dataset 

**CARER**
- Authors: Elvis Saravia, Hsien-Chi Toby Liu, Yen-Hao Huang, Junlin Wu, and Yi-Shin Chen.
- Description: Saravia et al. (2018) collected tweets with a set of hashtags they constructed, e.g. #depressed, #grief for sadness, or #fear, #worried for fear. 416,809 tweets. 
- Labels: anger, fear, joy, sadness, surprise, love
- Link to paper: [https://aclanthology.org/D18-1404/](https://aclanthology.org/D18-1404/)
- [https://huggingface.co/datasets/dair-ai/emotion](https://huggingface.co/datasets/dair-ai/emotion)

**CEDR** 
- Authors: Shoeb, A. A. M., & De Melo, G. (2020).
- Decription: Created a corpus of Russian data collected from several sources: social network posts, texts from an online news agency, and tweets.
- Labels: Data were annotated by crowdsourcing workers with Ekman minus disgust (multi-label).
- https://huggingface.co/datasets/cedr 

**Covid-Worry**
- Authors: Bennett Kleinberg, Isabelle van der Vegt, and Maximilian Mozes
- Description: Contains survey responses collected by (Kleinberg et al., 2020) in the UK first in 2020 and then 2021-22 (van der Vegt and Kleinberg, 2023). Participants wrote and self-rated the records. 5,350 survey responses from 3 years.
- Labels: anger, anxiety, disgust, desire, fear, happiness, relaxation,  sadness
- Link to paper: [https://aclanthology.org/2020.nlpcovid19-acl.11/](https://aclanthology.org/2020.nlpcovid19-acl.11/)
- [https://osf.io/awy7r/](https://osf.io/awy7r/)

**DENS**
- Authors: Liu, C., Osama, M., & De Andrade, A. (2019)
- Description: Collected classic and modern English narratives from online sources (wattpad and Project Gutenberg). The 9,710 passages in DENS (Dataset for Emotions of Narrative Sequences) were annotated by Amazon Mechanical Turk workers with joy, sadness, anger, fear, anticipation, surprise, love, disgust, neutral.
- The data is available on request.

**EmoContext**
- Authors: Ankush Chatterjee, Kedhar Nath Narahari, Meghana Joshi, and Puneet Agrawal.
- Description: Part of the SemEval 2019 task 3. Contains 40,0000 textual dialogues: a user utterance along with two turns of context.
- Labels: happy, sad, angry, neutral
- Link to paper: [https://aclanthology.org/S19-2005/](https://aclanthology.org/S19-2005/)
- [https://competitions.codalab.org/competitions/19790](https://competitions.codalab.org/competitions/19790)

**EmoEvent**
- Authors: Flor Miriam Plaza del Arco, Carlo Strapparava, L. Alfonso Urena Lopez, and Maite Martin
- Description: Contains tweets collected by (Plaza-del-Arco et al., 2020) related to events in 2019. The resulting tweets in English and in Spanish were annotated by Amazon MTurkers.
- Labels: anger, disgust, fear, joy, sadness, surprise, neutral
- Link to paper: [https://aclanthology.org/2020.lrec-1.186/](https://aclanthology.org/2020.lrec-1.186/)
- https://github.com/fmplaza/EmoEvent](https://github.com/fmplaza/EmoEvent)

**EmotionLines**
- Authors: Sheng-Yeh Chen, Chao-Chun Hsu, Chuan-Chun Kuo, Ting-Hao (Kenneth)Huang, Lun-Wei Ku
- Description: Contains 29,000 dialogues from TV scripts and Facebook Messenger.
- Labels: anger, disgust, fear, joy, sadness, surprise, neutral
- Link to paper: [https://aclanthology.org/L18-1252/](https://aclanthology.org/L18-1252/)
- [https://doraemon.iis.sinica.edu.tw/emotionlines/index.html](https://doraemon.iis.sinica.edu.tw/emotionlines/index.html)

**enISEAR**
- Authors: Enrica Troiano, Sebastian Padó, Roman Klinger
- Description: Answers from a questionnaire where crowdsourced annotators gave a description of an event for which they felt a particular emotion. Uses a framework similar to earlier ISEAR (International Survey on Emotion Antecedents and Reactions)(Scherer and Wallbott, 1994).
- Labels: anger, disgust, fear, joy, sadness, surprise, shame/guilt
- Link to paper: [https://aclanthology.org/P19-1391/](https://aclanthology.org/P19-1391/)
- [https://www.ims.uni-stuttgart.de/forschung/ressourcen/korpora/deisear/](https://www.ims.uni-stuttgart.de/forschung/ressourcen/korpora/deisear/)

**FB-Emo-SP**
- Authors: Tessore, J. P., Esnaola, L. M., Lanzarini, L., & Baldassarri, S. (2022)
- Description: Collected Spanish comments and reactions from Facebook for popular news portals in Argentina in 2016-2019.
- Labels: distant supervision. They only kept comments with reactions love, haha, angry, and sad (these were actual reactions on Facebook). Out of these (over one million) comments, a sample of 247 comments were manually tagged by psychologists.
- https://link.springer.com/article/10.1007/s12559-020-09800-x#Sec17 

**FEEL-IT**
- Authors: Bianchi, F., Nozza, D., & Hovy, D. (2021)
- Description: Collected Italian tweets in 2020 without using specific terms.
- Labels: Two of the authors annotated about 2 thousand tweets with four emotions: anger, fear, joy, sadness.
- On request: https://github.com/MilaNLProc/feel-it 

**github-emotion-love**
- Authors: Mia Mohammad Imran, Yashasvi Jain, Preetha Chatterjee, Kostadin Damevski
- Description: GitHub comments on pull requests/issues for popular repositories. The comments were labeled by the authors.
- Labels: anger, fear, joy, sadness, surprise, love
- Link to paper: [https://dl.acm.org/doi/pdf/10.1145/3551349.3556925](https://dl.acm.org/doi/pdf/10.1145/3551349.3556925)
- [https://huggingface.co/datasets/imranraad/github-emotion-love](https://huggingface.co/datasets/imranraad/github-emotion-love) and https://github.com/vcu-swim-lab/SE-Emotion-Study

**GoEmotions**
- Authors: Dorottya Demszky, Dana Movshovitz-Attias, Jeongwoo Ko, Alan Cowen, Gaurav Nemade, Sujith Ravi
- Description: Contains Reddit comments with fine-grained human annotations.
- Labels
  - 27 emotions + neutral. Revised from Cowen and Keltner.
  - Included Ekman mapping: anger, disgust, fear, joy, sadness, surprise, neutral
- Link to paper: [https://aclanthology.org/2020.acl-main.372/](https://aclanthology.org/2020.acl-main.372/)
- [https://github.com/google-research/google-research/tree/master/goemotions](https://github.com/google-research/google-research/tree/master/goemotions)

**GoodNews** 
- Authors: ﻿	Bostan, L.A.M., Kim, E., & Klinger, R. (2020)
- Description: Collected English news headlines and annotated them via crowdsourcing (titled `GoodNewsEveryone' in the paper). Annotations were provided for emotions and their intensity, as well as semantic roles (experiencer, cause, target, cue) and reader perspective.
- Labels: anger, annoyance, disgust, fear, guilt, joy, love, negative anticipation including pessimism, negative surprise, positive anticipation including optimism, positive surprise, pride, sadness, shame, and trust.
- https://www.ims.uni-stuttgart.de/forschung/ressourcen/korpora/goodnewseveryone/

**IAEC (Iraqi Arabic Emotion Corpus)**  
- Authors: Almahdawi, A. J., & Teahan, W. J. (2019).
- Description: IAEDS collected Facebook posts in 2016-18 written in the Iraqi dialect using words such as happy or awesome for happiness.
- Labels: Iraqui annotators (professors) annotated the records with Ekman.
- This corpus is not publicly available.

**MultiEmo-IT** 
- Authors: Sprugnoli, R. (2020).
- Description: Italian comments on youtube videos and on Facebook videos/pictures collected in 2020 (originally named MultiEmotions-IT).
- Labels: annotated by students following Plutchik and neutral, plus dyads: composed of two basic emotions (e.g., love is a blend of joy and trust). The annotation also involved `relatedness' to the media content, polarity of opinion, and if the comment expressed sarcasm.
- https://github.com/RacheleSprugnoli/Esercitazioni_SA
  
**Palo-Emo-Gr** 
- Authors: Alexandridis, G., Korovesis, K., Varlamis, I., Tsantilas, P., & Caridakis, G. (2021).
- Description: collected Greek tweets and then annotated them through crowdsourcing
- Labels: Plutchik or none (multi-labeled when not in none). 
- This corpus is not publicly available.

**RECCON** 
- Authors: Poria, S., Majumder, N., Hazarika, D., Ghosal, D., Bhardwaj, R., & Jian, S. Y. B. (2021).
- Description: conversational utterances also annotated with the cause of the emotion. RECCON (Recognizing Emotion Cause in CONversations) contains samples from previous datasets: IEMOCAP pbusso2008iemocap and Daily Dialog.
- LAbels: annotated by undergraduate/graduate computer science students with Ekman plus neutral, frustrated, and excited.
- https://github.com/declare-lab/RECCON

**RU-EN** 
- Authors: Ilyas, A., Shahzad, K., & Kamran Malik, M. (2023).
- Description: scrapped 400,000 sentences from three social media platforms to identify 20,000 Roman Urdu sentences. Roman Urdu (RU) refers to writing Urdu using the Latin script instead of the Arabic script, which is prevalent on social media. RU-EN `code-mixed' text means that speakers switch between using English and RU words and terms.
- Labels: annotated by native speakers (paper used the term `experts') with anger, fear, happy, sad and surprise. 
- https://www.kaggle.com/drkhurramshahzad/datasets

**SenWave** 
- Authors: Yang, Q., Alamro, H., Albaradei, S., Salhi, A., Lv, X., & Ma, C. (2020).
- Description: collected more than 105 million tweets in various languages and over 1 million Chinese weibo posts, all related to COVID-19. A subset of the tweets in English and Arabic were annotated by at least three experienced annotators in the corresponding language with optimistic, thankful, empathetic, pessimistic, anxious, sad, annoyed, as well as non-emotion labels: denial, official report, and joking. They also translated the labeled English tweets into Spanish, French, and Italian with Google translate. On the other hand, a subset of the Chinese weibo posts were annotated with Ekman plus gratitude.
- https://github.com/gitdevqiang/SenWave

**ShEMO** 
- Authors: Mohamad Nezami, O., Jamshid Lou, P., & Karami, M. (2019).
- Description: Persian dataset based on radio plays. Though ShEmo (Sharif Emotional Speech Database) is a speech database, the transcripts of each record are available.
- Labels: Annotators were Persian native speakers and used anger, fear, happiness, sadness and surprise, plus neutral.
- https://huggingface.co/datasets/Mansooreh/sharif-emotional-speech-dataset

**StackOverflow - Gold Standard**
- Authors: Nicole Novielli, Fabio Calefato, Filippo Lanubile
- Description: Stack Overflow questions, answers, and comments, annotated by volunteers.
- Labels: anger, disgust, fear, joy, sadness, surprise, love
- Link to paper: [https://dl.acm.org/doi/pdf/10.1145/3196398.3196453](https://dl.acm.org/doi/pdf/10.1145/3196398.3196453)
- [https://github.com/collab-uniba/EmotionDatasetMSR18](https://github.com/collab-uniba/EmotionDatasetMSR18)

**TweetEval**
- Authors: Francesco Barbieri, Jose Camacho-Collados, Leonardo Neves, Luis Espinosa-Anke
- Description: A unified Twitter dataset with seven heterogeneous Twitter-specific classification tasks. Includes Affect in Tweets (Mohammad et al., 2018), only keeping single-label records.
- Labels: anger, joy, optimism, sadness
- Link to paper: [https://aclanthology.org/2020.findings-emnlp.148/](https://aclanthology.org/2020.findings-emnlp.148/)
- [https://github.com/cardiffnlp/tweeteval/tree/main/datasets/emotion](https://github.com/cardiffnlp/tweeteval/tree/main/datasets/emotion)

**UIT-VSMEC**
- Authors: Ho, V. A., Nguyen, D. H. C., Nguyen, D. H., Pham, L. T. V., Nguyen, D. V., Nguyen, K. V., & Nguyen, N.L.T. (2020)
- Description: Collected Vietnamese Facebook posts in the Vietnamese Social Media Emotion Corpus (VSMEC).
- Labels: annotated by 3 human annotators with Ekman plus neutral.
- https://sites.google.com/uit.edu.vn/uit-nlp/datasets

**Universal Joy**
- Authors: Sotiris Lamprinidis, Federico Bianchi, Daniel Hardt, Dirk Hovy
- Description: anonymized public Facebook posts collected in 2014 in 18 languages. The authors labeled the records.
- Labels: anger, anticipation, fear, joy, sadness
- Link to paper: [https://aclanthology.org/2021.wassa-1.7/](https://aclanthology.org/2021.wassa-1.7/)
- [https://github.com/sotlampr/universal-joy](https://github.com/sotlampr/universal-joy)

**Us vs. Them**
- Authors: Huguet Cabot, P. L., Abadi, D., Fischer, A., & Shutova, E. (2021).
- Desription: Collected Reddit comments posted for specific news headlines. Then, crowdsourcing (Amazon Mechanical Turk) to annotate the comments for populist attitudes towards specific groups such as Immigrants or Muslims or Jews. 
- Labels: Extended Ekman’s model to a 12-emotion model, so that they could include a balanced set of positive (e.g. gratitude) and negative emotions (e.g. contempt)
- https://github.com/LittlePea13/UsVsThem

**WASSA-21**
- Authors: Valentin Barriere, João Sedoc, Shabnam Tafreshi, and Salvatore Giorgi
- Description: Part of the 11th Workshop on Computational Approaches to Subjectivity, Sentiment & Social Media Analysis. Contains essays written after reading news articles related to harm to an individual, nature, etc.
- Labels: anger, disgust, fear, joy, sadness, surprise, neutral
- Link to paper: [https://aclanthology.org/2021.wassa-1.10/](https://aclanthology.org/2021.wassa-1.10/)
- [https://competitions.codalab.org/competitions/28713](https://competitions.codalab.org/competitions/28713)

**WASSA-23**
- Authors: Barriere, V., Sedoc, J., Tafreshi, S., & Giorgi, S. (2023).
- Description: Similar to WASSA-21, records were also essays written after reading an article but the data were annotated as multi-labeled with Ekman plus neutral, hope. The new task in 2023 also provided conversations between the study participants after they wrote their essays: the data was first presented in (Omitaomu, 2022).
- We were able to obtain the training and development sets from the organizers, but not the test set, as they are still working on improving the test set. https://codalab.lisn.upsaclay.fr/competitions/11167

**XED** 
- Authors: Öhman, E., Piotrowski, M., & Hämäläinen, M. (2023).
- Description: used an existing corpus of movie subtitles called OPUS, in English and Finnish.
- Labels: Plutchik plus neutral by university students (with some annotations provided by experts). The data was projected on multiple languages using human translations, resulting in 32 languages total.
- https://github.com/Helsinki-NLP/XED
