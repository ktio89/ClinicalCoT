# Clinical_CoT
Official Repo for the paper "Large Language Models are Clinical Reasoners: Reasoning-Aware Diagnosis Framework with Prompt-Generated Rationales"
Paper link: [https://arxiv.org/abs/2312.07399](https://arxiv.org/abs/2312.07399)

# This repo provides ...
This repo contains the 2 few-shot clinical chain-of-thought exemplars created together by humans and machines (2 licensed radiologists and GPT-4).
These shots are used to prompt the LLMs to *generate clinical rationales* that link the provided patient information (e.g., EHR) to the final diagnosis of Alzheimer's disease (AD, MCI, or NC).
Specifically, these are used in our *Module I: Clinical Rationalization* and *Module II-1: Few-shot CoT Reasoning*.

# One can use these exemplars to ...
Researchers can utilize our expert-provided exemplars to guide the CoT reasoning in AD diagnosis with LLMs.
This can serve as a strong baseline for comparison.
The use of these exemplars should be *only for educational purposes*. 

# Citation
If you applied our exemplars in your work, please use the following BibTeX to cite our paper:
```
@inproceedings{kwon2024large,
  title={Large Language Models Are Clinical Reasoners: Reasoning-Aware Diagnosis Framework with Prompt-Generated Rationales},
  author={Kwon, Taeyoon and Ong, Kai Tzu-iunn and Kang, Dongjin and Moon, Seungjun and Lee, Jeong Ryong and Hwang, Dosik and Sohn, Beomseok and Sim, Yongsik and Lee, Dongha and Yeo, Jinyoung},
  booktitle={Proceedings of the AAAI Conference on Artificial Intelligence},
  volume={38},
  number={16},
  pages={18417--18425},
  year={2024}
}
```
