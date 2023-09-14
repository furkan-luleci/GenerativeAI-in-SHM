# Generative AI in Civil SHM

### Objective:

<ins>The goal of this repository</ins> is to help researchers get updated about the studies conducted using generative AI models in the civil Structural Health Monitoring (SHM) area. 

Thus, <ins>**the repository herein presents**</ins> the direct and indirect use of Deep Generative Models (DGMs): *Generative Adversarial Networks (GANs)*, *Variational Autoencoders (VAEs)*, *Diffusion Models (DMs)*, *Flow-Based Models (FBMs)*, *Energy-Based Models (EBMs)*, and *Autoregressive Models (AMs)*, in the context of civil SHM applications to date.

While the discriminative AI approaches have been prevalent ever since the data-driven applications were used in the civil SHM domain, the DGMs are the generative AI models used for generative AI tasks, and their use has been observed increasingly lately. Thus, <ins>**this repo aims to present**</ins> these generative AI models used for SHM applications in research.

### A brief background:

Generative AI, as seen in large language models like ChatGPT, LLAMA, BARD, or PaLM, and other image-based generative models used for text-to-image applications, such as Dalle, Midjourney, StableDiffusion, or Imagen, has become a part of our daily lives. The origins of the generative AI research field go back to the 2010s with the development of Deep Learning models, like RNNs and CNNs, which improved the generative tasks significantly, allowing computers to generate data that resembles human-generated content. The AI research field, in fact, dates back as early as the 1950s, when Alan Turing made important contributions. However, the term “generative AI” gained widespread recognition more recently with the release of generative models like ChatGPT. These generative AI models have demonstrated impressive generative skills and have been applied in various domains, from natural language generation to art creation.

### In civil SHM:

