# Replication Package for paper 'An Empirical Study of Self-Consistency and Confidence Elicitation in LLM-Based Pointwise Re-Ranking'


This directory contains the replication materials and results for three datasets used in this paper:

- **dl19**  
- **dl20**  
- **touche**

Each dataset folder has two subfolders, **RQ1** and **RQ2**, corresponding to the two research questions addressed in the study.

---

## Model and Prompting Strategy

We used the **[mistralai/Mixtral-8x7B-Instruct-v0.1]** ([https://huggingface.co/mistralai/Mixtral-8x7B-Instruct-v0.1]) for all experiments.  

We designed our prompt bassed on the fine-grained relevance labels in the pointwise approach [1], Self-consistency [2] and Confidence Elicitation [3].  

For details about the exact prompting strategy used in this work, please see the paper.

---

## RQ1 Folder

Within the **RQ1** folder of each dataset, you will find:

- One CSV file and one JSON file for **each** temperature setting.  
- These files contain the experimental outcomes for **RQ1** at the specified temperature levels.

---

## RQ2 Folder

Within the **RQ2** folder of each dataset, there are two subfolders:

1. **diff_temp**  
2. **one_temp**

Each of these subfolders contains three additional folders, one for each of the **aggregation methods** considered in RQ2. 


---

## References

[1] Zhuang, H., Qin, Z., Hui, K., Wu, J., Yan, L., Wang, X., & Bendersky, M. (2024). Beyond Yes and No: Improving Zero-Shot Pointwise LLM Rankers via Scoring Fine-Grained Relevance Labels. In Proceedings of the 2024 Conference of the North American Chapter of the Association for Computational Linguistics (NAACL).

[2] Wang, Xuezhi, Jason Wei, Dale Schuurmans, Quoc Le, Ed Chi, Sharan Narang, Aakanksha Chowdhery, and Denny Zhou. "Self-consistency improves chain of thought reasoning in language models." arXiv preprint arXiv:2203.11171 (2022).

[3] Xiong, Miao, Zhiyuan Hu, Xinyang Lu, Yifei Li, Jie Fu, Junxian He, and Bryan Hooi. "Can llms express their uncertainty? an empirical evaluation of confidence elicitation in llms." arXiv preprint arXiv:2306.13063 (2023).





