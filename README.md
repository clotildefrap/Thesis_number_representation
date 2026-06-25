# Thesis_number_representation

In this repository, you will find all the codes, results, and plots related to the work completed for my thesis on the influence of the methodological choices on the results of the analyses on the geometry of numerical representations in the semantic spaces of Large Language Models. We focus particularly on the influence of dimensionality reduction techniques (DRTs) and on linear vs. non-linear probes.

The 'Replication' folder contains all the materials related to the Replication of Shah et al.,'study (2023) and the the results of the statistical tests conducted to quantify the divergences between our results and the results from the original paper.

The 'Experiment_1' folder contains all the materials used and produces by our first experiment which consisted in extending the Shah et al.,'s experiments to larger magnitudes (up to N = 500) and to start the investigations on DRTs by swapping MDS for PCA in the otherwise identical pipeline.

The 'Experiment_2' folder contains all the materials used and produces by our second experiment which introduced our own comparative framework. In this study we test five number ranges (N = 9, 50, 100, 500, 1000), four DRTs (MDS, PCa, UMAP, and t-SNE), four models (ELMo, BERT, RoBERTa, and GPT-2), and analyse the spacing patterns in  the orignal spaces of the models, the correlations between reduced embeddings and functional fits (linear, log, square root, Power-Law, and Exponential), the mononicity of the embedding arrangements, the preservation of the original space by the DRTs. We then quantify the divergences between DRTs and attempt to decipher whether a particular scale arise consistently.

The 'Experiment_3' folder contains all the materials used and produces by our third experiment which consisted training and testing linear and non-linear probes on different data splits to evaluate their accuracies, the differences i performance between them, and whether they were able to learn numerical representations beyond their training split.

The 'Prompting_task' folder contains all the materials used and produces by the additional task we conducted to start investigating whether the behavioural performance of the odels corresponded to their internal structure.