The earliest use of generative AI started with using AMs more than a decade ago. The use of AMs has been a very popular research activity in many SHM studies, but largely for feature extraction purposes, more than the generative tasks. I have identified a few studies that use AMs for generative tasks e.g., signal reconstruction. However, there are over a hundred studies that deal with feature extraction (I've included a few of the representative recent studies that directly focused on data generation using AMs in this repo). Also, considering that subsequently developed DGMs, such as VAEs, GANs, or DMs, demonstrate better generative performances than AMs [ref1](https://ieeexplore.ieee.org/abstract/document/9555209), [ref2](https://link.springer.com/article/10.1007/s43503-023-00017-z). Because of these reasons, I’ve excluded AMs in this repo and hope to include them later in the future when I can spare more time on this.

### In civil SHM (without AMs): 

When the AMs are excluded, it is observed that a large portion of generative AI studies are implemented using GANs and then VAEs. I have observed one study using DMs, which is a much newer generative AI model compared to other DGMs. I have not observed any study using EBMs and FBMs in the context of civil SHM research.

### Note 1: 

As the civil SHM study area is growing rapidly, the scope of the literature review somewhat overlaps with other fields. I aimed to define the scope of this repo as the generative AI models applied to civil engineering structures, excluding any machinery tools/testbeds/rotating machines and pavement structures, but including monitoring of wind turbines.

### Note 2: 

The four main applications of generative AI in civil SHM are *lost data reconstruction*, *data augmentation*, *data domain translation*, and *data denoising, repair, deblurring, and increased resolution*. I categorized the others as the studies focused on direct-content generation and the studies that are not directly focused on content generation.

<ins>Please let me know</ins> in the Pull Requests tab above or personally email me at ([email link](furkanluleci@ucf.edu)). I'd appreciate any contribution to this repo. 

Thanks!



## Contents
- [Survey](#survey)
- [Lost Data Reconstruction](#lost-data-reconstruction)
- [Data Augmentation](#data-augmentation)
- [Data Domain Translation](#data-domain-translation)
- [Data Denoising, Repair, Deblurring, and Increased Resolution](#data-denoising,-repair,-deblurring,-and-increased-resolution)
- [Data Generation for Various Other SHM Applications](#data-generation-for-various-other-shm-applications)
  - [Data Generation (focused on direct-content generation and model's generative-ability, e.g., data feature capturing, distribution construction, etc.)](#data-generation-(focused-on-direct-content-generation-and-model's-generative-ability,-e.g.,-data-feature-capturing,-distribution-reconstruction,-etc.))
  - [Leveraging Generative AI for Anomaly/Novelty/Outlier Detection, Damage Diagnosis/Prognosis, Physics-based Modeling, and other Condition Assessment Techniques - (the studies here are not directly focused on content generation)](#leveraging-generative-ai-for-anomaly/novelty/outlier-detection,-damage-diagnosis/prognosis,-physics-based-modeling,and-other-condition-assessment-techniques-(the-studies-here-are-not-directly-focused-on-content-generation))





## Survey

**A literature review: Generative adversarial networks for civil structural health monitoring** \
*Furkan Luleci, F. Necati Catbas, Onur Avci* \
Frontiers in Built Environment [[Paper](https://www.frontiersin.org/articles/10.3389/fbuil.2022.1027379/full)] \
07 November 2022

**Generative adversarial networks review in earthquake-related engineering fields** \
*Giuseppe Carlo Marano, Marco Martino Rosso, Angelo Aloisio, Giansalvo Cirrincione* \
Bulletin of Earthquake Engineering [[Paper](https://link.springer.com/article/10.1007/s10518-023-01645-7)] \
28 February 2023

**A brief introductory review to deep generative models for civil structural health monitoring** \
*Furkan Luleci, F. Necati Catbas* \
AI in Civil Engineering [[Paper](https://link.springer.com/article/10.1007/s43503-023-00017-z)] \
23 August 2023

## Lost Data Reconstruction

**Lost data reconstruction for structural health monitoring using deep convolutional generative adversarial networks** \
*Xiaoming Lei, Limin Sun, Ye Xia* \
Structural Health Monitoring [[Paper](https://doi.org/10.1177/1475921720959226)] \
10 October 2020

**Data driven structural dynamic response reconstruction using segment based generative adversarial networks** \
*Gao Fan, Jun Li, Hong Hao, Yu Xin* \
Engineering Structures [[Paper](https://doi.org/10.1016/j.engstruct.2021.111970)] \
12 February 2021

**Continuous missing data imputation with incomplete dataset by generative adversarial networks–based unsupervised learning for long-term bridge health monitoring** \
*Huachen Jiang, Chunfeng Wan, Kang Yang, Youliang Ding, Songtao Xue* \
Structural Health Monitoring [[Paper](https://doi.org/10.1177/14759217211021942)] \
4 June 2021

**Data Loss Reconstruction Method for a Bridge Weigh-in-Motion System Using Generative Adversarial Networks** \
*Yizhou Zhuang,Jiacheng Qin,Bin Chen, Chuanzhi Dong, Chenbo Xue, Said M. Easa* \
Sensors [[Paper](https://www.mdpi.com/1424-8220/22/3/858)] \
23 January 2022

**Deep learning and data augmentation based data imputation for structural health monitoring system in multi-sensor damaged state** \
*Jiale Hou, Huachen Jiang, Chunfeng Wan, Letian Yi, Shuai Gao, Youliang Ding, Songtao Xue* \
Measurement [[Paper](https://doi.org/10.1016/j.measurement.2022.111206)] \
20 April 2022

**Missing data imputation framework for bridge structural health monitoring based on slim generative adversarial networks** \
*Shuai Gao, Wenlong Zhao, Chunfeng Wan, Huachen Jiang, Youliang Ding, Songtao Xue* \
Measurement [[Paper](https://doi.org/10.1016/j.measurement.2022.112095)] \
21 October 2022

**Structural dynamic response reconstruction using self-attention enhanced generative adversarial networks** \
*Gao Fan, Zhengyan He, Jun Li* \
Engineering Structures [[Paper](https://doi.org/10.1016/j.engstruct.2022.115334)] \
1 December 2022

**Structural health monitoring response reconstruction based on UAGAN under structural condition variations with few-shot learning** \
*Gao Fan, Zhengyan He, Jun Li* \
ResearchGate [[Paper](https://www.researchgate.net/publication/368510160_Structural_health_monitoring_response_reconstruction_based_on_UAGAN_under_structural_condition_variations_with_few-shot_learning)] \
1 December 2022

**Reconstruction of long-term strain data for structural health monitoring with a hybrid deep-learning and autoregressive model considering thermal effects** \
*Chengbin Chen, Liqun Tang, Yonghui Lu, Yong Wang, Zejia Liu, Yiping Liu, Licheng Zhou, Zhenyu Jiang, Bao Yang* \
Engineering Structures, [[Paper](https://doi.org/10.1016/j.engstruct.2023.116063)] \
7 April 2023

**Multi-channel response reconstruction using transformer based generative adversarial network** \
*Wenhao Zheng, Jun Li, Qilin Li, Hong Hao* \
Earthquake Engineering and Structural Dynamics [[Paper](https://doi.org/10.1002/eqe.3960)] \
5 Jul 2023

**Deep Learning-Based Imputation Framework in Bridge Health Monitoring using Generative Adversarial Networks** \
*Saha, Sumit* \
Masters thesis, Indian Institute of Technology Hyderabad [[Paper](https://raiith.iith.ac.in/11523/)] \
19 Jul 2023










## Data Augmentation

**Efficient Processing of Distributed Acoustic Sensing Data Using a Deep Learning Approach** \
*Lihi Shiloh, Avishay Eyal, and Raja Giryes* \
Journal of Lightwave Technology [[Paper](https://opg.optica.org/jlt/abstract.cfm?URI=jlt-37-18-4755)] \
May 29, 2019

**Unsupervised domain adaptation with self-attention for post-disaster building damage detection** \
*Yundong Li, Chen Lin, Hongguang Li, Wei Hu, Han Dong, Yi Liu* \
Neurocomputing [[Paper](https://doi.org/10.1016/j.neucom.2020.07.005)] \
14 July 2020

**Deep leaf-bootstrapping generative adversarial network for structural image data augmentation** \
*Yuqing Gao, Boyuan Kong, Khalid M. Mosalam* \
Computer-Aided Civil and Infrastructure Engineering [[Paper](https://doi.org/10.1111/mice.12458)] \
18 July 2019

**Railway Fastener Fault Diagnosis Based on Generative Adversarial Network and Residual Network Model** \
*Dechen Yao, Qiang Sun, Jianwei Yang, Hengchang Liu, Jiao Zhang* \
Shochk and Vibration [[Paper](https://www.hindawi.com/journals/sv/2020/8823050/)] \
07 Nov 2020

**Balanced semisupervised generative adversarial network for damage assessment from low-data imbalanced-class regime** \
*Yuqing Gao, Pengyuan Zhai, Khalid M. Mosalam* \
Computer-Aided Civil and Infrastructure Engineering [[Paper](https://doi.org/10.1111/mice.12741)] \
28 June 2021

**A general framework for supervised structural health monitoring and sensor output validation mitigating data imbalance with generative adversarial networks-generated high-dimensional features** \
*Mohammad Hesam Soleimani-Babakamali, Roksana Soleimani-Babakamali, Rodrigo Sarlo* \
Structural Health Monitoring [[Paper](https://doi.org/10.1177/14759217211025488)] \
13 July 2021

**Fatigue Damage Diagnostics of Composites Using Data Fusion and Data Augmentation With Deep Neural Networks ** \
*Shweta Dabetwar, Stephen Ekwaro-Osire, João Paulo Dias* \
ASME J Nondestructive Evaluation [[Paper](https://doi.org/10.1115/1.4051947)] \
23 August 2021

**Data augmentation and its application in distributed acoustic sensing data denoising** \
*Y X Zhao, Y Li, N Wu* \
Geophysical Journal International [[Paper](https://doi.org/10.1093/gji/ggab345)] \
24 August 2021

**Enhancement of Multi-Class Structural Defect Recognition Using Generative Adversarial Network** \
*Hyunkyu Shin,Yonghan Ahn, Sungho Tae, Heungbae Gil, Mihwa Song, Sanghyo Lee* \
Sustainability [[Paper](https://www.mdpi.com/2071-1050/13/22/12682)] \
16 November 2021

**Crack Detection Based on Generative Adversarial Networks and Deep Learning** \
*Gongfa Chen, Shuai Teng, Mansheng Lin, Xiaomei Yang, Xiaoli Sun* \
KSCE Journal of Civil Engineering [[Paper](https://link.springer.com/article/10.1007/s12205-022-0518-2)] \
24 January 2022

**Pavement crack detection algorithm based on generative adversarial network and convolutional neural network under small samples** \
*Boqiang Xu, Chao Liu* \
Measurement [[Paper](https://doi.org/10.1016/j.measurement.2022.111219)] \
19 April 2022

**The Multiclass Fault Diagnosis of Wind Turbine Bearing Based on Multisource Signal Fusion and Deep Learning Generative Model** \
*Liang Zhang; Hao Zhang; Guowei Cai* \
IEEE [[Paper](https://www.techrxiv.org/articles/preprint/Effective_Generative_Data_Augmentation_in_Condition_Monitoring/24024522)] \
27 May 2022

**Attention-based generative adversarial network with internal damage segmentation using thermography** \
*Rahmat Ali, Young-Jin Cha* \
KSCE Journal of Civil Engineering [[Paper](https://doi.org/10.1016/j.autcon.2022.104412)] \
13 June 2022

**Data Augmentation for Deep-Learning-Based Multiclass Structural Damage Detection Using Limited Information** \
*Kyle Dunphy, Mohammad Navid Fekri,Katarina Grolinger, Ayan Sadhu* \
Sensors [[Paper](https://www.mdpi.com/1424-8220/22/16/6193)] \
18 August 2022

**Improvement of Fiber Bragg Grating Wavelength Demodulation System by Cascading Generative Adversarial Network and Dense Neural Network** \
*Shuna Li, Sufen Ren, Shengchao Chen, Benguo Yu* \
Applied Sciences [[Paper](https://www.mdpi.com/2076-3417/12/18/9031)] \
8 September 2022

**Generative adversarial networks for labeled acceleration data augmentation for structural damage detection** \
*Furkan Luleci, F. Necati Catbas, Onur Avci* \
Journal of Civil Structural Health Monitoring [[Paper](https://link.springer.com/article/10.1007/s13349-022-00627-8)] \
24 September 2022

**A Novel Data Augmentation Method for Improved Visual Crack Detection Using Generative Adversarial Networks** \
*Efstathios Branikas; Paul Murray; Graeme West* \
IEEE [[Paper](https://ieeexplore.ieee.org/abstract/document/10058512)] \
03 March 2023

**Dual generative adversarial networks combining conditional assistance and feature enhancement for imbalanced fault diagnosis** \
*Ranran Li, Shunming Li, Kun Xu, Mengjie Zeng, Xianglian Li* \
Structural Health Monitoring [[Paper](https://doi.org/10.1177/14759217231165223)] \
24 April 2023

**A machine learning-based data augmentation strategy for structural damage classification in civil infrastructure system** \
*Lechen Li & Raimondo Betti* \
Journal of Civil Structural Health Monitoring [[Paper](https://link.springer.com/article/10.1007/s13349-023-00705-5)] \
11 May 2023

**Subdomain-Alignment Data Augmentation for Pipeline Fault Diagnosis: An Adversarial Self-Attention Network** \
*Chuang Wang, Zidong Wang, Lifeng Ma, Hongli Dong, Weiguo Sheng* \
IEEE [[Paper](https://ieeexplore.ieee.org/abstract/document/10123949)] \
12 May 2023

**Data Anomaly Detection through Semisupervised Learning Aided by Customised Data Augmentation Techniques** \
*Xiaoyou Wang, Yao Du, Xiaoqing Zhou, Yong Xia* \
Structural Control and Health Monitoring [[Paper](https://www.hindawi.com/journals/schm/2023/2430011/)] \
22 July 2023

**Effective Generative Data Augmentation in Condition Monitoring** \
*Daniel Ortiz-Arroyo, Petar Durdevic* \
IEEE Sensors Journal [[Paper](https://www.techrxiv.org/articles/preprint/Effective_Generative_Data_Augmentation_in_Condition_Monitoring/24024522)] \
28 August 2023









## Data Domain Translation

**Self-Supervised Structure Learning for Crack Detection Based on Cycle-Consistent Generative Adversarial Networks** \
*Kaige Zhang, Yingtao Zhang, H. D. Cheng* \
Journal of Computing in Civil Engineering [[Paper](https://doi.org/10.1061/(ASCE)CP.1943-5487.0000883)] \
21 Jan 2020

**Generative Damage Learning for Concrete Aging Detection using Auto-flight Images** \
*Takato Yasuno, Akira Ishii, Junichiro Fujii, Masazumi Amakata, Yuta Takahashi* \
37th International Symposium on Automation and Robotics in Construction [[Paper](https://arxiv.org/abs/2006.15257)] \
27 Jun 2020

**Forecasting infrastructure deterioration with inverse GANs** \
*Eric Bianchi, Matthew Hebdon* \
Proceedings Volume 11843, Applications of Machine Learning 2021 [[Paper](https://doi.org/10.1117/12.2595111)] \
1 August 2021

**On the application of generative adversarial networks for nonlinear modal analysis** \
*G. Tsialiamanis, M.D. Champneys, N. Dervilis, D.J. Wagg, K. Worden* \
Mechanical Systems and Signal Processing [[Paper](https://doi.org/10.1016/j.ymssp.2021.108473)] \
8 October 2021

**Damage analysis and quantification of RC beams assisted by Damage-T Generative Adversarial Network** \
*Yanzhi Qi, Cheng Yuan, Peizhen Li, Qingzhao Kong* \
Engineering Applications of Artificial Intelligence [[Paper](https://doi.org/10.1016/j.engappai.2022.105536)] \
28 October 2022

**Structural State Translation: Condition Transfer between Civil Structures Using Domain-Generalization for Structural Health Monitoring** \
*Furkan Luleci, F. Necati Catbas* \
arXiv [[Paper](https://arxiv.org/abs/2212.14048)] \
28 December 2022

**Improved undamaged-to-damaged acceleration response translation for Structural Health Monitoring** \
*Furkan Luleci, Onur Avci, F. Necati Catbas* \
Engineering Applications of Artificial Intelligence [[Paper](https://doi.org/10.1016/j.engappai.2023.106146)] \
22 March 2023

**Establishment and evaluation of conditional GAN-based image dataset for semantic segmentation of structural cracks** \
*Furkan Luleci, F. Necati Catbas* \
Engineering Structures [[Paper](https://doi.org/10.1016/j.engstruct.2023.116058)] \
31 March 2023

**CycleGAN for undamaged-to-damaged domain translation for structural health monitoring and damage detection** \
*Furkan Luleci, Onur Avci, F. Necati Catbas* \
Mechanical Systems and Signal Processing [[Paper](https://doi.org/10.1016/j.ymssp.2023.110370)] \
23 April 2023

**Unsupervised deep learning-based ground penetrating radar image translation for internal defect recognition of underground engineering structures** \
*Zhengfang Wang, Ming Lei, Jing Wang, Bo Li, Jing Xu, Yuchen Jiang, Qingmei Sui, Yao Li* \
Structural Health Monitoring [[Paper](https://doi.org/10.1177/14759217231173314)] \
16 May 2023

**Condition transfer between prestressed bridges using structural state translation for structural health monitoring** \
*Furkan Luleci, F. Necati Catbas* \
AI in Civil Engineering [[Paper](https://link.springer.com/article/10.1007/s43503-023-00016-0)] \
02 August 2023








## Data Denoising, Repair, Deblurring, and Increased Resolution

**Application of improved least-square generative adversarial networks for rail crack detection by AE technique** \
*Wang Kangwei, Zhang Xin, Hao Qiushi, Wang Yan, Shen Yi* \
Neurocomputing [[Paper](https://doi.org/10.1016/j.neucom.2018.12.057)] \
30 December 2018

**Deep Learning–Based Enhancement of Motion Blurred UAV Concrete Crack Images** \
*Yiqing Liu, Justin K. W. Yeoh, David K. H. Chua* \
Journal of Computing in Civil Engineering [[Paper](https://doi.org/10.1061/(ASCE)CP.1943-5487.0000907)] \
10 June 2020

**Recovering compressed images for automatic crack segmentation using generative models** \
*Yong Huang, Haoyu Zhang, Hui Li, Stephen Wu* \
Mechanical Systems and Signal Processing [[Paper](https://doi.org/10.1016/j.ymssp.2020.107061)] \
29 June 2020

**Improved Image Based Super Resolution and Concrete Crack Prediction Using Pre-Trained Deep Learning Models** \
*Karunanithi Sathya, D. Sangavi, P. Sridharshini, M. Manobharathi, G. Jayapriya* \
Journal of Soft Computing in Civil Engineering [[Paper](https://www.jsoftcivil.com/article_110942_14151.html)] \
24 July 2020

**A two-stage data cleansing method for bridge global positioning system monitoring data based on bi-direction long and short term memory anomaly identification and conditional generative adversarial networks data repair** \
*Kang Yang, Youliang Ding, Huachen Jiang, Hanwei Zhao, Gan Luo* \
Structural Control and Health Monitoring [[Paper](https://doi.org/10.1002/stc.2993)] \
11 May 2022

**Vision-based displacement measurement enhanced by super-resolution using generative adversarial networks** \
*Chujin Sun, Donglian Gu, Yi Zhang, Xinzheng Lu* \
Structural Control and Health Monitoring [[Paper](https://doi.org/10.1002/stc.3048)] \
13 July 2022

**A fast sparsity-free compressive sensing approach for vibration data reconstruction using deep convolutional GAN** \
*Guan-Sen Dong, Hua-Ping Wan, Yaozhi Luo, Michael D. Todd* \
Mechanical Systems and Signal Processing [[Paper](https://doi.org/10.1016/j.ymssp.2022.109937)] \
26 November 2022

**Anomaly detection for wind turbine pitch bearings via autoencoder enhanced nonlinear autoregressive model** \
*Chao Zhang, Long Zhang* \
IEEE [[Paper](https://ieeexplore.ieee.org/abstract/document/10058286)] \
13 March 2023

**CrackDiffusion: crack inpainting with denoising diffusion models and crack segmentation perceptual score** \
*Lizhou Chen, Luoyu Zhou, Lei Li, Mingzhang Luo* \
Smart Materials and Structures [[Paper](https://iopscience.iop.org/article/10.1088/1361-665X/acc624)] \
30 March 2023

**Learning Structure for Concrete Crack Detection Using Robust Super-Resolution with Generative Adversarial Network** \
*Jin Kim, Seungbo Shim, Seok-Jun Kang, Gye-Chun Cho* \
Structural Control and Health Monitoring [[Paper](https://www.hindawi.com/journals/schm/2023/8850290/)] \
04 Apr 2023

**Multi-component condition monitoring method for wind turbine gearbox based on adaptive noise reduction** \
*Yang Chen, Yongqian Liu, Shuang Han, Yanhui Qiao* \
Structural Health Monitoring [[Paper](https://doi.org/10.1049/rpg2.12772)] \
12 June 2023

**Structural floor acceleration denoising method using generative adversarial network** \
*Junkai Shen, Lingxin Zhang, Koichi Kusunoki, Trevor Zhiqing Yeow* \
Soil Dynamics and Earthquake Engineering [[Paper](https://doi.org/10.1016/j.soildyn.2023.108061)] \
4 July 2023

**Robust multitask compressive sampling via deep generative models for crack detection in structural health monitoring** \
*Haoyu Zhang, Stephen Wu, Yong Huang, Hui Li* \
Structural Health Monitoring [[Paper](https://doi.org/10.1177/14759217231183663)] \
17 July 2023










## Data Generation for Various Other SHM Applications

### *Data Generation (focused on direct-content generation and model's generative-ability, e.g., data feature capturing, distribution reconstruction, etc.)*

**Generative Model of Acceleration Data for Deep Learning-based Damage Detection for Bridges Using Generative Adversarial Network** \
*Lee Kanghyeok, Shin Do Hyoung* \
Journal of KIBIM [[Paper](https://doi.org/10.13161/kibim.2019.9.1.042)] \
31 March 2019

**A Generative Adversarial Network Model for Simulating Various Types of Human-Induced Loads** \
*Jiecheng Xiong, Jun Chen* \
International Journal of Structural Stability and Dynamics [[Paper](https://doi.org/10.1142/S0219455419500925)] \
19 April 2019

**Deep digital twins for detection, diagnostics and prognostics** \
*Wihan Booyse, Daniel N. Wilke, Stephan Heyns* \
Mechanical Systems and Signal Processing [[Paper](https://doi.org/10.1016/j.ymssp.2019.106612)] \
1 February 2020

**An application of generative adversarial networks in structural health monitoring** \
*G.Tsialiamanis, E.Chatzi, N.Dervilis, D.J.Wagg, K.Worden* \
Proceedings of the XI International Conference on Structural Dynamics [[Paper](https://eprints.whiterose.ac.uk/169129/)] \
30 September 2020

**Deep-Learning-Based Bridge Condition Assessment by Probability Density Distribution Reconstruction of Girder Vertical Deflection and Cable Tension Using Unsupervised Image Transformation Model** \
*Yang Xu, Yadi Tian, Yufeng Zhang, Hui Li* \
European Workshop on Structural Health Monitoring [[Paper](https://link.springer.com/chapter/10.1007/978-3-030-64908-1_4)] \
09 January 2021

**Probabilistic vehicle weight estimation using physics-constrained generative adversarial network** \
*Yang Yu, C. S. Cai, Yongming Liu* \
Computer-Aided Civil and Infrastructure Engineering [[Paper](https://doi.org/10.1111/mice.12677)] \
30 March 2021

**On Generating Parametrised Structural Data Using Conditional Generative Adversarial Networks** \
*G. Tsialiamanis, D. J. Wagg, N. Dervilis, K. Worden* \
Data Science in Engineering [[Paper](https://link.springer.com/chapter/10.1007/978-3-030-76004-5_6)] \
17 May 2021

**A Generative Adversarial Network Based Autoencoder for Structural Health Monitoring** \
*Giorgia Colombera,Luca Rosafalco, Matteo Torzoni, Filippo Gatti, Stefano Mariani, Andrea Manzoni, Alberto Corigliano* \
Computuer Sciences Mathematic Forum [[Paper](https://www.mdpi.com/2813-0324/2/1/9)] \
22 September 2021

**Time-Domain Signal Synthesis with Style-Based Generative Adversarial Networks Applied to Guided Waves** \
*Mateusz Heesch, Krzysztof Mendrok, Ziemowit Dworakowski* \
 Artificial Intelligence and Soft Computing [[Paper](https://link.springer.com/chapter/10.1007/978-3-030-87986-0_7)] \
05 October 2021

**A Wasserstein generative adversarial network-based approach for real-time track irregularity estimation using vehicle dynamic responses** \
*Zhandong Yuan,Jun Luo,Shengyang Zhu, Wanming Zhai* \
Vehicle System Dynamics [[Paper](https://doi.org/10.1080/00423114.2021.1999480)] \
24 November 2021

**Deep generative Bayesian optimization for sensor placement in structural health monitoring** \
*Seyedomid Sajedi, Xiao Liang* \
IEEE [[Paper](https://doi.org/10.1111/mice.12799)] \
22 December 2021

**Generative Adversarial Networks for Data Generation in Structural Health Monitoring** \
*Furkan Luleci, F. Necati Catbas, Onur Avci* \
Frontiers in Built Environment [[Paper](https://www.frontiersin.org/articles/10.3389/fbuil.2022.816644)] \
11 February 2022

**Diagnostic-Quality Guided Wave Signals Synthesized Using Generative Adversarial Neural Networks** \
*Mateusz Heesch, Michał Dziendzikowski, Krzysztof Mendrok, Ziemowit Dworakowski* \
Sensors [[Paper](https://www.mdpi.com/1424-8220/22/10/3848)] \
19 May 2022

**Self-Supervised Metalearning Generative Adversarial Network for Few-Shot Fault Diagnosis of Hoisting System With Limited Data** \
*Yang Li, Feiyun Xu, Chi-Guhn Lee* \
IEEE [[Paper](https://ieeexplore.ieee.org/abstract/document/9783112)] \
27 May 2022

**Autoregressive Deep Learning Models for Bridge Strain Prediction** \
*Anastasios Panagiotis Psathas, Lazaros Iliadis, Dimitra V. Achillopoulou, Antonios Papaleonidas, Nikoleta K. Stamataki, Dimitris Bountas, Ioannis M. Dokas* \
Engineering Applications of Neural Networks [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-08223-8_13)] \
10 June 2022

**Dual generative adversarial networks for automated component layout design of steel frame-brace structures** \
*Bochao Fu, Yuqing Gao, Wei Wang* \
arXiv [[Paper](https://doi.org/10.1016/j.autcon.2022.104661)] \
25 November 2022

**In situ health monitoring of multiscale structures and its instantaneous verification using mechanoluminescence and dual machine learning** \
*Seong Yeon Ahn, Suman Timilsina, Ho Geun Shin, Jeong Heon Lee, Seong-Hoon Kim, Kee-Sun Sohn, Yong Nam Kwon 5, Kwang Ho Lee, Ji Sik Kim* \
iScience [[Paper](https://doi.org/10.1016/j.isci.2022.105758)] \
January 20, 2023

**Conditional deep generative models as surrogates for spatial field solution reconstruction with quantified uncertainty in Structural Health Monitoring applications** \
*Nicholas E. Silionis, Theodora Liangou, Konstantinos N. Anyfantis* \
arXiv [[Paper](https://doi.org/10.48550/arXiv.2302.08329)] \
14 February 2023

**Crack image generation algorithm based on deep convolutional generative adversarial network** \
*DingJun Zhang, MingChao Liao, XiXiang Wang, LaLao Gao* \
Second International Conference on Green Communication, Network, and Internet of Things [[Paper](https://doi.org/10.1117/12.2667214)] \
8 March 2023

**Reconstruction of long-term strain data for structural health monitoring with a hybrid deep-learning and autoregressive model considering thermal effects** \
*Chengbin Chen, Liqun Tang, Yonghui Lu, Yong Wang, Zejia Liu, Yiping Liu, Licheng Zhou, Zhenyu Jiang, Bao Yang* \
Engineering Structures [[Paper](https://doi.org/10.1016/j.engstruct.2023.116063)] \
7 April 2023

**A fast-response-generation method for single-layer reticulated shells based on implicit parameter model of generative adversarial networks** \
*Xiaonong Guo, Jindong Zhang, Shaohan Zong, Shaojun Zhu* \
Journal of Building Engineering [[Paper](https://doi.org/10.1016/j.jobe.2023.106563)] \
15 April 2023

**Acoustic Sensor Placement Optimization for Compressor Based on Adversarial Transfer Learning and Vibro-Acoustic Simulation** \
*Di Song, Junxian Shen,Tianchi Ma, Feiyun Xu* \
IEEE [[Paper](https://ieeexplore.ieee.org/abstract/document/10122886)] \
10 May 2023

**Generative adversarial network for predicting visible deterioration and NDE condition maps in highway bridge decks** \
*Amirali Najafi, John Braley, Nenad Gucunski, Ali Maher* \
Journal of Infrastructure Intelligence and Resilience [[Paper](https://www.sciencedirect.com/science/article/pii/S2772991523000178)] \
2 June 2023

**Implicit parametric modal expansion method for single-layer reticulated shells based on generative adversarial network** \
*Jindong Zhang, Xiaonong Guo, Shaohan Zong* \
Structures [[Paper](https://doi.org/10.1016/j.istruc.2023.05.151)] \
11 June 2023

**Generative adversarial networks for real-time realistic physics simulations** \
*Mark Harlow, Matthew Martinez, Xiaoyan Han, Stoian Borissov, Jason Hill* \
Proceedings Volume 12536, Thermosense: Thermal Infrared Applications XLV [[Paper](https://doi.org/10.1117/12.2663951)] \
12 June 2023

**Neural Extended Kalman Filters for Learning and Predicting Dynamics of Structural Systems** \
*Wei Liu, Zhilu Lai, Kiran Bacsa, Eleni Chatzi* \
Structural Health Monitoring [[Paper](https://doi.org/10.1177/14759217231179912)] \
29 June 2023

**A Data-Driven Based Response Reconstruction Method of Plate Structure with Conditional Generative Adversarial Network** \
*He Zhang, Chengkan Xu, Jiqing Jiang, Jiangpeng Shu, Liangfeng Sun, Zhicheng Zhang* \
Sensors [[Paper](https://doi.org/10.3390/s23156750)] \
28 July 2023

**Multi-modal generative adversarial networks for synthesizing time-series structural impact responses** \
*Zhymir Thompson, Austin R.J. Downey, Jason D. Bakos, Jie Wei, Jacob Dodson* \
Mechanical Systems and Signal Processing [[Paper](https://doi.org/10.1016/j.ymssp.2023.110725)] \
9 September 2023














### *Leveraging Generative AI for Anomaly/Novelty/Outlier Detection, Damage Diagnosis/Prognosis, Physics-based Modeling, and other Condition Assessment Techniques - (the studies here are not directly focused on content generation)*

**Variational autoencoder-based approach for rail defect identification** \
*Yuan Hao Wei, Yi Qing Ni* \
The Hong Kong Polytechnic University [[Paper](https://research.polyu.edu.hk/en/publications/variational-autoencoder-based-approach-for-rail-defect-identifica)] \
1 Jan 2019

**Deep Unsupervised Learning for Condition Monitoring and Prediction of High Dimensional Data with Application on Windfarm SCADA Data** \
*C. Mylonas, I. Abdallah & E. N. Chatzi* \
 Model Validation and Uncertainty Quantification [[Paper](https://link.springer.com/chapter/10.1007/978-3-030-12075-7_21)] \
31 May 2019

**Structural damage identification based on unsupervised feature-extraction via Variational Auto-encoder** \
*Xirui Ma, Yizhou Lin, Zhenhua Nie, Hongwei Ma* \
Measurement [[Paper](https://doi.org/10.1177/14759217221103016)] \
13 April 2020

**Toward data anomaly detection for automated structural health monitoring: Exploiting generative adversarial nets and autoencoders** \
*Jianxiao Mao, Hao Wang, Billie F Spencer, Jr* \
Structural Health Monitoring [[Paper](https://doi.org/10.1177/1475921720924601)] \
7 June 2020

**Infrastructure degradation and post-disaster damage detection using anomaly detecting generative adversarial networks** \
*S. M. Tilon, F. Nex, D. Duarte, N. Kerle, and G. Vosselman* \
ISPRS Ann. Photogramm. Remote Sens. Spatial Inf. Sci. [[Paper](https://isprs-annals.copernicus.org/articles/V-2-2020/573/2020/)] \
03 August 2020

**Wind Turbine Gearbox Failure Detection Based on SCADA Data: A Deep Learning-Based Approach** \
*Luoxiao Yang; Zijun Zhang* \
IEEE [[Paper](https://ieeexplore.ieee.org/abstract/document/9298851)] \
18 December 2020

**Post-Disaster Building Damage Detection from Earth Observation Imagery Using Unsupervised and Transferable Anomaly Detecting Generative Adversarial Networks** \
*Sofia Tilon,Francesco Nex,Norman Kerle, George Vosselman* \
Remote Sensing [[Paper](https://www.mdpi.com/2072-4292/12/24/4193)] \
21 December 2020

**Prognostics With Variational Autoencoder by Generative Adversarial Learning** \
*Yu Huang, Yufei Tang, James VanZwieten* \
IEEE [[Paper](https://ieeexplore.ieee.org/abstract/document/9339944)] \
28 January 2021

**Conditional variational autoencoders for probabilistic wind turbine blade fatigue estimation using Supervisory, Control, and Data Acquisition data** \
*Charilaos Mylonas, Imad Abdallah, Eleni Chatzi* \
Wind Energy [[Paper](https://doi.org/10.1002/we.2621)] \
11 February 2021

**VAE-TALSTM: a temporal attention and variational autoencoder-based long short-term memory framework for dam displacement prediction** \
*Xiaosong Shu, Tengfei Bao, Yangtao Li, Jian Gong & Kang Zhang* \
Engineering with Computers [[Paper](https://link.springer.com/article/10.1007/s00366-021-01362-2)] \
22 April 2021

**Bat Ant Lion Optimization-Based Generative Adversarial Network For Structural Heath Monitoring In IoT** \
*Yoganand S, Chithra S* \
The Computer Journal [[Paper](https://doi.org/10.1093/comjnl/bxab081)] \
07 June 2021

**Dam anomaly assessment based on sequential variational autoencoder and evidence theory** \
*Xiaosong Shu, Tengfei Bao, Ruichen Xu, Yangtao Li, Kang Zhang* \
Applied Mathematical Modelling [[Paper](https://doi.org/10.48550/arXiv.2308.05350)] \
27 June 2021

**Generative Adversarial Network for Damage Identification in Civil Structures** \
*Zahra Rastin, Gholamreza Ghodrati Amiri, Ehsan Darvishan* \
Shock and Vibration [[Paper](https://www.hindawi.com/journals/sv/2021/3987835/)] \
06 Sept 2021

**An unsupervised method based on convolutional variational auto-encoder and anomaly detection algorithms for light rail squat localization** \
*Zhandong Yuan, Shengyang Zhu, Chao Chang, Xuancheng Yuan, Qinglai Zhang, Wanming Zhai* \
Construction and Building Materials [[Paper](https://doi.org/10.1016/j.conbuildmat.2021.125563)] \
13 November 2021

**Toward a general unsupervised novelty detection framework in structural health monitoring** \
*Mohammad Hesam Soleimani-Babakamali, Reza Sepasdar, Kourosh Nasrollahzadeh, Ismini Lourentzou, Rodrigo Sarlo* \
Computer-Aided Civil and Infrastructure Engineering [[Paper](https://doi.org/10.1111/mice.12812)] \
21 January 2022

**Data anomaly detection for structural health monitoring using a combination network of GANomaly and CNN** \
*Gaoyang Liu, Yanbo Niu, Weijian Zhao, Yuanfeng Duan and Jiangpeng Shu* \
Smart Structures and Systems [[Paper](https://doi.org/10.12989/sss.2022.29.1.053)] \
29 January 2022

**A system reliability approach to real-time unsupervised structural health monitoring without prior information** \
*Mohammad Hesam Soleimani-Babakamali, Reza Sepasdar, Kourosh Nasrollahzadeh, Rodrigo Sarlo* \
Frontiers in Built Environment [[Paper](https://doi.org/10.1016/j.ymssp.2022.108913)] \
22 February 2022

**Unsupervised dam anomaly detection with spatial–temporal variational autoencoder** \
*Xiaosong Shu, Tengfei Bao, Yuhang Zhou, Ruichen Xu, Yangtao Li, Kang Zhang* \
Structural Health Monitoring [[Paper](https://doi.org/10.1177/14759217211073301)] \
4 April 2022

**A novel vision-based method for loosening detection of marked T-junction pipe fittings integrating GAN-based segmentation and SVM-based classification algorithms** \
*Xinjian Deng, Jianhua Liu, Hao Gong, Jiayu Huang* \
Journal of Intelligent Manufacturing  [[Paper](https://link.springer.com/article/10.1007/s10845-022-01948-7)] \
22 April 2022

**Variational AutoEncoder (VAE) Boosted Parametric Reduced Order Modelling (pROM)** \
*Konstantinoscc Vlachas, Thomas Simpson, Anthony Garland, Carianne Martinez, Dane Quinn, Eleni Chatzi,* \
6th Workshop on Nonlinear System Identification Benchmarks [[Paper](https://doi.org/10.3929/ethz-b-000601436)] \
26 April 2022

**Unsupervised deep learning method for bridge condition assessment based on intra-and inter-class probabilistic correlations of quasi-static responses** \
*Yang Xu, Yadi Tian, and Hui Li* \
Structural Health Monitoring [[Paper](https://doi.org/10.1177/14759217221103016)] \
21 May 2022

**RCNN-GAN: An Enhanced Deep Learning Approach Towards Detection of Road Cracks** \
*Shadrack Fred Mahenge, Stephen Wambura, Licheng Jiao* \
ICCDA 2022: 2022 The 6th International Conference on Compute and Data Analysis [[Paper](https://doi.org/10.1145/3523089.3523104)] \
23 May 2022

**Generative adversarial networks with fuzzy clustering on damage detection of rc beams using piezoceramic sensing signals** \
*YUAN Cheng, XIONG Qing-song, QIN Xiao-ming, XIONG Hai-bei, KONG Qing-zhao* \
Engineering Mechanics [[Paper](https://www.engineeringmechanics.cn/en/article/doi/10.6052/j.issn.1000-4750.2022.05.0480)] \
30 May 2022

**Anomaly Detection with Autoencoders as a Tool for Detecting Sensor Malfunctions** \
*Artur Liebert, Wolfgang Weber, Sebastian Reif, Bernd Zimmering, Oliver Niggemann* \
IEEE [[Paper](https://ieeexplore.ieee.org/abstract/document/9816908)] \
18 July 2022

**On an Application of Generative Adversarial Networks on Remaining Lifetime Estimation** \
*G. Tsialiamanis, D. Wagg, N. Dervilis, K. Worden* \
arXiv [[Paper](https://arxiv.org/abs/2208.08666)] \
18 August 2022

**Anomaly Detection by Unsupervised Adversarial Generative Self-labelling Autoencoder** \
*Deyi Zeng* \
IEEE [[Paper](https://doi.org/10.1109/ICAICA54878.2022.9844459)] \
05 August 2022

**Dam safety assessment through data-level anomaly detection and information fusion** \
*Yuhang Zhou, Xiaosong Shu, Tengfei Bao, Yangtao Li, Kang Zhang* \
Structural Health Monitoring [[Paper](https://doi.org/10.1177/14759217221117478)] \
16 August 2022

**Multiclass damage detection in concrete structures using a transfer learning-based generative adversarial networks** \
*Kyle Dunphy, Ayan Sadhu, Jinfei Wang* \
Structural Control and Health Monitoring [[Paper](https://doi.org/10.1002/stc.3079)] \
19 August 2022

**Adversarially-Trained Tiny Autoencoders for Near-Sensor Continuous Structural Health Monitoring** \
*Alessio Burrello; Giacomo Sintoni; Davide Brunelli; Luca Benini* \
IEEE [[Paper](https://ieeexplore.ieee.org/abstract/document/9869952)] \
5 September 2022

**Multi-objective variational autoencoder: an application for smart infrastructure maintenance** \
*Ali Anaissi, Seid Miad Zandavi, Basem Suleiman, Mohamad Naji & Ali Braytee* \
Applied Intelligence [[Paper](https://link.springer.com/article/10.1007/s10489-022-04163-2)] \
20 September 2022

**A comparative study of attention mechanism and generative adversarial network in facade damage segmentation** \
*Fangzheng Lin, Jiesheng Yang, Jiangpeng Shu, Raimar J. Scherer* \
arXiv [[Paper](https://arxiv.org/abs/2209.13283)] \
27 September 2022

**Modern Crack Detection for Bridge Infrastructure Maintenance Using Machine Learning** \
*Hafiz Suliman Munawar, Ahmed W. A. Hammad, S. Travis Waller & Md Rafiqul Islam* \
Human-Centric Intelligent Systems [[Paper](https://link.springer.com/article/10.1007/s44230-022-00009-9)] \
28 September 2022

**DEGAN: Time Series Anomaly Detection using Generative Adversarial Network Discriminators and Density Estimation** \
*Yueyan Gu, Farrokh Jazizadeh* \
arXiv [[Paper](https://arxiv.org/abs/2210.02449)] \
5 October 2022

**A deep generative model based on CNN-CVAE for wind turbine condition monitoring** \
*Jiarui Liu, Guotian Yang, Xinli Li, Shumin Hao, Yingming Guan, Yaqi Li* \
Measurement Science and Technology [[Paper](https://iopscience.iop.org/article/10.1088/1361-6501/aca496/meta)] \
6 December 2022

**An unsupervised structural health monitoring framework based on Variational Autoencoders and Hidden Markov Models** \
*Eduardo M. Coraça, Janito V. Ferreira, Eurípedes G.O. Nóbrega* \
Reliability Engineering & System Safety [[Paper](https://doi.org/10.1016/j.ress.2022.109025)] \
9 December 2022

**A GAN-based fault detection for dynamic process with deconvolutional networks** \
*Dapeng Zhang, Zhiwei Gao* \
IEEE [[Paper](https://ieeexplore.ieee.org/abstract/document/9976142)] \
15 December 2022

**Unsupervised structural damage detection based on an improved generative adversarial network and cloud model** \
*Yongpeng Luo, Xu Guo, Lin-Kun Wang, Jin-Ling Zheng, Jing-Liang Liu, Fei-Yu Liao* \
Journal of Low Frequency Noise, Vibration and Active Control [[Paper](https://journals.sagepub.com/doi/full/10.1177/14613484221150804)] \
12 January 2023

**Structural Nonlinear Model Updating Based on an Improved Generative Adversarial Network** \
*Zi-Qing Yuan, Yu Xin, Zuo-Cai Wang, Ya-Jie Ding, Jun Wang, Dong-Hui Wang* \
Structural Control and Health Monitoring [[Paper](https://www.hindawi.com/journals/schm/2023/9278389/)] \
07 February 2023

**Unsupervised learning-based framework for indirect structural health monitoring using adversarial autoencoder** \
*A. Calderon Hurtado, K. Kaur, M. Makki Alamdari, E. Atroshchenko, K.C. Chang, C.W. Kim* \
arXiv [[Paper](https://doi.org/10.1016/j.jsv.2023.117598)] \
11 February 2023

**VpROM: A novel Variational AutoEncoder-boosted Reduced Order Model for the treatment of parametric dependencies in nonlinear systems** \
*Thomas Simpson, Konstantinos Vlachas, Anthony Garland, Nikolaos Dervilis, Eleni Chatzi* \
arXiv [[Paper](https://arxiv.org/abs/2304.12437)] \
11 April 2023

**A Semi-Supervised Learning Approach for Pixel-Level Pavement Anomaly Detection** \
*Ruiqi Ren, Peixin Shi, Pengjiao Jia, Xiangyang Xu* \
IEEE [[Paper](https://ieeexplore.ieee.org/document/10106612)] \
21 April 2023

**Uncertainty-aware structural damage warning system using deep variational composite neural networks** \
*Kareem A. Eltouny, Xiao Liang* \
Earthquake Engineering & Structural Dynamics [[Paper](https://doi.org/10.1002/eqe.3892)] \
24 April 2023

**Zero-shot transfer learning for structural health monitoring using generative adversarial networks and spectral mapping** \
*Mohammad Hesam Soleimani-Babakamali, Roksana Soleimani-Babakamali, Kourosh Nasrollahzadeh, Onur Avci, Serkan Kiranyaz, Ertugrul Taciroglu* \
Mechanical Systems and Signal Processing [[Paper](https://doi.org/10.1016/j.ymssp.2023.110404)] \
9 May 2023

**Early Detection and Diagnosis of Wind Turbine Abnormal Conditions Using an Interpretable Supervised Variational Autoencoder Model** \
*Adaiton Oliveira-Filho, Adaiton Oliveira-Filho, Ryad Zemouri, Philippe Cambron, Antoine Tahan* \
Energies [[Paper](https://doi.org/10.3390/en16124544)] \
6 June 2023

**Microstructural image based convolutional neural networks for efficient prediction of full-field stress maps in short fiber polymer composites** \
*S. Gupta, T. Mukhopadhyay, V. Kushvaha* \
Defence Technology [[Paper](https://doi.org/10.1016/j.dt.2022.09.008)] \
23 June 2023

**Semi-Supervised Detection of Structural Damage Using Variational Autoencoder and a One-Class Support Vector Machine** \
*Andrea Pollastro; Giusiana Testa; Antonio Bilotta; Roberto Prevete* \
IEEE [[Paper](https://ieeexplore.ieee.org/document/10171358)] \
03 July 2023

**Concrete Crack Detection Using Deep Convolutional Generative Adversarial Network** \
*Biswajit Padhi, Motahar Reza, Md. Salman Shams & Arcot Navya Sai* \
Advanced Computing [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-35641-4_11)] \
14 July 2023

**Deep Representation Clustering of Multi-Type Damage Features Based on Unsupervised Generative Adversarial Network** \
*Feng-Liang Zhang, Xiao Li, Jun Lei, Wei Xiang* \
SSRN [[Paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4518296)] \
22 July 2023

**Deep generative models for unsupervised delamination detection using guided waves** \
*Mahindra Rautela, Amin Maghareh, Shirley Dyke, S. Gopalakrishnan* \
arXiv [[Paper](https://doi.org/10.48550/arXiv.2308.05350)] \
10 August 2023
