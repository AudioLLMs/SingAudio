# Advancing Singlish Understanding: Bridging the Gap with Datasets and Multimodal Models

[Paper 2025](https://arxiv.org/abs/2501.01034), [Datasets](https://huggingface.co/datasets/MERaLiON/Multitask-National-Speech-Corpus-v1)

## Overview

Singlish, a Creole language rooted in English, is prominent in Singapore's multilingual and multicultural landscape. Despite its widespread use, the spoken form of Singlish remains underexplored, limiting insights into its linguistic structure and applications. This project addresses this gap by standardizing and annotating the largest spoken Singlish corpus from National Speech Corpus.

The original National Speech Corpus is consisted of 10k hours of speech and transcriptions. In our first release, we reorganized and released the high quality ones and extended to multitask datasets and standard train/test split.

## Multitask National Speech Corpus (MNSC)

The **MNSC** is a comprehensive dataset supporting various tasks:

- **Automatic Speech Recognition (ASR):** Transcribing spoken Singlish into text.
- **Spoken Question Answering (SQA):** Answering questions based on spoken content.
- **Spoken Dialogue Summarization (SDS):** Summarizing spoken dialogues.
- **Paralinguistic Question Answering (PQA):** Analyzing paralinguistic features like accent and gender.

The dataset includes standardized splits and a human-verified test set to facilitate research and benchmarking. It is available at [MNSC-V1-Huggingface](https://huggingface.co/datasets/MERaLiON/Multitask-National-Speech-Corpus-v1).


## Other Singlish Corpus

- [SEAME 2015](https://catalog.ldc.upenn.edu/LDC2015S04)


# Citation
If you found our resource useful, please consider cite our work:
```
@article{wang2025advancing,
  title={Advancing Singlish Understanding: Bridging the Gap with Datasets and Multimodal Models},
  author={Wang, Bin and Zou, Xunlong and Sun, Shuo and Zhang, Wenyu and He, Yingxu and Liu, Zhuohan and Wei, Chengwei and Chen, Nancy F and Aw, AiTi},
  journal={arXiv preprint arXiv:2501.01034},
  year={2025}
}
```