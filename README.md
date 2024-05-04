# ESLTTS

The full paper can be accessed here: [arXiv](https://arxiv.org/abs/2404.18094), [IEEE Xplore](https://ieeexplore.ieee.org/document/10508477).

## Abstract

With the progress made in speaker-adaptive TTS approaches, advanced approaches have shown a remarkable capacity to reproduce the speaker’s voice in the commonly used TTS datasets. However, mimicking voices characterized by substantial accents, such as non-native English speakers, is still challenging.  Regrettably, the absence of a dedicated TTS dataset for speakers with substantial accents inhibits the research and evaluation of speaker-adaptive TTS models under such conditions. To address this gap, we developed a corpus of non-native speakers' English utterances.

We named this corpus “English as a Second Language TTS dataset ” (ESLTTS). The ESLTTS dataset consists of roughly 37 hours of 42,000 utterances from 134 non-native English speakers. These speakers represent a diversity of linguistic backgrounds spanning 31 native languages. For each speaker, the dataset includes an adaptation set lasting about 5 minutes for speaker adaptation, a test set comprising 10 utterances for speaker-adaptive TTS evaluation, and a development set for further research.

## Dataset Structure

```
ESLTTS Dataset/
├─ Malayalam_3/     ------------ {Speaker Native Language}_{Speaker id}
│  ├─ ada_1.flac    ------------ {Subset Name}_{Utterance id}
│  ├─ ada_1.txt     ------------ Transcription for "ada_1.flac"
│  ├─ test_1.flac   ------------ {Subset Name}_{Utterance id}
│  ├─ test_1.txt    ------------ Transcription for "test_1.flac"
│  ├─ dev_1.flac    ------------ {Subset Name}_{Utterance id}
│  ├─ dev_1.txt     ------------ Transcription for "dev_1.flac"
│  ├─ ...
├─ Arabic_3/        ------------ {Speaker Native Language}_{Speaker id}
│  ├─ ada_1.flac    ------------ {Subset Name}_{Utterance id}
│  ├─ ...
├─ ...
```

## Online Access
You can access this dataset through [Google Driver](https://drive.google.com/file/d/1ChQ_z-TxvKWNUbUMWnbyjM2VY3v2SKEi/view?usp=sharing) or [IEEE Dataport](http://ieee-dataport.org/documents/english-second-language-tts-esltts-dataset).

## Citation
```
@ARTICLE{10508477,
  author={Wang, Wenbin and Song, Yang and Jha, Sanjay},
  journal={IEEE/ACM Transactions on Audio, Speech, and Language Processing}, 
  title={USAT: A Universal Speaker-Adaptive Text-to-Speech Approach}, 
  year={2024},
  volume={},
  number={},
  pages={1-15},
  keywords={Adaptation models;Training;Hidden Markov models;Timbre;Cloning;Speech enhancement;Navigation;Text-to-speech;speaker-adaptive;zero-shot learning;few-shot learning},
  doi={10.1109/TASLP.2024.3393714}}

```
