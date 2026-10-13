# Large Language Models – Text Analysis and Generation in the Era of Generative AI

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)
![Type: Research paper](https://img.shields.io/badge/type-research%20paper-blue)
![Year: 2024](https://img.shields.io/badge/year-2024-informational)

A 13-page research paper on how Large Language Models (LLMs) work, where they are used in the DACH region and what it takes to adapt them to Swiss education and Swiss German.

**[Read the paper (PDF)](AFE1_LLM_Paper.pdf)**

---

## Research question

> *How can Large Language Models be effectively adapted to the specific needs of the education sector in a German-speaking context and used to enhance learning processes?*

## Context

| | |
|---|---|
| **Institution** | Lucerne University of Applied Sciences and Arts (HSLU) & Swiss Distance University of Applied Sciences (FFHS) |
| **Module** | AFE1 – Applied Research and Development, Master's level |
| **Semester** | Spring 2024 (submitted June 2024) |
| **Method** | Literature review and an expert interview with the founder of the German education LLM *educa AI* |
| **Authors** | Seraina Fischer, Bigna Schmid, Annamária Sréter |
| **My contribution** | Co-author of the paper and participant in the expert interview with *educa AI* |

## What the paper covers

1. **Technical foundations:** NLP, NLU and NLG, the transformer architecture and parameter-efficient fine-tuning with **LoRA**.
2. **State-of-the-art models:** open-source LLMs (e.g. LLaMA, Mistral), small language models (e.g. Phi-3) and Swiss LLM initiatives.
3. **Key people:** researchers who shaped the field, from Turing and Weizenbaum to Hinton and Karpathy.
4. **Applications in the DACH region**, in four sectors:

   | Sector | Examples discussed |
   |---|---|
   | Education | educa AI, Syntea |
   | Law | Noxtua (CMS), SwissLLM |
   | Customer service | Spitch |
   | Swiss German | Whisper-based speech recognition, Swiss German translation systems |

5. **Challenges:** bias, hallucinations and misinformation, transparency, privacy and the effects on the job market.

## Key findings

- **Educational LLMs need context-based answers.** Generic responses often do not match the material a teacher actually covers.
- **German and Swiss German add language-specific difficulties.** Dialects without a standard spelling are low-resource languages and need dedicated data and models.
- **The Swiss market has high potential and little competition.** The paper recommends that providers work with Swiss universities to tailor models to local languages and use cases.
- **Responsible deployment is essential.** That means fairness, transparency and data protection.

## Follow-up work

The paper is the first phase of a two-phase project. In the second phase the team trained a text-generation model on Bernese Swiss German song lyrics:
[swiss-german-lyrics-generator](https://github.com/sreterannamaria/swiss-german-lyrics-generator)

## Repository structure

```
├── AFE1_LLM_Paper.pdf   # Full paper (13 pages)
└── README.md
```

## Citation

```bibtex
@techreport{fischer2024llm,
  title       = {Large Language Models -- Text Analysis and Generation in the Era of Generative AI},
  author      = {Fischer, Seraina and Schmid, Bigna and Sr{\'e}ter, Annam{\'a}ria},
  institution = {Lucerne University of Applied Sciences and Arts (HSLU) and FFHS},
  type        = {Applied research paper (AFE1)},
  year        = {2024}
}
```

## Acknowledgments

Thanks to Benjamin Ledel (Digital Learning GmbH, *educa AI*) for the expert interview.

## License

This work is licensed under [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/). You may share and adapt it for non-commercial purposes with appropriate credit.
