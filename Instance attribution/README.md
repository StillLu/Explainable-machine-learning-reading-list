

## IF models

Review: [Exit Through the Training Data: A Look into Instance-Attribution Explanations and Efficient Data Deletion in Machine Learning](https://www.cs.uoregon.edu/Reports/AREA-202009-Brophy.pdf)

1. [Understanding Black-box Predictions via Influence Functions](https://arxiv.org/pdf/1703.04730.pdf) International Conference on Machine Learning. PMLR, 2017.

2. [RelatIF: Identifying Explanatory Training Examples via Relative Influence](https://arxiv.org/pdf/2003.11630.pdf) International Conference on Artificial Intelligence and Statistics. PMLR, 2020.

3. [HYDRA: Hypergradient Data Relevance Analysis for Interpreting Deep Neural Networks](https://www.aaai.org/AAAI21Papers/AAAI-8686.ChenY.pdf) arXiv preprint arXiv:2102.02515 (2021).


4. [Identifying a Training-Set Attack’s Target Using Renormalized Influence Estimation](https://arxiv.org/pdf/2201.10055.pdf)  2022

5. [Estimating Training Data Influence by Tracing Gradient Descent](https://arxiv.org/abs/2002.08484) arXiv preprint arXiv:2002.08484 (2020).

6. [Input Similarity from the Neural Network Perspective](https://papers.nips.cc/paper/2019/file/c61f571dbd2fb949d3fe5ae1608dd48b-Paper.pdf) NeurIPS 2019-33th Annual Conference on Neural Information Processing Systems. 2019.
7. [Representer Point Selection for Explaining Deep Neural Networks](https://arxiv.org/abs/1811.09720) Advances in neural information processing systems 31 (2018).
8. [Understanding Instance-based Interpretability of Variational Auto-Encoders](https://arxiv.org/pdf/2105.14203.pdf) Advances in Neural Information Processing Systems 34 (2021).

<!---
 ## Evaluation metric (compared with leave-one-out)
   
1. data shapley value : [What is your data worth? Equitable Valuation of Data](https://arxiv.org/pdf/1904.02868.pdf)In International Conference on Machine Learning, pages 2242–2251. PMLR, 2019.
2. self-influence score: **IF models** ref.7 and ref.8 

-->

                         






## Empirical study
1. [Influence Functions in Deep Learning Are Fragile.](https://arxiv.org/pdf/2006.14651.pdf) arXiv preprint arXiv:2006.14651 (2020).

2. [Rethinking Influence Functions of Neural Networks in the Over-parameterized Regime](https://arxiv.org/pdf/2112.08297.pdf) arXiv preprint arXiv:2112.08297 (2021) 

3. [Characterizations of an empirical influence function for detecting influential cases in regression](https://www.jstor.org/stable/pdf/1268187.pdf?casa_token=9iGR59KbaKsAAAAA:ufXjpJ_eH4xnv84VbyAxPS6Lb9g3Dq_6GDXDM69DQlKRm4-lgCKhcVaZsI_b69AmooaM4O4wpMarAHgOwHpK0VVkdJ3HxoVB7yVomJ-TaPoVZ1EnPP-U) Technometrics 22.4 (1980): 495-508.  

4. [Revisiting Methods for Finding Influential Examples](https://arxiv.org/pdf/2111.04683.pdf) arXiv preprint arXiv:2111.04683 (2021)

5. [EVALUATION OF SIMILARITY-BASED EXPLANATIONS](https://arxiv.org/pdf/2006.04528.pdf) arXiv preprint arXiv:2006.04528 (2020)
6. [FIRST IS BETTER THAN LAST FOR TRAINING DATA INFLUENCE](https://arxiv.org/pdf/2202.11844.pdf) arXiv preprint arXiv:2202.11844 (2022). ** (the influence of freezing specific layers of bert)




## Application
1. [An Empirical Comparison of Instance Attribution Methods for NLP](https://aclanthology.org/2021.naacl-main.75.pdf) arXiv preprint arXiv:2104.04128 (2021).
2. [Explaining Black Box Predictions and Unveiling Data Artifacts through Influence Functions](https://arxiv.org/pdf/2005.06676.pdf) arXiv preprint arXiv:2005.06676 (2020)
**supplementary:**
   [Right for the Wrong Reasons: Diagnosing Syntactic Heuristics in Natural Language Inference](https://aclanthology.org/P19-1334.pdf) arXiv preprint arXiv:1902.01007 (2019).

3. [Combining Feature and Instance Attribution to Detect Artifacts](https://arxiv.org/pdf/2107.00323.pdf) arXiv preprint arXiv:2107.00323 (2021).

4. [Influence Tuning: Demoting Spurious Correlations via Instance Attribution and Instance-Driven Updates](https://arxiv.org/pdf/2110.03212.pdf) arXiv preprint arXiv:2110.03212 (2021).

5. [Interactive Label Cleaning with Example-based Explanations](https://proceedings.neurips.cc/paper/2021/file/6c349155b122aa8ad5c877007e05f24f-Paper.pdf) Advances in Neural Information Processing Systems 34 (2021).

6. [Detecting Adversarial Samples Using Influence Functions and Nearest Neighbors](https://openaccess.thecvf.com/content_CVPR_2020/papers/Cohen_Detecting_Adversarial_Samples_Using_Influence_Functions_and_Nearest_Neighbors_CVPR_2020_paper.pdf) Proceedings of the IEEE/CVF conference on computer vision and pattern recognition. 2020.


### Explanation Methods for NLP
#### Instance level
1. [On Sample Based Explanation Methods for NLP: Efficiency, Faithfulness, and Semantic Evaluation](https://aclanthology.org/2021.acl-long.419.pdf) arXiv preprint arXiv:2106.04753 (2021).
2. [Pair the Dots: Jointly Examining Training History and Test Stimuli for Model Interpretability](https://arxiv.org/pdf/2010.06943.pdf) arXiv preprint arXiv:2010.06943 (2020).

#### Feature level
1. [Gradient-based Analysis of NLP Models is Manipulable](https://arxiv.org/pdf/2010.05419.pdf) arXiv preprint arXiv:2010.05419 (2020).
2. [HotFlip: White-Box Adversarial Examples for Text Classification](https://arxiv.org/abs/1712.06751) arXiv preprint arXiv:1712.06751 (2017).





## Optimization
1. Second-Order Stochastic Optimization for Machine Learning in Linear Time.
2. [Learning with Bad Training Data via Iterative Trimmed Loss Minimization.](https://arxiv.org/pdf/1810.11874.pdf) International Conference on Machine Learning. PMLR, 2019.


## About XAI
1. [Towards Faithfully Interpretable NLP Systems: How should we define and evaluate faithfulness?](https://arxiv.org/pdf/2004.03685.pdf) arXiv preprint arXiv:2004.03685 (2020).
2. [Pathologies of Neural Models Make Interpretations Difficult](https://arxiv.org/pdf/1804.07781.pdf) arXiv preprint arXiv:1804.07781 (2018).
3. [Teach Me to Explain: A Review of Datasets for Explainable Natural Language Processing](https://openreview.net/pdf?id=ogNcxJn32BZ) Thirty-fifth Conference on Neural Information Processing Systems Datasets and Benchmarks Track (Round 1). 2021.

