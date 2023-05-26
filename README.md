# Alzheimer's Disease Classification
This repository contains the code for the INTERSPEECH2023 paper: "Alzheimer Disease Classification through ASR-based Transcriptions: Exploring the Impact of Punctuation and Pauses"

**Abstract:**

Alzheimer’s Disease (AD) is the world’s leading neurodegenerative disease, which often results in communication difficulties. Analysing speech can serve as a diagnostic tool for identifying the condition. The recent ADReSS challenge provided a dataset for AD classification and highlighted the utility of manual tran-
scriptions. In this study, we used the new state-of-the-art Automatic Speech Recognition (ASR) model Whisper to obtain the transcriptions, which also include automatic punctuation. The classification models achieved test accuracy scores of 0.854 and 0.833 combining the pretrained FastText word embeddings and recurrent neural networks on manual and ASR transcripts respectively. Additionally, we explored the influence of including pause information and punctuation in the transcriptions. We found that punctuation only yielded minor improvements in some cases, whereas pause encoding aided AD classification for both manual and ASR transcriptions across all approaches investigated

## Files and folders
* data: description of the ADReSS Challenge data, and instructions on how to obtain it.
* code.ipynb: jupyter notebook with the code used to train the models.
* requirements.txt: required packages to be installed.

## Citation
If you find this work helpful, please cite our work: 

        @inproceedings{gomez2023AD,
            title={Alzheimer Disease Classification through ASR-based Transcriptions: Exploring the Impact of Punctuation and Pauses},
            author={Gómez-Zaragozá, Lucia and Wills, Simone and Tejedor-Garcia, Cristian and Marín-Morales, Javier and Alcañiz, Mariano and Strik, Helmer},
            booktitle={INTERSPEECH},
            year={2023}
        }
