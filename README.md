# Learning-with-Noisy-Labels

    A curated list of most recent papers & codes in Learning with Noisy Labels

---

- Content
  - [Benchmarks & Leaderboard](#benchmarks--leaderboard)
  - [Papers & Code in 2021](#papers--code-in-2021)
    - [NeurIPS 2021](#NeurIPS-2021)
    - [IJCAI 2021](#IJCAI-2021)
    - [ICML 2021](#ICML-2021)
    - [ICLR 2021](#ICLR-2021)
    - [CVPR 2021](#CVPR-2021)
    - [AISTATS 2021](#AISTATS-2021)
    - [AAAI 2021](#AAAI-2021)
    - [Other Conferences 2021](#Other-Conferences-2021)
    - [ArXiv 2021](#ArXiv-2021)
  - [Papers & Code in 2020](#papers--code-in-2020)
    - [ICML 2020](#ICML-2020)
    - [ICLR 2020](#ICLR-2020)
    - [Nips 2020](#Nips-2020)
    - [AAAI 2020](#AAAI-2020)
    - [CVPR 2020](#CVPR-2020)
    - [ECCV 2020](#ECCV-2020)
    - [ArXiv 2020](#ArXiv-2020)
---

## Benchmarks & Leaderboard
Real-world noisy-label bechmarks:

Dataset | Leaderboard Link | Website | Paper
--- | --- | --- | ---
CIFAR-10N | [[Leaderboard]](http://noisylabels.com/) | [[Website]](http://noisylabels.com/) | [[Paper]](https://arxiv.org/abs/2110.12088) 
CIFAR-100N | [[Leaderboard]](http://noisylabels.com/) | [[Website]](http://noisylabels.com/)  | [[Paper]](https://arxiv.org/abs/2110.12088)
Red Stanford Cars | N/A | [[Website]](https://ai.googleblog.com/2020/08/understanding-deep-learning-on.html)  | [[Paper]](http://proceedings.mlr.press/v119/jiang20c/jiang20c.pdf)
Red Mini-ImageNet | N/A | [[Website]](https://ai.googleblog.com/2020/08/understanding-deep-learning-on.html)  | [[Paper]](http://proceedings.mlr.press/v119/jiang20c/jiang20c.pdf)
 Animal-10N | [[Leaderboard]](https://paperswithcode.com/dataset/animal) | [[Website]](https://dm.kaist.ac.kr/datasets/animal-10n/)  | [[Paper]](http://proceedings.mlr.press/v97/song19b.html)
 Food-101N | N/A| [[Website]](https://github.com/kuanghuei/clean-net)  | [[Paper]](https://arxiv.org/pdf/1711.07131.pdf)
 Clothing1M  | [[Leaderboard]](https://paperswithcode.com/dataset/clothing1m) | [[Website]](https://github.com/Cysu/noisy_label)  | [[Paper]](https://openaccess.thecvf.com/content_cvpr_2015/papers/Xiao_Learning_From_Massive_2015_CVPR_paper.pdf)
 
 Simulation of label noise:
 An Instance-Dependent Simulation Framework for Learning with Label Noise. [[Paper]](https://arxiv.org/abs/2107.11413)


## Papers & Code in 2021

This repo focus on papers after 2019, for previous works, please refer to (https://github.com/subeeshvasu/Awesome-Learning-with-Label-Noise).

### NeurIPS 2021 
Conference date:  
* [[**UCSC REAL Lab**]](https://github.com/UCSC-REAL) Can Less be More? When Increasing-to-Balancing Label Noise Rates Considered Beneficial. [[Paper]](https://arxiv.org/abs/2107.05913#:~:text=We%20are%20primarily%20inspired%20by,fairness%20guarantees%20against%20label%20bias.)[[Code]](https://github.com/UCSC-REAL/CanLessBeMore)
* Open-set Label Noise Can Improve Robustness Against Inherent Label Noise. [[Paper]](https://arxiv.org/abs/2106.10891)[[Code]](https://github.com/hongxin001/ODNL)
* Generalized Jensen-Shannon Divergence Loss for Learning with Noisy Labels. [[Paper]](https://arxiv.org/abs/2105.04522)[[Code]](https://github.com/ErikEnglesson/GJS)
* Understanding and Improving Early Stopping for Learning with Noisy Labels. [[Paper]](https://arxiv.org/abs/2106.15853)[[Code]](https://github.com/tmllab/PES)
* How does a Neural Network's Architecture Impact its Robustness to Noisy Labels? [[Paper]](https://openreview.net/forum?id=Ir-WwGboFN-)[[Code]](https://github.com/jinglingli/alignment_noisy_label)
* FINE Samples for Learning with Noisy Labels. [[Paper]](https://arxiv.org/pdf/2102.11628v3.pdf)[[Code]](https://github.com/Kthyeon/FINE_official)
* Label Noise SGD Provably Prefers Flat Global Minimizers. [[Paper]](https://arxiv.org/abs/2106.06530)[[Code]](https://github.com/adamian98/LabelNoiseFlatMinimizers)
* Improved Regularization and Robustness for Fine-tuning in Neural Networks. [[Paper]](https://openreview.net/forum?id=QX32YlxrQJc)[[Code]](https://github.com/NEU-StatsML-Research/Regularized-Self-Labeling)
* Instance-dependent Label-noise Learning under a Structural Causal Model. [[Paper]](https://arxiv.org/abs/2109.02986)
* Combating Noise: Semi-supervised Learning by Region Uncertainty Quantification. [[Paper]](https://arxiv.org/abs/2111.00928)
* DP-SSL: Towards Robust Semi-supervised Learning with A Few Labeled Samples. [[Paper]](https://arxiv.org/abs/2110.13740)
* Corruption Robust Active Learning. [[Paper]](https://openreview.net/forum?id=Ruw3MHL9jAO)

-----

### IJCAI 2021 

* Learning Implicitly with Noisy Data in Linear Arithmetic. [[Paper]](https://www.ijcai.org/proceedings/2021/0195.pdf)
* Towards Understanding Deep Learning from Noisy Labels with Small-Loss Criterion. [[Paper]](https://www.ijcai.org/proceedings/2021/0340.pdf)
* Modeling Noisy Hierarchical Types in Fine-Grained Entity Typing: A Content-Based Weighting Approach. [[Paper]](https://www.ijcai.org/proceedings/2019/0731.pdf) 
* Multi-level Generative Models for Partial Label Learning with Non-random Label Noise. [[Paper]](https://www.ijcai.org/proceedings/2021/0449.pdf)
-----

### ICML 2021
Conference date: Jul 18, 2021 -- Jul 24, 2021

* [[**UCSC REAL Lab**]](https://github.com/UCSC-REAL) The importance of understanding instance-level noisy labels. [[Paper]](https://arxiv.org/pdf/2102.05336.pdf)
* [[**UCSC REAL Lab**]](https://github.com/UCSC-REAL) Clusterability as an Alternative to Anchor Points When Learning with Noisy Labels. [[Paper]](https://arxiv.org/pdf/2102.05291.pdf)[[Code]](https://github.com/zwzhu-d/HOC)
* Scaling Up Visual and Vision-Language Representation Learning With Noisy Text Supervision. [[Paper]](https://arxiv.org/pdf/2102.05918v2.pdf)[[Code]](https://github.com/MicPie/clasp)
* Learning Noise Transition Matrix from Only Noisy Labels via Total Variation Regularization. [[Paper]](https://arxiv.org/pdf/2102.02414v2.pdf)[[Code]](https://github.com/YivanZhang/lio)
* Class2Simi: A Noise Reduction Perspective on Learning with Noisy Labels. [[Paper]](https://arxiv.org/abs/2006.07831)
* Provably End-to-end Label-noise Learning without Anchor Points. [[Paper]](https://arxiv.org/pdf/2102.02400.pdf)
* Asymmetric Loss Functions for Learning with Noisy Labels. [[Paper]](https://arxiv.org/pdf/2106.03110v1.pdf)[[Code]](https://github.com/hitcszx/ALFs)
* Confidence Scores Make Instance-dependent Label-noise Learning Possible. [[Paper]](https://arxiv.org/abs/2001.03772) 
* Provable Generalization of SGD-trained Neural Networks of Any Width in the Presence of Adversarial Label Noise. [[Paper]](https://arxiv.org/abs/2101.01152)
* Wasserstein Distributional Normalization For Robust Distributional Certification of Noisy Labeled Data. [[Paper]](http://proceedings.mlr.press/v139/park21a/park21a.pdf)
* Learning from Noisy Labels with No Change to the Training Process. [[Paper]](http://proceedings.mlr.press/v139/zhang21k/zhang21k.pdf)
-----
### ICLR 2021

* [[**UCSC REAL Lab**]](https://github.com/UCSC-REAL) When Optimizing f-Divergence is Robust with Label Noise. [[Paper]](https://openreview.net/pdf?id=WesiCoRVQ15)[[Code]](https://github.com/weijiaheng/Robust-f-divergence-measures) 
* [[**UCSC REAL Lab**]](https://github.com/UCSC-REAL) Learning with Instance-Dependent Label Noise: A Sample Sieve Approach. [[Paper]](https://openreview.net/pdf?id=2VXyy9mIyU3)[[Code]](https://github.com/haochenglouis/cores) 
* Noise against noise: stochastic label noise helps combat inherent label noise. [[Paper]](https://openreview.net/pdf?id=80FMcTSZ6J0)[[Code]](https://github.com/chenpf1025/SLN)
* Learning with Feature-Dependent Label Noise: A Progressive Approach. [[Paper]](https://openreview.net/pdf?id=ZPa2SyGcbwh)[[Code]](https://github.com/pxiangwu/PLC)
* Robust early-learning: Hindering the memorization of noisy labels. [[Paper]](https://openreview.net/pdf?id=Eql5b1_hTE4)[[Code]](https://github.com/xiaoboxia/CDR)
* MoPro: Webly Supervised Learning with Momentum Prototypes. [[Paper]](https://openreview.net/forum?id=0-EYBhgw80y) [[Code]](https://github.com/salesforce/MoPro) 
* Robust Curriculum Learning: from clean label detection to noisy label self-correction. [[Paper]](https://openreview.net/pdf?id=lmTWnm3coJJ)
* How Does Mixup Help With Robustness and Generalization? [[Paper]](https://openreview.net/pdf?id=8yKEo06dKNo)
* Theoretical Analysis of Self-Training with Deep Networks on Unlabeled Data. [[Paper]](https://openreview.net/pdf?id=rC8sJ4i6kaH)
-----
### CVPR 2021
Conference date: Jun 19, 2021 -- Jun 25, 2021

* [[**UCSC REAL Lab**]](https://github.com/UCSC-REAL) A Second-Order Approach to Learning with Instance-Dependent Label Noise. [[Paper]](https://arxiv.org/abs/2012.11854)[[Code]](https://github.com/UCSC-REAL/CAL)
* Improving Unsupervised Image Clustering With Robust Learning. [[Paper]](https://arxiv.org/abs/2012.11150)
* Multi-Objective Interpolation Training for Robustness to Label Noise. [[Paper]](https://arxiv.org/abs/2012.04462)[[Code]](https://git.io/JI40X)
* Noise-resistant Deep Metric Learning with Ranking-based Instance Selection. [[Paper]](https://arxiv.org/abs/2103.16047)[[Code]](https://github.com/alibaba-edu/Ranking-based-Instance-Selection)
* Augmentation Strategies for Learning with Noisy Labels. [[Paper]](https://arxiv.org/abs/2103.02130)[[Code]](https://github.com/KentoNishi/Augmentation-for-LNL)
* Jo-SRC: A Contrastive Approach for Combating Noisy Labels. [[Paper]](https://arxiv.org/pdf/2103.13029.pdf)[[Code]](https://github.com/NUST-Machine-Intelligence-Laboratory/Jo-SRC)
* Multi-Objective Interpolation Training for Robustness to Label Noise. [[Paper]](https://arxiv.org/abs/2012.04462)[[Code]](https://github.com/DiegoOrtego/LabelNoiseMOIT)
* Partially View-aligned Representation Learning with Noise-robust Contrastive Loss. [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Yang_Partially_View-Aligned_Representation_Learning_With_Noise-Robust_Contrastive_Loss_CVPR_2021_paper.pdf)[[Code]](https://github.com/XLearning-SCU/2021-CVPR-MvCLN)
* Correlated Input-Dependent Label Noise in Large-Scale Image Classification. [[Paper]](https://arxiv.org/abs/2105.10305)
* DAT: Training Deep Networks Robust To Label-Noise by Matching the Feature Distributions.[[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Qu_DAT_Training_Deep_Networks_Robust_To_Label-Noise_by_Matching_the_CVPR_2021_paper.pdf)
* Faster Meta Update Strategy for Noise-Robust Deep Learning. [[Paper]](https://github.com/youjiangxu/FaMUS/tree/main/paper)[[Code]](https://github.com/youjiangxu/FaMUS)
* DualGraph: A graph-based method for reasoning about label noise. [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_DualGraph_A_Graph-Based_Method_for_Reasoning_About_Label_Noise_CVPR_2021_paper.pdf)
* Background-Aware Pooling and Noise-Aware Loss for Weakly-Supervised Semantic Segmentation. [[Paper]](https://arxiv.org/abs/2104.00905)
* Joint Negative and Positive Learning for Noisy Labels. [[Paper]](https://arxiv.org/abs/2104.06574)
* Faster Meta Update Strategy for Noise-Robust Deep Learning. [[Paper]](https://arxiv.org/abs/2104.15092)
* AutoDO: Robust AutoAugment for Biased Data with Label Noise via Scalable Probabilistic Implicit Differentiation. [[Paper]](https://arxiv.org/abs/2103.05863)[[Code]](https://github.com/gudovskiy/autodo)
* Meta Pseudo Labels. [[Paper]](https://arxiv.org/pdf/2003.10580.pdf)[[Code]](https://github.com/google-research/google-research/tree/master/meta_pseudo_labels)
* All Labels Are Not Created Equal: Enhancing Semi-supervision via Label Grouping and Co-training. [[Paper]](https://arxiv.org/abs/2104.05248)[[Code]](https://github.com/islam-nassar/semco)
* SimPLE: Similar Pseudo Label Exploitation for Semi-Supervised Classification. [[Paper]](https://arxiv.org/abs/2103.16725)[[Code]](https://github.com/zijian-hu/SimPLE)
-----
### AISTATS 2021
Conference date: Apr 13, 2021 -- Apr 15, 2021

* Collaborative Classification from Noisy Labels. [[Paper]](http://proceedings.mlr.press/v130/maystre21a.html)
* Linear Models are Robust Optimal Under Strategic Behavior. [[Paper]](http://proceedings.mlr.press/v130/tang21a.html)
-----
### AAAI 2021
* Beyond Class-Conditional Assumption: A Primary Attempt to Combat Instance-Dependent Label Noise. [[Paper]](https://arxiv.org/abs/2012.05458)[[Code]](https://github.com/chenpf1025/IDN)
* Learning to Purify Noisy Labels via Meta Soft Label Corrector. [[Paper]](https://arxiv.org/abs/2008.00627)[[Code]](https://github.com/WuYichen-97/Learning-to-Purify-Noisy-Labels-via-Meta-Soft-Label-Corrector)
* Robustness of Accuracy Metric and its Inspirations in Learning with Noisy Labels. [[Paper]](https://arxiv.org/abs/2012.04193)[[Code]](https://github.com/chenpf1025/RobustnessAccuracy)
* Learning from Noisy Labels with Complementary Loss Functions. [[Paper]](http://palm.seu.edu.cn/zhangml/files/AAAI'21a.pdf)[[Code]](https://github.com/dengbaowang/CompLossForNoisyLabels)
* Analysing the Noise Model Error for Realistic Noisy Label Data. [[Paper]](https://arxiv.org/abs/2101.09763)[[Code]](https://github.com/uds-lsv/noise-estimation)
* Tackling Instance-Dependent Label Noise via a Universal Probabilistic Model. [[Paper]](https://niug1984.github.io/paper/wang_aaai21.pdf)
* Learning with Group Noise. [[Paper]](https://gcatnjust.github.io/ChenGong/paper/wang_aaai21_2.pdf)
* Meta Label Correction for Noisy Label Learning. [[Paper]](https://www.microsoft.com/en-us/research/publication/meta-label-correction-for-noisy-label-learning/)
-----
### Other Conferences 2021
* (ICCV 2021) Learning with Noisy Labels for Robust Point Cloud Segmentation. [[Paper]](https://shuquanye.com/PNAL_website/)[[Code]](https://github.com/pleaseconnectwifi/PNAL)
* (ICCV 2021) Learning with Noisy Labels via Sparse Regularization. [[Paper]](https://arxiv.org/abs/2108.00192)
* (WACV 2022) Towards a Robust Differentiable Architecture Search under Label Noise. [[Paper]](https://arxiv.org/abs/2110.12197)
* (WACV 2022) Addressing out-of-distribution label noise in webly-labelled data. [[Paper]](https://arxiv.org/abs/2110.13699)[[Code]](https://github.com/PaulAlbert31/DSOS)
* (BMVC 2021) PropMix: Hard Sample Filtering and Proportional MixUp for Learning with Noisy Labels. [[Paper]](https://arxiv.org/abs/2110.11809)[[Code]](https://github.com/filipe-research/PropMix.)
* (IJCAI2021 Workshop) An Ensemble Noise-Robust K-fold Cross-Validation Selection Method for Noisy Labels. [[Paper]](https://arxiv.org/abs/2107.02347)
-----
### ArXiv 2021
* [[**UCSC REAL Lab**]](https://github.com/UCSC-REAL) Learning with Noisy Labels Revisited: A Study Using Real-World Human Annotations. [[Paper]](https://arxiv.org/abs/2110.12088)[[Code]](https://github.com/zwzhu-d/cifar-10-100n)
* [[**UCSC REAL Lab**]](https://github.com/UCSC-REAL) Understanding Generalized Label Smoothing when Learning with Noisy Labels. [[Paper]](https://arxiv.org/abs/2106.04149)
* [[**UCSC REAL Lab**]](https://github.com/UCSC-REAL) A Good Representation Detects Noisy Labels. [[Paper]](https://arxiv.org/pdf/2110.06283.pdf)
* [[**UCSC REAL Lab**]](https://github.com/UCSC-REAL) Demystifying How Self-Supervised Features Improve Training from Noisy Labels. [[Paper]](https://arxiv.org/pdf/2110.09022.pdf)[[code]](https://github.com/UCSC-REAL/SelfSup_NoisyLabel)
* Pervasive Label Errors in Test Sets Destabilize Machine Learning Benchmarks. [[Paper]](https://arxiv.org/abs/2103.14749)[[Code]](https://github.com/cgnorthcutt/label-errors)
* Double Descent in Adversarial Training: An Implicit Label Noise Perspective. [[Paper]](https://arxiv.org/pdf/2110.03135.pdf)
* Estimating Instance-dependent Label-noise Transition Matrix using DNNs. [[Paper]](https://arxiv.org/abs/2105.13001)
* A Theoretical Analysis of Learning with Noisily Labeled Data. [[Paper]](https://arxiv.org/abs/2104.04114)
* Learning from Multiple Annotators by Incorporating Instance Features. [[Paper]](https://arxiv.org/abs/2106.15146)
* Learning from Multiple Noisy Partial Labelers. [[Paper]](https://arxiv.org/abs/2106.04530)
* Instance Correction for Learning with Open-set Noisy Labels. [[Paper]](https://arxiv.org/abs/2106.00455)
* Sample Selection with Uncertainty of Losses for Learning with Noisy Labels. [[Paper]](https://arxiv.org/abs/2106.00445)
* Analysis of classifiers robust to noisy labels. [[Paper]](https://arxiv.org/abs/2106.00274)
* NoiLIn: Do Noisy Labels Always Hurt Adversarial Training? [[Paper]](https://arxiv.org/abs/2105.14676)
* Alleviating Noisy-label Effects in Image Classification via Probability Transition Matrix. [[Paper]](https://arxiv.org/abs/2110.08866)
* Learning with Noisy Labels by Targeted Relabeling. [[Paper]](https://arxiv.org/abs/2110.08355)
* Simple Attention Module based Speaker Verification with Iterative noisy label detection. [[Paper]](https://arxiv.org/abs/2110.06534)
* Adaptive Early-Learning Correction for Segmentation from Noisy Annotations. [[Paper]](https://arxiv.org/abs/2110.03740)
* Robust Deep Learning from Crowds with Belief Propagation. [[Paper]](https://arxiv.org/abs/2111.00734)
* Adaptive Hierarchical Similarity Metric Learning with Noisy Labels. [[Paper]](https://arxiv.org/abs/2111.00006)
* Prototypical Classifier for Robust Class-Imbalanced Learning. [[Paper]](https://arxiv.org/abs/2110.11553)
* A Survey of Label-noise Representation Learning: Past, Present and Future. [[Paper]](https://arxiv.org/pdf/2011.04406.pdf)
* Noisy-Labeled NER with Confidence Estimation. [[Paper]](https://arxiv.org/pdf/2104.04318.pdf)[[Code]](https://github.com/liukun95/Noisy-NER-Confidence-Estimation)
* Study Group Learning: Improving Retinal Vessel Segmentation Trained with Noisy Labels. [[Paper]](https://arxiv.org/pdf/2103.03451.pdf)[[Code]](https://github.com/SHI-Labs/SGL-Retinal-Vessel-Segmentation)
* Contrast to Divide: Self-Supervised Pre-Training for Learning with Noisy Labels. [[Paper]](https://arxiv.org/pdf/2103.13646.pdf)[[Code]](https://github.com/ContrastToDivide/C2D)
* Exponentiated Gradient Reweighting for Robust Training Under Label Noise and Beyond. [[Paper]](https://arxiv.org/pdf/2104.01493.pdf)
* Understanding the Interaction of Adversarial Training with Noisy Labels. [[Paper]](https://arxiv.org/pdf/2102.03482.pdf)
* Learning from Noisy Labels via Dynamic Loss Thresholding. [[Paper]](https://arxiv.org/pdf/2104.02570.pdf)
* Evaluating Multi-label Classifiers with Noisy Labels. [[Paper]](https://arxiv.org/pdf/2102.08427.pdf)
* Self-Supervised Noisy Label Learning for Source-Free Unsupervised Domain Adaptation. [[Paper]](https://arxiv.org/pdf/2102.11614.pdf)
* Transform consistency for learning with noisy labels. [[Paper]](https://arxiv.org/pdf/2103.13872.pdf)
* Learning to Combat Noisy Labels via Classification Margins. [[Paper]](https://arxiv.org/pdf/2102.00751.pdf)
* Joint Negative and Positive Learning for Noisy Labels. [[Paper]](https://arxiv.org/pdf/2104.06574.pdf)
* Robust Classification from Noisy Labels: Integrating Additional Knowledge for Chest
Radiography Abnormality Assessment. [[Paper]](https://arxiv.org/pdf/2104.05261.pdf)
* DST: Data Selection and joint Training for Learning with Noisy Labels. [[Paper]](https://arxiv.org/pdf/2103.00813.pdf)
* LongReMix: Robust Learning with High Confidence Samples in a Noisy Label Environment. [[Paper]](https://arxiv.org/pdf/2103.04173.pdf)
* A Novel Perspective for Positive-Unlabeled Learning via Noisy Labels. [[Paper]](https://arxiv.org/pdf/2103.04685.pdf)
*  Ensemble Learning with Manifold-Based Data Splitting for Noisy Label Correction. [[Paper]](https://arxiv.org/pdf/2103.07641.pdf)
* MetaLabelNet: Learning to Generate Soft-Labels from Noisy-Labels. [[Paper]](https://arxiv.org/pdf/2103.10869.pdf)
* On the Robustness of Monte Carlo Dropout Trained with Noisy Labels. [[Paper]](https://arxiv.org/pdf/2103.12002.pdf)
*  Co-matching: Combating Noisy Labels by Augmentation Anchoring. [[Paper]](https://arxiv.org/pdf/2103.12814.pdf)
* Pathological Image Segmentation with Noisy Labels. [[Paper]](https://arxiv.org/pdf/2104.02602.pdf)
* CrowdTeacher: Robust Co-teaching with Noisy Answers & Sample-specific Perturbations for Tabular Data. [[Paper]](https://arxiv.org/pdf/2103.17144.pdf)
* Approximating Instance-Dependent Noise via Instance-Confidence Embedding. [[Paper]](https://arxiv.org/abs/2103.13569)
* Rethinking Noisy Label Models: Labeler-Dependent Noise with Adversarial Awareness. [[Paper]](https://arxiv.org/abs/2105.14083)
* ScanMix: Learning from Severe Label Noise viaSemantic Clustering and Semi-Supervised Learning. [[Paper]](https://arxiv.org/abs/2103.11395)
* Friends and Foes in Learning from Noisy Labels. [[Paper]](https://arxiv.org/pdf/2103.15055.pdf)
* Learning from Noisy Labels for Entity-Centric Information Extraction. [[Paper]](https://arxiv.org/pdf/2104.08656.pdf)
* A Fremework Using Contrastive Learning for Classification with Noisy Labels. [[Paper]](https://arxiv.org/pdf/2104.09563.pdf)
* Contrastive Learning Improves Model Robustness Under Label Noise. [[Paper]](https://arxiv.org/pdf/2104.08984.pdf)[[Code]](https://github.com/arghosh/noisy_label_pretrain)
* Noise-Resistant Deep Metric Learning with Probabilistic Instance Filtering. [[Paper]](https://arxiv.org/pdf/2108.01431.pdf)
* Compensation Learning. [[Paper]](https://arxiv.org/pdf/2107.11921.pdf)
* kNet: A Deep kNN Network To Handle Label Noise. [[Paper]](https://arxiv.org/pdf/2107.09735.pdf)
* Temporal-aware Language Representation Learning From Crowdsourced Labels. [[Paper]](https://arxiv.org/pdf/2107.07958.pdf)
* Memorization in Deep Neural Networks: Does the Loss Function matter?. [[Paper]](https://arxiv.org/pdf/2107.09957.pdf)
* Mitigating Memorization in Sample Selection for Learning with Noisy Labels. [[Paper]](https://arxiv.org/pdf/2107.07041.pdf)
* P-DIFF: Learning Classifier with Noisy Labels based on Probability Difference Distributions. [[Paper]](https://arxiv.org/abs/2009.06382)[[Code]](https://github.com/fistyee/P-DIFF)
* Decoupling Representation and Classifier for Noisy Label Learning. [[Paper]](https://arxiv.org/pdf/2011.08145.pdf)
* Contrastive Representations for Label Noise Require Fine-Tuning. [[Paper]](https://arxiv.org/pdf/2108.09154.pdf)
* NGC: A Unified Framework for Learning with Open-World Noisy Data. [[Paper]](https://arxiv.org/pdf/2108.11035.pdf)
* Learning From Long-Tailed Data With Noisy Labels. [[Paper]](https://arxiv.org/pdf/2108.11096.pdf)
* Robust Long-Tailed Learning Under Label Noise. [[Paper]](https://arxiv.org/pdf/2108.11569.pdf)
* Instance-dependent Label-noise Learning under a Structural Causal Model. [[Paper]](https://arxiv.org/pdf/2109.02986.pdf)
* Assessing the Quality of the Datasets by Identifying Mislabeled Samples. [[Paper]](https://arxiv.org/pdf/2109.05000.pdf)
* Learning to Aggregate and Refine Noisy Labels for Visual Sentiment Analysis. [[Paper]](https://arxiv.org/abs/2109.07509)
* Robust Temporal Ensembling for Learning with Noisy Labels. [[Paper]](https://arxiv.org/pdf/2109.14563.pdf)
* Knowledge Distillation with Noisy Labels for Natural Language Understanding. [[Paper]](https://arxiv.org/pdf/2109.10147.pdf)
* Robustness and reliability when training with noisy labels. [[Paper]](https://arxiv.org/pdf/2110.03321.pdf)
* Noisy Annotations Robust Consensual Collaborative Affect Expression Recognition. [[Paper]](https://openaccess.thecvf.com/content/ICCV2021W/ABAW/papers/Gera_Noisy_Annotations_Robust_Consensual_Collaborative_Affect_Expression_Recognition_ICCVW_2021_paper.pdf)
* Consistency Regularization Can Improve Robustness to Label Noise. [[Paper]](https://arxiv.org/pdf/2110.01242.pdf)
-----
## Papers & Code in 2020
-----
### ICML 2020
* [[**UCSC REAL Lab**]](https://github.com/UCSC-REAL) Peer Loss Functions: Learning from Noisy Labels without Knowing Noise Rates. [[Paper]](http://proceedings.mlr.press/v119/liu20e)[[Code 1]](https://github.com/weijiaheng/Multi-class-Peer-Loss-functions) [[Code 2]](https://github.com/gohsyi/PeerLoss)
* Normalized Loss Functions for Deep Learning with Noisy Labels. [[Paper]](https://arxiv.org/abs/2006.13554)[[Code]](https://github.com/HanxunH/Active-Passive-Losses)
* SIGUA: Forgetting May Make Learning with Noisy Labels More Robust. [[Paper]](http://proceedings.mlr.press/v119/han20c.html)[[Code]](https://github.com/bhanML/SIGUA)
* Error-Bounded Correction of Noisy Labels. [[Paper]](http://proceedings.mlr.press/v119/zheng20c.html)[[Code]](https://github.com/pingqingsheng/LRT)
* Training Binary Neural Networks through Learning with Noisy Supervision. [[Paper]](http://proceedings.mlr.press/v119/han20d.html)[[Code]](https://github.com/zhaohui-yang/Binary-Neural-Networks)
* Improving generalization by controlling label-noise information in neural network weights. [[Paper]](http://proceedings.mlr.press/v119/harutyunyan20a.html)[[Code]](https://github.com/hrayrhar/limit-label-memorization)
* Self-PU: Self Boosted and Calibrated Positive-Unlabeled Training. [[Paper]](https://arxiv.org/abs/2006.11280)[[Code]](https://github.com/VITA-Group/Self-PU)
* Searching to Exploit Memorization Effect in Learning with Noisy Labels. [[Paper]](http://proceedings.mlr.press/v119/yao20b.html)[[Code]](https://github.com/jerermyyoung/rtlearning)
* Learning with Bounded Instance and Label-dependent Label Noise. [[Paper]](http://proceedings.mlr.press/v119/cheng20c.html)
* Label-Noise Robust Domain Adaptation. [[Paper]](http://proceedings.mlr.press/v119/yu20c.html)
* Beyond Synthetic Noise: Deep Learning on Controlled Noisy Labels. [[Paper]](http://proceedings.mlr.press/v119/jiang20c)
* Does label smoothing mitigate label noise?. [[Paper]](http://proceedings.mlr.press/v119/lukasik20a.html)
* Learning with Multiple Complementary Labels. [[Paper]](http://proceedings.mlr.press/v119/feng20a.html)
* Deep k-NN for Noisy Labels. [[Paper]](http://proceedings.mlr.press/v119/bahri20a.html)
* Extreme Multi-label Classification from Aggregated Labels. [[Paper]](http://proceedings.mlr.press/v119/shen20f.html)
-----
### ICLR 2020
* DivideMix: Learning with Noisy Labels as Semi-supervised Learning. [[Paper]](https://openreview.net/forum?id=HJgExaVtwr)[[Code]](https://github.com/LiJunnan1992/DivideMix)
* Learning from Rules Generalizing Labeled Exemplars. [[Paper]](https://openreview.net/pdf?id=SkeuexBtDr) [[Code]](https://github.com/awasthiabhijeet/Learning-From-Rules)
* Robust training with ensemble consensus. [[Paper]](https://openreview.net/forum?id=ryxOUTVYDH)[[Code]](https://github.com/jisoolee0123/Robust-training-with-ensemble-consensus)
* Self-labelling via simultaneous clustering and representation learning. [[Paper]](https://openreview.net/forum?id=Hyx-jyBFPr)[[Code]](https://github.com/yukimasano/self-label)
* Can gradient clipping mitigate label noise? [[Paper]](https://openreview.net/forum?id=rklB76EKPr)[[Code]](https://github.com/dmizr/phuber)
* Mutual Mean-Teaching: Pseudo Label Refinery for Unsupervised Domain Adaptation on Person Re-identification. [[Paper]](https://openreview.net/forum?id=rJlnOhVYPS)[[Code]](https://github.com/yxgeee/MMT)
* Curriculum Loss: Robust Learning and Generalization against Label Corruption. [[Paper]](https://openreview.net/forum?id=rkgt0REKwS)
* Simple and Effective Regularization Methods for Training on Noisily Labeled Data with Generalization Guarantee. [[Paper]](https://openreview.net/forum?id=Hke3gyHYwH)
* SELF: Learning to Filter Noisy Labels with Self-Ensembling. [[Paper]](https://openreview.net/forum?id=HkgsPhNYPS)
-----
### Nips 2020
* Part-dependent Label Noise: Towards Instance-dependent Label Noise. [[Paper]](https://papers.nips.cc/paper/2020/hash/5607fe8879e4fd269e88387e8cb30b7e-Abstract.html)[[Code]](https://github.com/xiaoboxia/Part-dependent-label-noise)
* Identifying Mislabeled Data using the Area Under the Margin Ranking. [[Paper]](https://papers.nips.cc/paper/2020/hash/c6102b3727b2a7d8b1bb6981147081ef-Abstract.html)[[Code]](https://github.com/asappresearch/aum)
* Dual T: Reducing Estimation Error for Transition Matrix in Label-noise Learning. [[Paper]](https://papers.nips.cc/paper/2020/hash/512c5cad6c37edb98ae91c8a76c3a291-Abstract.html)
* Early-Learning Regularization Prevents Memorization of Noisy Labels. [[Paper]](https://papers.nips.cc/paper/2020/hash/ea89621bee7c88b2c5be6681c8ef4906-Abstract.html)[[Code]](https://github.com/shengliu66/ELR)
* Coresets for Robust Training of Deep Neural Networks against Noisy Labels. [[Paper]](https://papers.nips.cc/paper/2020/hash/8493eeaccb772c0878f99d60a0bd2bb3-Abstract.html)[[Code]](https://github.com/snap-stanford/crust)
* Modeling Noisy Annotations for Crowd Counting. [[Paper]](https://papers.nips.cc/paper/2020/hash/22bb543b251c39ccdad8063d486987bb-Abstract.html)[[Code]](https://github.com/jia-wan/NoisyCC-pytorch)
* Robust Optimization for Fairness with Noisy Protected Groups. [[Paper]](https://papers.nips.cc/paper/2020/hash/37d097caf1299d9aa79c2c2b843d2d78-Abstract.html)[[Code]](https://github.com/wenshuoguo/robust-fairness-code)
* Stochastic Optimization with Heavy-Tailed Noise via Accelerated Gradient Clipping. [[Paper]](https://papers.nips.cc/paper/2020/hash/abd1c782880cc59759f4112fda0b8f98-Abstract.html)[[Code]](https://github.com/eduardgorbunov/accelerated_clipping)
* A Topological Filter for Learning with Label Noise. [[Paper]](https://papers.nips.cc/paper/2020/hash/f4e3ce3e7b581ff32e40968298ba013d-Abstract.html)[[Code]](https://github.com/pxiangwu/TopoFilter)
* Self-Adaptive Training: beyond Empirical Risk Minimization. [[Paper]](https://proceedings.neurips.cc//paper/2020/hash/e0ab531ec312161511493b002f9be2ee-Abstract.html)[[Code]](https://github.com/LayneH/self-adaptive-training)
* Disentangling Human Error from the Ground Truth in Segmentation of Medical Images. [[Paper]](https://proceedings.neurips.cc//paper/2020/file/b5d17ed2b502da15aa727af0d51508d6-Paper.pdf)[[Code]](https://github.com/moucheng2017/Learn_Noisy_Labels_Medical_Images)
* Non-Convex SGD Learns Halfspaces with Adversarial Label Noise. [[Paper]](https://papers.nips.cc/paper/2020/hash/d785bf9067f8af9e078b93cf26de2b54-Abstract.html)
* Efficient active learning of sparse halfspaces with arbitrary bounded noise. [[Paper]](https://papers.nips.cc/paper/2020/hash/5034a5d62f91942d2a7aeaf527dfe111-Abstract.html)
* Semi-Supervised Partial Label Learning via Confidence-Rated Margin Maximization. [[Paper]](https://papers.nips.cc/paper/2020/hash/4dea382d82666332fb564f2e711cbc71-Abstract.html)
* Labelling unlabelled videos from scratch with multi-modal self-supervision. [[Paper]](https://papers.nips.cc/paper/2020/hash/31fefc0e570cb3860f2a6d4b38c6490d-Abstract.html)[[Code]](https://github.com/facebookresearch/selavi)
* Distribution Aligning Refinery of Pseudo-label for Imbalanced Semi-supervised Learning. [[Paper]](https://papers.nips.cc/paper/2020/hash/a7968b4339a1b85b7dbdb362dc44f9c4-Abstract.html)[[Code]](https://github.com/bbuing9/DARP)
* MetaPoison: Practical General-purpose Clean-label Data Poisoning. [[Paper]](https://papers.nips.cc/paper/2020/hash/8ce6fc704072e351679ac97d4a985574-Abstract.html)[[Code 1]](https://github.com/wronnyhuang/metapoison)[[Code 2]](https://github.com/JonasGeiping/poisoning-gradient-matching)
* Provably Consistent Partial-Label Learning. [[Paper]](https://papers.nips.cc/paper/2020/hash/7bd28f15a49d5e5848d6ec70e584e625-Abstract.html)
* A Variational Approach for Learning from Positive and Unlabeled Data. [[Paper]](https://papers.nips.cc/paper/2020/hash/aa0d2a804a3510442f2fd40f2100b054-Abstract.html)[[Code]](https://github.com/HC-Feynman/vpu)
-----
### AAAI 2020
* [[**UCSC REAL Lab**]](https://github.com/UCSC-REAL) Reinforcement Learning with Perturbed Rewards. [[Paper]](https://arxiv.org/abs/1810.01032) [[Code]](https://github.com/wangjksjtu/rl-perturbed-reward)
* Less Is Better: Unweighted Data Subsampling via Influence Function. [[Paper]](https://arxiv.org/abs/1912.01321) [[Code]](https://github.com/RyanWangZf/Influence_Subsampling)
* Weakly Supervised Sequence Tagging from Noisy Rules. [[Paper]](https://ojs.aaai.org//index.php/AAAI/article/view/6009)[[Code]](https://github.com/BatsResearch/wiser)
* Coupled-View Deep Classifier Learning from Multiple Noisy Annotators. [[Paper]](https://ojs.aaai.org//index.php/AAAI/article/view/5898)
* Partial multi-label learning with noisy label identification. [[Paper]](http://www.xiemk.pro/publication/aaai20-pml-ni.pdf)
* Self-Paced Robust Learning for Leveraging Clean Labels in Noisy Data. [[Paper]](https://xuczhang.github.io/papers/aaai20_sprl.pdf)
* Label Error Correction and Generation Through Label Relationships. [[Paper]](https://ojs.aaai.org//index.php/AAAI/article/view/5778)
-----
### CVPR 2020
* Combating noisy labels by agreement: A joint training method with co-regularization. [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Wei_Combating_Noisy_Labels_by_Agreement_A_Joint_Training_Method_with_CVPR_2020_paper.html)[[Code]](https://github.com/hongxin001/JoCoR)
* Distilling Effective Supervision From Severe Label Noise. [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Zhang_Distilling_Effective_Supervision_From_Severe_Label_Noise_CVPR_2020_paper.html)[[Code]](https://github.com/google-research/google-research/tree/master/ieg)
* Self-Training With Noisy Student Improves ImageNet Classification. [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Xie_Self-Training_With_Noisy_Student_Improves_ImageNet_Classification_CVPR_2020_paper.html)[[Code]](https://github.com/google-research/noisystudent)
* Noise Robust Generative Adversarial Networks. [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Kaneko_Noise_Robust_Generative_Adversarial_Networks_CVPR_2020_paper.html)[[Code]](https://github.com/takuhirok/NR-GAN/)
* Global-Local GCN: Large-Scale Label Noise Cleansing for Face Recognition. [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Zhang_Global-Local_GCN_Large-Scale_Label_Noise_Cleansing_for_Face_Recognition_CVPR_2020_paper.html)
* DLWL: Improving Detection for Lowshot Classes With Weakly Labelled Data. [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Ramanathan_DLWL_Improving_Detection_for_Lowshot_Classes_With_Weakly_Labelled_Data_CVPR_2020_paper.html)
* Spherical Space Domain Adaptation With Robust Pseudo-Label Loss. [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Gu_Spherical_Space_Domain_Adaptation_With_Robust_Pseudo-Label_Loss_CVPR_2020_paper.html)[[Code]](https://github.com/XJTU-XGU/RSDA)
* Training Noise-Robust Deep Neural Networks via Meta-Learning. [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Wang_Training_Noise-Robust_Deep_Neural_Networks_via_Meta-Learning_CVPR_2020_paper.html)[[Code]](https://github.com/ZhenWang-PhD/Training-Noise-Robust-Deep-Neural-Networks-via-Meta-Learning)
* Shoestring: Graph-Based Semi-Supervised Classification With Severely Limited Labeled Data. [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Lin_Shoestring_Graph-Based_Semi-Supervised_Classification_With_Severely_Limited_Labeled_Data_CVPR_2020_paper.html)[[Code]](https://github.com/iQua/CVPR2020-Shoestring)
* Noise-Aware Fully Webly Supervised Object Detection. [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Shen_Noise-Aware_Fully_Webly_Supervised_Object_Detection_CVPR_2020_paper.html)[[Code]](https://github.com/shenyunhang/NA-fWebSOD)
* Learning From Noisy Anchors for One-Stage Object Detection. [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Li_Learning_From_Noisy_Anchors_for_One-Stage_Object_Detection_CVPR_2020_paper.html)[[Code]](https://github.com/henrylee2570/NoisyAnchor)
* Generating Accurate Pseudo-Labels in Semi-Supervised Learning and Avoiding Overconfident Predictions via Hermite Polynomial Activations. [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Lokhande_Generating_Accurate_Pseudo-Labels_in_Semi-Supervised_Learning_and_Avoiding_Overconfident_Predictions_CVPR_2020_paper.html)[[Code]](https://github.com/lokhande-vishnu/DeepHermites)
* Revisiting Knowledge Distillation via Label Smoothing Regularization. [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Yuan_Revisiting_Knowledge_Distillation_via_Label_Smoothing_Regularization_CVPR_2020_paper.html)[[Code]](https://github.com/yuanli2333/Teacher-free-Knowledge-Distillation)
-----
### ECCV 2020
* 2020-ECCV - Learning with Noisy Class Labels for Instance Segmentation. [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/2062_ECCV_2020_paper.php)[[Code]](https://github.com/longrongyang/LNCIS)
* 2020-ECCV - Suppressing Mislabeled Data via Grouping and Self-Attention. [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/2633_ECCV_2020_paper.php)[[Code]](https://github.com/kaiwang960112/AFM)
* 2020-ECCV - NoiseRank: Unsupervised Label Noise Reduction with Dependence Models. [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/5921_ECCV_2020_paper.php)
* 2020-ECCV - Weakly Supervised Learning with Side Information for Noisy Labeled Images. [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/7467_ECCV_2020_paper.php)
* 2020-ECCV - Learning Noise-Aware Encoder-Decoder from Noisy Labels by Alternating Back-Propagation for Saliency Detection. [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/2760_ECCV_2020_paper.php)
* 2020-ECCV - Graph convolutional networks for learning with few clean and many noisy labels. [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/1060_ECCV_2020_paper.php)
-----
### ArXiv 2020
* No Regret Sample Selection with Noisy Labels. [[Paper]](https://arxiv.org/pdf/2003.03179.pdf)[[Code]](https://github.com/songheony/TAkS)
* Meta Soft Label Generation for Noisy Labels. [[Paper]](https://arxiv.org/pdf/2007.05836.pdf)[[Code]](https://github.com/gorkemalgan/MSLG_noisy_label)
* Learning from Noisy Labels with Deep Neural Networks: A Survey. [[Paper]](https://arxiv.org/pdf/2007.08199.pdf)
* RAR-U-Net: a Residual Encoder to Attention Decoder by Residual Connections Framework for Spine Segmentation under Noisy Labels. [[Paper]](https://arxiv.org/pdf/2009.12873.pdf)
* Learning from Small Amount of Medical Data with Noisy Labels: A Meta-Learning Approach. [[Paper]](https://arxiv.org/pdf/2010.06939.pdf)
-----
