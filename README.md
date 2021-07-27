# Speech To Text on Amazon Transcribe

### Agenda
0. [Data Source Configuration](docs/DataSource.md)
1. [Speech-to-text on Amazon Transcribe](docs/Transcribe.md)
2. [Using Custom Vocabulary on Amazon Transcribe](docs/CustomVocab.md)
3. [Using Vocabulary Filtering on Amazon Transcribe](docs/VocabFilter.md)
4. [Using Speaker Identification (speaker diarization) on Amazon Transcribe](docs/SpeakerIdentify.md)
5. [Improving Speech-to-text Machine Learning using A2I (Augmented Intelligence)](docs/A2I.md)

### Scope of Project
1. Tutorial is using Singapore region, and focusing on AWS Transcribe
2. For A2I, the project is using private workforce. There are 3 ways to achieve this (Mechanical Turk, Private, or Vendor)
3. to do Speech-to-text on SageMaker, I recommend to use DeepSpeech (More description for [DeepSpeech is Here](https://deepspeech.readthedocs.io/en/r0.9/?badge=latest)).
4. to create custom vocabulary and Vocabulary Filtering, please use txt file. Mac users are recommended to use `TextEdit` and use plain text format (Format > Make Plain Text)

### Dataset Resources
* [Indonesian Speech](https://commonvoice.mozilla.org/en/datasets)
* [Indonesian 2 Speakers - KickAndy YouTube](https://youtube.com/watch?v=nVYxJjlFhno)
* [Indonesian Swear Words](https://github.com/abhimantramb/elang/blob/master/word2vec/utils/swear-words.txt)
