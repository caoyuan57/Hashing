# Hashing based Approximate Nearest Neighbor Search Methods: <span style="color: blue"> Papers + Codes </span>
## 😍Normal  
### 😄Single-Modal
* #### Traditional-Unsupervised  
***1998 STOC*** Approximate nearest neighbors: Towards removing the curse of dimensionality(`LSH`)[[Paper]](https://citeseerx.ist.psu.edu/viewdoc/download;jsessionid=1A183B4D95F7F4C394DFBDFD2DA950CC?doi=10.1.1.390.7411&rep=rep1&type=pdf)[[Code1]](https://github.com/RUSH-LAB/LSH_Memory)[[Code2]](https://github.com/TreezzZ/LSH_PyTorch)  
***2008 NIPS*** Spectral hashing(`SH`)[[Paper]](https://citeseerx.ist.psu.edu/viewdoc/download;jsessionid=0F054F33F2D7C9B0292947BF45BBB4A3?doi=10.1.1.304.2748&rep=rep1&type=pdf)[[Code]](https://github.com/BMC-SDNU/Cross-Modal-Hashing-Retrieval)  
***2010 ICML*** Sequential projection learning for hashing with compact codes(`SpH`)[[Paper]](https://citeseerx.ist.psu.edu/viewdoc/download;jsessionid=17F628E16E02D2B37040F60D02244BDA?doi=10.1.1.165.8208&rep=rep1&type=pdf)[[Code]](https://github.com/BMC-SDNU/Cross-Modal-Hashing-Retrieval)  
***2011 CVPR*** Iterative quantization: A procrustean approach to learning binary codes(`PCAH`)  
***2011 CVPR*** Iterative quantization: A procrustean approach to learning binary codes(`ITQ`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=5995432)[[Code]](http://sglab.kaist.ac.kr/Spherical_Hashing/)  
***2014 TCYB*** Density sensitive hashing(`DSH`)[[Paper]](https://arxiv.org/pdf/1205.2930v1.pdf)[[Code]](http://www.cad.zju.edu.cn/home/dengcai/Data/DSH.html)  
* #### Deep-Unsupervised  
***2015 CVPR*** Deep Hashing for Compact Binary Codes Learning(`DH`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7298862)  
***2016 CVPR/2019 TPAMI*** Learning compact binary descriptors with unsupervised deep neural networks(`DeepBit`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7780502)[[Code]](https://github.com/kevinlin311tw/cvpr16-deepbit)  
***2017 ICML*** Stochastic generative hashing(`SGH`)[[Paper]](https://arxiv.org/pdf/1701.02815.pdf)[[Code]](https://github.com/zhangcheng-007/Stochastic_Generative_Hashing)  
***2018 AAAI/2020 IJCV*** Binary generative adversarial networks for image retrieval(`BGAN`)[[Paper]](https://arxiv.org/pdf/1708.04150.pdf)[[Code]](https://github.com/ht014/BGAN)  
***2018 NIPS*** Greedy hash: Towards fast optimization for accurate hash coding in cnn(`GreedyHash`)[[Paper]](https://proceedings.neurips.cc/paper_files/paper/2018/file/13f3cf8c531952d72e5847c4183e6910-Paper.pdf)[[Code1]](https://github.com/ssppp/GreedyHash)[[Code2]](https://github.com/swuxyj/DeepHash-pytorch)  
***2018 NIPS*** Bingan: Learning compact binary descriptors with a regularized gan(`BinGAN`)[[Paper]](https://arxiv.org/pdf/1806.06778.pdf)[[Code]](https://github.com/maciejzieba/binGAN)  
***2018 IJCAI*** Semantic structure-based unsupervised deep hashing(`SSDH`)[[Paper]](https://www.ijcai.org/proceedings/2018/0148.pdf)[[Code]](https://github.com/yangerkun/IJCAI2018_SSDH)  
***2018 TPAMI*** Unsupervised deep hashing with similarity-adaptive and discrete optimization(`SADH`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8247210)[[Code]](https://github.com/xuyan1115/Similarity-Adaptive-Deep-Hashing)  
***2019 TIP*** Unsupervised Semantic-Preserving Adversarial Hashing for Image Search(`USPAH`)[[Paper]](http://www.ncbi.nlm.nih.gov/pubmed/30872226)  
***2019 CVPR*** DistillHash: Unsupervised deep hashing by distilling data pairs(`DistillHash`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8953280)[[Code]](https://github.com/tmllab/tongliang-liu.github.io/tree/master/code)  
***2019 IJCV*** Unsupervised binary(`DVB`)  
***2020 IJCAI*** MLS3RDUH: Deep Unsupervised Hashing via Manifold based Local Semantic(`MLS³RDUH`)[[Paper]](https://www.researchgate.net/publication/342793496_MLS3RDUH_Deep_Unsupervised_Hashing_via_Manifold_based_Local_Semantic_Similarity_Structure_Reconstructing)[[Code]](https://github.com/rongchengtu1/MLS3RDUH)  
***2020 CVPR*** Auto-encoding twin-bottleneck hashing(`TBH`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9157770)[[Code]](https://github.com/ymcidence/TBH)  
***2020 MM*** Deep Unsupervised Hybrid-similarity Hadamard Hashing(`DU3H`)[[Paper]](https://dl.acm.org/doi/pdf/10.1145/3394171.3414028)
***2021 AAAI*** Deep Unsupervised Image Hashing by Maximizing Bit Entropy(`DMBE`)[[Paper]](https://arxiv.org/pdf/2012.12334v1.pdf)[[Code1]](https://github.com/liyunqianggyn/Deep-Unsupervised-Image-Hashing)[[Code2]](https://github.com/swuxyj/DeepHash-pytorch)  
***2021 ICCV*** Self-supervised Product Quantization for Deep Unsupervised Image Retrieval(`SPQ`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9711357)[[Code]](https://github.com/youngkyunJang/SPQ)  
***2021 TCSVT*** Unsupervised Deep K-Means Hashing for Efficient Image Retrieval and Clustering(`UDKH`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9248040)  
***2021 TCSVT*** Unsupervised Deep Multi-Similarity Hashing With Semantic Structure for Image Retrieval(`UDMSH`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9234431)
***2021 IJCAI*** Unsupervised Hashing with Contrastive Information Bottleneck(`CJBHash`)[[Paper]](https://arxiv.org/pdf/2105.06138.pdf)[[Code]](https://github.com/zexuanqiu/CIBHash)
***2021 IJCAI*** CIMON: Towards High-quality Hash Codes(`CIMON`)[[Paper]](https://arxiv.org/pdf/2010.07804.pdf)
***2021 TIP*** Unsupervised Discrete Hashing With Affinity Similarity(`UDH`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9467816)
***2021 TMM*** Deep Unsupervised Self-Evolutionary Hashing for Image Retrieval(`DUSH`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9201108)
***2021 MM*** A Statistical Approach to Mining Semantic Similarity for Deep Unsupervised Hashing(`DATE`)[[Paper]](https://dl.acm.org/doi/pdf/10.1145/3474085.3475570)
***2021 ICME*** Deep Unsupervised Hashing by Global and Local Consistency
(`GLC`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9428094)
***2021 CIKM*** Deep Self-Adaptive Hashing for Image Retrieval(`DSAH`)[[Paper]](https://dl.acm.org/doi/pdf/10.1145/3459637.3482247)
***2022 AAAI*** Deep Unsupervised Hashing with Latent Semantic Components(`DSCH`)[[Paper]](https://arxiv.org/pdf/2203.09420.pdf)[[Code]](https://github.com/Bruce-XJChen/DSCH)
***2022 Neuro*** Unsupervised deep hashing with pretrained semantic information distillation and preservation(`PSIDP`)[[Paper]](https://pdf.sciencedirectassets.com/271597/1-s2.0-S0925231222X00283/1-s2.0-S0925231222007937/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDoaCXVzLWVhc3QtMSJHMEUCIQDLgzfVmYHNBLZWLiTEBDxh4beYNPBXXG9EfcIiBpqrvQIgQEi%2FyJNy43n3mv6VzH%2BXSFEhsA2UWx7nO%2FuRRteJML8qswUIEhAFGgwwNTkwMDM1NDY4NjUiDNJhBr7PTFvrgGJZcCqQBdcF%2FbCSMIpqIZBnIqk9Tj1PgMrrEz4IwLb3oOD9bs79yc5pl5vZcq5Xz8lpp7KBpMAvdcymL9vEJs0A59ltsPvjEoRB79Pp7%2Fyjvqq3NeUIdMnffyJA5B6RumO4GsIbD577B078s7PgeWU4a8twy2ydYYaMVK7vSSkS5MTFo2jCsP6zLoelngsWO9Map7rlIJf45T4L2TrGWVdZ%2F14ciwhY4FX8FETtCHUN7V2wu030ipIPwV1UvPJUD%2FPuSIE6PoAkyrlF7bvhn3LXkK0Ay3oz3tJAvY9kihaNbJkjMXqrG49h%2BU4sDqx7TswCEBcSUI5UkIkG4qk7LwPa6i13dv6Q9%2FhnRzg28yDDualSUN6DMcVFONaY9wXUGOZ1nsT2h4ENFaza8eYVFA%2F1eak3JJ9a9HikOsflUVfzspTePkU63yRCOeZ%2B%2BsvBWrLpIFiTKdy178CxfIvkD727qTBFoR1Hl%2FDtQKhoQMy0%2BsTQdcL79jwfpnGA4MzAHSSZPzgPg4sdWRougis9Z2cQf3iiJN1zFC%2F54VnEZspM0MyMA1iAYLNYip3CkBJ1KAdW5RA1W6JVR6S17XgvsogDE8xqpOeZKoecifQ0AWwbpPTSgHIO9xw6s9xux1tpZiGi%2F8JMMwQW4gwIfMbrpFKy0NsRV5auy5GQibH2TIRnnchjL%2FaiPEq4LM%2B3LyhQiDyDKe8Yj5xfblelMA4zp0s%2Buwv2i%2FeMuie%2FF6Gi6SyHK94%2B0GRK0fX9fqn8x2IvIgaXxHV%2F94HtLOTmyW1obmdqH%2BmmJGuVv8jjhXgO5BFncJZG3Pyi92%2FXrhevGwcteMIkm7O8clc0D4JR%2B2OHjlnImAb8VBgyY6elJKNtAWWPlE%2BSxkR%2BMJ38y6cGOrEBFXUT2joLpYmjtMNF4sCwvPVy2qNglKwVjZNxjYZvoPbRacS9Vim8Yt0eiAWKsUXQ0yJ%2Fl8fHNJ%2BEj9LHs86h%2BxSNFiyVSMeXqEyjdMqkzWzLdYV6ryDOa%2FOoxjHxHq98%2Ba3qhbHzoyPGwGRxKw%2FQsGLpTi0uy%2BlwsSlvo6%2BddksQEenom%2Fivcg%2B95wMcOTDci0cIZ49X7UyvZ2Z5ETUUS4NlEtL6B5D8m2ZXEinBwcpU&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20230902T095302Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYRXQYPEEC%2F20230902%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=6eac435448b888e143420aae23049c37569540d2ba5478b2999d01248b8b249e&hash=5f17cb5f5fd7c96afce3286cee2bae50a9aa179f04a44be297a406701463baaa&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0925231222007937&tid=spdf-c11a3eef-7d89-44a5-b6eb-99785ba6863b&sid=8d52d06d81c81041d25ae25-beecf9958990gxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=19085853545a030a545000&rr=8004dd17bbd38b45&cc=cn)[[Code]](https://github.com/reresearcher/PSIDP)
***2022 AAAI*** Contrastive Quantization with Code Memory for Unsupervised Image Retrieval(`MeCoQ`)[[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/20147/19906)[[Code]](https://github.com/gimpong/AAAI22-MeCoQ)
***2022 IJCAI*** Improved Deep Unsupervised Hashing with Fine-grained Semantic Similarity Mining for Multi-Label Image Retrieval(`HAMAN`)[[Paper]](https://www.ijcai.org/proceedings/2022/0175.pdf)
***2022 MM*** Improved Deep Unsupervised Hashing via Prototypical Learning(`PURPLE`)[[Paper]](https://dl.acm.org/doi/pdf/10.1145/3503161.3548403)
***2022 SPL*** Improve Deep Unsupervised Hashing via Structural
and Intrinsic Similarity Learning(`HashSIM`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9705618)[[Code]](https://github.com/FrankloveCQ/HashSIM)
***2023 TCSVT*** Deep Learning based Image Retrieval with Unsupervised Double Bit Hashing(`UDBH`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10103906)
***2023 TCSVT*** Unsupervised Hashing Retrieval via Efficient
Correlation Distillation(`CDUH`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10005297)
* #### Deep-Supervised  
***2014 SIGIR*** Supervised Hashing with Latent Factor Model(`LFH`)[[Paper]](https://dl.acm.org/doi/pdf/10.1145/2600428.2609600)[[Code]](https://github.com/TreezzZ/LFH_PyTorch)
***2015 CVPR*** Supervised Discrete Hashing(`SDH`)[[Paper]](https://openaccess.thecvf.com/content_cvpr_2015/papers/Shen_Supervised_Discrete_Hashing_2015_CVPR_paper.pdf)[[Code]](https://github.com/TreezzZ/SDH_PyTorch)
***2015 CVPR*** Deep Learning of Binary Hash Codes for Fast Image Retrieval(`DLBC`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7301269)[[Code]](https://github.com/flyingpot/pytorch_deephash)
***2016 CVPR*** Deep Supervised Hashing for Fast ImaDeep Supervised Hashing for Fast Image Retrievalge Retrieval(`DSH`)[[Paper]](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Liu_Deep_Supervised_Hashing_CVPR_2016_paper.pdf)[[Code1]](https://github.com/swuxyj/DeepHash-pytorch)[[Code2]](https://github.com/weixu000/DSH-pytorch)  
***2016 IJCAI*** Feature Learning based Deep Supervised Hashing with Pairwise Labels(`DPSH`)[[Paper]](https://arxiv.org/pdf/1511.03855.pdf)[[Code1]](https://github.com/swuxyj/DeepHash-pytorch)[[Code2]](https://github.com/jiangqy/DPSH-pytorch)  
***2016 AAAI*** Deep Hashing Network for Efficient Similarity Retrieval(`DHN`)[[Paper]](http://ise.thss.tsinghua.edu.cn/~mlong/doc/deep-hashing-network-aaai16.pdf)[[Code1]](https://github.com/swuxyj/DeepHash-pytorch)[[Code2]](https://github.com/thulab/DeepHash)  
***2016 ACCV*** Deep Supervised Hashing with Triplet Labels(`DTSH`)[[Paper]](https://doc.taixueshu.com/foreign/arXiv161203900.html)[[Code1]](https://github.com/swuxyj/DeepHash-pytorch)[[Code2]](https://github.com/Minione/DTSH)  
***2017 ICCV*** HashNet: Deep Learning to Hash by Continuation(`HashNet`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8237860)[[Code1]](https://github.com/swuxyj/DeepHash-pytorch)[[Code2]](https://github.com/thuml/HashNet)  
***2017 NIPS*** Deep Supervised Discrete Hashing(`DSDH`)[[Paper]](https://arxiv.org/pdf/1705.10999.pdf)[[Code1]](https://github.com/swuxyj/DeepHash-pytorch)[[Code2]](https://github.com/TreezzZ/DSDH_PyTorch)  
***2017 MM*** Deep Asymmetric Pairwise Hashing(`DAPH`)[[Paper]](https://cfm.uestc.edu.cn/~fshen/DAPH.pdf)[[Code]](https://github.com/swuxyj/DeepHash-pytorch)  
***2017 IJCAI*** Locality-Constrained Deep Supervised Hashing for Image Retrieval(`LCDSH`)[[Paper]](https://www.ijcai.org/proceedings/2017/0499.pdf)[[Code]](https://github.com/swuxyj/DeepHash-pytorch)  
***2017 TPAMI*** Supervised Learning of Semantics-Preserving Hash via Deep Convolutional Neural Networks(`SSDH`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7849132)[[Code]](https://github.com/kevinlin311tw/Caffe-DeepBinaryCode)
***2018 arXiv*** Instance Similarity Deep Hashing for Multi-Label Image Retrieval(`ISDH`)[[Paper]](https://arxiv.org/pdf/1803.02987.pdf)[[Code1]](https://github.com/swuxyj/DeepHash-pytorch)[[Code2]](https://github.com/pectinid16/ISDH-Tensorflow)  
***2018 AAAI*** Asymmetric Deep Supervised Hashing(`ADSH`)[[Paper]](https://arxiv.org/pdf/1707.08325.pdf)[[Code1]](https://github.com/swuxyj/DeepHash-pytorch)[[Code2]](https://github.com/TreezzZ/ADSH_PyTorch)[[Code3]](https://github.com/jiangqy/ADSH-AAAI2018)  
***2018 IJCAI*** Semantic Structure-based Unsupervised Deep Hashing(`SSDH`)[[Paper]](https://see.xidian.edu.cn/faculty/chdeng/Welcome%20to%20Cheng%20Deng's%20Homepage_files/Papers/Conference/IJCAI2018_Yang.pdf)[[Code]](https://github.com/TreezzZ/SSDH_PyTorch)
***2018 CVPR*** Deep cauchy hashing for hamming space retrieval(`DCH`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8578232)[[Code1]](https://github.com/swuxyj/DeepHash-pytorch)[[Code2]](https://github.com/BMC-SDNU/Cross-Modal-Hashing-Retrieval)  
***2018 CVPR*** Dual Asymmetric Deep Hashing Learning(`DADH`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8758410)[[Code]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8758410)
***2019 BMVC*** Push for Quantization: Deep Fisher Hashing(`DFH`)[[Paper]](https://arxiv.org/pdf/1909.00206.pdf)[[Code1]](https://github.com/swuxyj/DeepHash-pytorch)[[Code2]](https://github.com/liyunqianggyn/Push-for-Quantization-Deep-Fisher-Hashing)  
# 下次继续 #
***2019 TMM*** Improved Deep Hashing with Soft Pairwise Similarity for Multi-label Image(`IDHN`)[[Paper]](https://arxiv.org/pdf/1803.02987.pdf)[[Code1]](https://github.com/swuxyj/DeepHash-pytorch)[[Code2]](https://github.com/pectinid16/IDHN)  
***2019 ICCV*** Deep Supervised Hashing with Anchor Graph(`DAGH`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9010953)[[Code1]](https://github.com/swuxyj/DeepHash-pytorch)[[Code2]](https://www.scholat.com/personalPaperList.html?Entry=laizhihui&selectType=allPaper)  
***2019 IEEE ACCESS*** Deep Supervised Hashing Based on Stable Distribution(`DHSHD`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8648432)[[Code]](https://github.com/swuxyj/DeepHash-pytorch)  
***2019 Neuro*** Deep balanced discrete hashing for image retrieval(`DBDH`)[[Paper]](https://www.nstl.gov.cn/paper_detail.html?id=9a19912e72e38fd09e0a9e2a0c5eb1cf)[[Code]](https://github.com/swuxyj/DeepHash-pytorch)  
***2020 CVPR*** Central Similarity Quantization for Efficient Image and Video Retrieval(`CSQ`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9156349)[[Code1]](https://github.com/swuxyj/DeepHash-pytorch)[[Code2]](https://github.com/yuanli2333/Hadamard-Matrix-for-hashing)  
***2014 SIGIR*** Supervised Hashing with Latent Factor Model(`LFH`)[[Code]](https://github.com/TreezzZ/LFH_PyTorch)  
***2015 CVPR*** Supervised Discrete Hashing(`SDH`)[[Code]](https://github.com/TreezzZ/SDH_PyTorch)  
***2018 TPAMI*** Supervised Learning of Semantics-Preserving Deep Hashing(`SSDH`)[[Code]](https://github.com/kevinlin311tw/Caffe-DeepBinaryCode)  
***2018 IJCAI*** Semantic Structure-based Unsupervised Deep Hashing(`SSDH`)[[Code]](https://github.com/TreezzZ/SSDH_PyTorch)  
***2018 CVPR*** Dual Asymmetric Deep Hashing Learning(`DADH`)[[Code]](https://github.com/deepakks1995/DeepHashing)  
***2020 CVPR*** Self-supervised asymmetric deep hashing with margin-scalable constraint(`SADH`)[[Paper]](https://arxiv.org/pdf/2012.03820v2.pdf)[[Code]](https://github.com/SWU-CS-MediaLab/SADH)  
***2020 ECCV*** Targeted Attack for Deep Hashing based Retrieval(`DHTA`)[[Code]](https://github.com/jiawangbai/DHTA-master)  
***2020 NIPS*** One Loss for All: Deep Hashing with a Single Cosine Similarity based Learning Objective(`OrthoHash`)[[Code]](https://github.com/kamwoh/orthohash)  
***2022 MM*** HyP2 Loss : Beyond Hypersphere Metric Space for Multi-label Image Retrieval(`HyP2-Loss`)[[Code]](https://github.com/JerryXu0129/HyP2-Loss)  
### 😄Cross-Modal  
* #### Traditional-Unsupervised  
***2010 CVPR*** Data fusion through cross-modality metric learning using similarity-sensitive hashing(`CMSSH`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=5539928)
***2011 IJCAI*** Learning hash functions for cross-view similarity search(`CVH`)[[Paper]](https://www.ijcai.org/Proceedings/11/Papers/230.pdf)[[Code]](https://github.com/BMC-SDNU/Cross-Modal-Hashing-Retrieval)  
***2013 SIGKDD*** Inter-media hashing for large-scale retrieval from heterogeneous data sources(`IMH`)[[Paper]](https://dl.acm.org/doi/pdf/10.1145/2463676.2465274)[[Code]](https://github.com/BMC-SDNU/Cross-Modal-Hashing-Retrieval)  
***2013 MM*** Linear cross-modal hashing for efficient multimedia search(`LCMH`)[[Paper]](https://dl.acm.org/doi/pdf/10.1145/2502081.2502107)  
***2014 CVPR*** Collective matrix factorization hashing for multimodal data(`CMFH`)[[Paper]](https://openaccess.thecvf.com/content_cvpr_2014/papers/Ding_Collective_Matrix_Factorization_2014_CVPR_paper.pdf)[[Code1]](https://github.com/SachJbp/Cross-Modal-Retrieval-using-CMFH)[[Code2]](https://github.com/BMC-SDNU/Cross-Modal-Hashing-Retrieval)  
***2014 SIGIR*** Latent semantic sparse hashing for cross_x005f modal similarity search(`LSSH`)[[Paper]](https://dl.acm.org/doi/pdf/10.1145/2600428.2609610)[[Code]](https://github.com/BMC-SDNU/Cross-Modal-Hashing-Retrieval)  
***2017 CVPR*** Cross-Modality Binary Code Learning via Fusion Similarity Hashing(`FSH`)[[Paper]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Liu_Cross-Modality_Binary_Code_CVPR_2017_paper.pdf)[[Code]](https://github.com/LynnHongLiu/FSH)  
***2017 TCYB*** Semi-paired discrete hashing: Learning latent hash codes for semi-paired cross-view retrieval(`SPDH`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7570179)  
***2018 TCSVT*** Robust and flexible discrete hashing for cross-modal similarity search(`RFDH`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7967838)[[Code]](https://github.com/Wangdi-Xidian/RFDH)  
* #### Deep-Unsupervised  
***2018 AAAI*** Unsupervised Generative Adversarial Cross-modal Hashing(`UGACH`)[[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/11263/11122)[[Code1]](https://github.com/PKU-ICST-MIPL/UGACH_AAAI2018)[[Code2]](https://github.com/zjmonk/UGACH)  
***2018 CVPR*** Self-Supervised Adversarial Hashing Networks for Cross-Modal Retrieval(`SSAH`)[[Paper]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Li_Self-Supervised_Adversarial_Hashing_CVPR_2018_paper.pdf)[[Code1]](https://github.com/zyfsa/cvpr2018-SSAH)[[Code2]](https://github.com/SincereJoy/SSAH_CVPR2018)[[Code3]](https://github.com/lelan-li/SSAH)[[Code4]](https://github.com/haitao-hub-stu/SSAH)[[Code5]](https://github.com/BMC-SDNU/Cross-Modal-Hashing-Retrieval)  
***2018 ECCV*** Attention-aware Deep Adversarial Hashing for Cross-Modal Retrieval(`ADAH`)[[Paper]](https://openaccess.thecvf.com/content_ECCV_2018/papers/Xi_Zhang_Attention-aware_Deep_Adversarial_ECCV_2018_paper.pdf)[[Code]](https://github.com/zhongzhh8/Cross-Modal-Retrieval)  
***2018 IJCAI*** Unsupervised Deep Hashing via Binary Latent Factor Models for Large-scale Cross-modal(`UDCMH`)[[Paper]](https://www.ijcai.org/Proceedings/2018/0396.pdf)  
***2018 TMM*** Deep Binary Reconstruction for Cross-modal Hashing(`DBRC`)[[Paper]](https://arxiv.org/pdf/1708.05127.pdf)  
***2019 MM*** Deep binary reconstruction for cross-modal hashing(`DBRC`)[[Paper]](https://arxiv.org/pdf/1708.05127.pdf)
***2019 KDS*** Multimodal adversarial network for cross-modal retrieval(`MAN`)[[Paper]](https://pdf.sciencedirectassets.com/271505/1-s2.0-S0950705119X00167/1-s2.0-S0950705119302230/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDkaCXVzLWVhc3QtMSJGMEQCIDXTP59DDRedGdEVlC0LPhh8QB5rfvkdLVUt010ptbNlAiA5WPG4CjCQTd9M1HUvlYBbgNq4neuiDNH60GeoZFM2ZCqzBQgREAUaDDA1OTAwMzU0Njg2NSIMUQaySFFXyxlImzE7KpAFvxMvtme0xzdysBYqDH7IxHtCtM2rphOPnb14DKchaVu7xgjsKEn5knN2vhxj9CPWT%2F578RQFqA8EmX5aQaEHvcsUMcFjZagGhgkgKt5dD55CBnOZpzSH0TX%2B87ktAkgP3Gb4iPfduQa%2F6Sw5eTeRk4tmONE0Iqy0hawBL%2FqBCjdr2JzaHG8guLe2bOkhPjbl%2B6xM%2BYDb9TlOWbobhqSJ5c5%2BchntTcMcixo94b7QVLet99THUuU%2FPJOIyu4VKwAbr3RWZBMuki2t%2FUry9%2BUlkMLnLLQ8K%2FphNMQA30aUEuViaYXoZ%2B6MDtyq5Vn%2FUwQ%2Blz0xfDDd7dQ6Mhfwklwwu7p8mfusv4D%2BTI9fx2a02%2Fkczw4Tl9dzSfbHA3D1%2FQZtIgQYR4sOiKtDUFO%2F31LWVUzefA%2BwFdXFWXXyjv8fk4KY3p75YV8sHDU7PW5ozA07G0LIH%2Fkp8hF9ptgB4Jag4xXw2wkqctyGZhoTYB83d0L%2BMn1DFLNKCa5kjPzXw9SsRm6PirmcQMASrm1fpcfg0t0S%2FEzdCm0IupyYgcqPB2L57o9QFrpIXnTax1gGzu4ZFGqrBxSAlPdZYDH3lG1nAjwoq%2BXATXjAiKCQT6dIkEn42jycSatLEIJUPFXyP9UIXuChc8YBF9V4xFmVERqH7%2Bibb0sNaYp8YMn%2F5iZBd5PUSQYq1y6QUGHxzDuBhnKfrd%2F5nQQ4YVdULMp%2FpfzHputTwHbJiFCC1d9hNHFHbOpYQ%2B5mhkDMNwa8ug4foafCcuQJSyWNhlVRUDYWxMqO4lA0GebiI17RMGnnWPKay28hHt6UUhx6Fp29K1cIhe%2B8gnNizavcSZL%2BKYa5Z3S5Log4FWEbpaPZZDj4Y4coxc0w3N%2FLpwY6sgFMyKqnLH5Iu8WP36OlvG8OhB10%2BN5tve6UL8qn8kwjAmpa6B7LGxPT26yAhS%2BEoaL1Z25E3VNnnDqyElJ522hwBnjNx6PcX1t7BObf4hIWhhjAEfngC%2FrT1Nv9HhHo3QRBBdwOHtY7%2BKKgtwO2Hshzk570Hr%2Bp3m1nKrh590n%2BBhA6JbvvDokKo3%2F4sPhEi3xtCPfF208lpKtxZaPgEzHhdEfkyVbgahw3M4%2BopWqhYkVk&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20230902T092721Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTY7WZNYJXC%2F20230902%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=584b57f20e91247fe48375dd470402ba3236fa0375f1533cd3d7fb31ea80116c&hash=c2e79bc666e6c78db4398d78a6bcac00c127284f003c7f1a77b15ae78c209ffd&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0950705119302230&tid=spdf-277725a3-3fd4-4476-808f-b241ee7e47fc&sid=ef66f5cb8d5f324477799415b58537176495gxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=19085853545a0559525153&rr=8004b7761eb01228&cc=cn)[[Code]](https://github.com/penghu-cs/MAN)  
***2019 TOMM*** Cross-modal Generative Adversarial Networks for Common Representation Learning(`CMGANS`)[[Paper]](https://dl.acm.org/doi/pdf/10.1145/3284750)[[Code]](https://github.com/PKU-ICST-MIPL/CM-GANS_TOMM2019)  
***2019 ICCV*** Joint-Semantics Reconstructing Hashing for Large-Scale Unsupervised Cross-Modal Retrieval(`DJSRH`)[[Paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Su_Deep_Joint-Semantics_Reconstructing_Hashing_for_Large-Scale_Unsupervised_Cross-Modal_Retrieval_ICCV_2019_paper.pdf)[[Code1]](https://github.com/zs-zhong/DJSRH)[[Code2]](https://github.com/BMC-SDNU/Cross-Modal-Hashing-Retrieval)  
***2020 ICMR*** Deep Adversarial Discrete Hashing for Cross-Modal Retrieval(`DADH`)[[Paper]](https://dl.acm.org/doi/pdf/10.1145/3372278.3390711)[[Code]](https://github.com/Zjut-MultimediaPlus/DADH)  
***2020 IJCNN*** Unsupervised_Deep_Imputed_Hashing_for_Partial_Cross-modal_Retrieval(`UDIH`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9206611)[[Code]](http://github.com/AkChen/UDIH)  
***2020 TMM*** Multi-pathway Generative Adversarial Hashing for Unsupervised Cross-modal Retrieval(`MGAH`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8734835)[[Code]](https://github.com/PKU-ICST-MIPL/MGAH_TMM2019)  
***2020 ICMR*** Deep Semantic-Alignment Hashing for Unsupervised Cross-Modal Retrieval(`DSAH`)[[Paper]](https://dl.acm.org/doi/pdf/10.1145/3372278.3390673)[[Code]](https://github.com/idejie/DSAH)  
***2020 SIGIR*** Joint-modal Distribution-based Similarity Hashing for Large-scale Unsupervised Deep Cross-modal Retrieval(`JDSH`)[[Paper]](https://dl.acm.org/doi/pdf/10.1145/3397271.3401086)[[Code1]](https://github.com/KaiserLew/JDSH)[[Code2]](https://github.com/BMC-SDNU/Cross-Modal-Hashing-Retrieval)  
***2020 CVPR*** Creating Something from Nothing Unsupervised Knowledge Distillation for Cross-Modal Hashing(`UKD`)[[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Hu_Creating_Something_From_Nothing_Unsupervised_Knowledge_Distillation_for_Cross-Modal_Hashing_CVPR_2020_paper.pdf)[[Code]](https://github.com/huhengtong/UKD_CVPR2020)  
***2021 ICASSP*** Deep Adversarial Quantization Network for Cross-modal Retrieval(`DAQN`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9414247)[[Code]](https://github.com/zhouyu1996/DAQN)  
***2021 AAAI*** Similarity Reasoning and Filtration for Image-Text Matching(`SGRAF`)[[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/16209/16016)[[Code]](https://github.com/Paranioar/SGRAF)  
***2021 AAAI*** Deep Graph-neighbor Coherence Preserving Network for Unsupervised Cross-modal Hashing(`DGCPN`)[[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/16592/16399)[[Code]](https://github.com/Atmegal/DGCPN)  
***2021 TCSVT*** Deep Multiscale Fusion Hashing for Cross-Modal Retrieval(`DMFH`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9001018)
***2021 TCSVT*** Fast Unmediated Hashing for Cross-Modal Retrieval(`FUH`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9285286)
***2021 TKDE*** BATCH A Scalable Asymmetric Discrete Cross-Modal Hashing(`BATCH`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9001235)
***2021 TMM*** Mask Cross-Modal Hashing Networks(`MDCH`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9055057)
***2021 TPAMI*** MTFH A Matrix Tri-Factorization Hashing Framework for Efficient Cross-Modal Retrieval(`MTFH`)[[Paper]](http://i.uran.ru/webcab/system/files/journalspdf/ieee-transactions-pattern-analysis-and-machine-intelligence/ieee-transactions-pattern-analysis-and-machine-intelligence-2021-vol43-n-3/1-321.pdf)
***2021 AAAI*** Dual Adversarial Graph Neural Networks for Multi-label Cross-modal Retrieval(`DAGNN`)[[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/16345/16152)
***2021 MM*** Joint-teaching: Learning to Refine Knowledge for Resource-constrained Unsupervised Cross-modal Retrieval(`JOG`)[[Paper]](https://dl.acm.org/doi/pdf/10.1145/3474085.3475286)
***2022 TKDE*** Correlation-Identity Reconstruction Hashing for Unsupervised Cross-modal Retrieval(`CIRH`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9933831)[[Code]](https://github.com/XizeWu/CIRH)  
***2022 TCSVT*** Deep Adaptively-Enhanced Hashing with Discriminative Similarity Guidance for Unsupervised Cross-modal Retrieval(`DAEH`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9768805)[[Code]](https://github.com/reresearcher/DAEH)  
***2022 arXiv*** Deep Unsupervised Contrastive Hashing for Large-Scale Cross-Modal Text-Image Retrieval in Remote Sensing(`DUCH`)[[Paper]](https://arxiv.org/pdf/2201.08125.pdf)[[Code]](https://github.com/comrados/duch)  






***2023 TPAMI*** Unsupervised Contrastive Cross-modal Hashing(`UCCH`)
[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9782584)[[Code]](https://github.com/penghu-cs/UCCH)  
* #### Deep-Supervised  
***2017 CVPR*** Deep Cross-Modal Hashing(`DCMH`)[[Code1]](https://github.com/jiangqy/DCMH-CVPR2017)[[Code2]](https://github.com/WendellGul/DCMH)[[Code3]](https://github.com/WangGodder/deep-cross-modal-hashing)[[Code4]](https://github.com/jiangqy/DCMH-CVPR2017/tree/master/DCMH_matlab/DCMH_matlab)[[Code5]](https://github.com/BMC-SDNU/Cross-Modal-Hashing-Retrieval)  
***2017 MM*** Adversarial Cross-Modal Retrieval(`ACMR`)[[Code]](https://github.com/cuishuhao/ACMR)  
***2017 AAAI*** Collective Deep Quantization for Efficient Cross-Modal Retrieval(`CDQ`)[[Code]](https://github.com/caoyue10/aaai17-cdq)  
***2017 ICIP*** Label Consistent Matrix Factorization based Hashing for Cross Modal Retrieval(`LCMFH`)[[Code]](https://github.com/devraj89/LABEL-CONSISTENT-MATRIX-FACTORIZATION-BASED-HASHING-FOR-CROSS-MODAL-RETRIEVAL)  
***2018 TCYB*** Semi-supervised Cross-modal Hashing by Generative Adversarial Network(`SCHGAN`)[[Code]](https://github.com/PKU-ICST-MIPL/SCHGAN_TCYB2018)  
***2018 DASFAA*** Subspace Relation Learning for Cross-modal Hashing(`SRLCH`)[[Code]](https://github.com/llcing/Cross-modal-hashing-SRLCH)  
***2018 TIP*** Generalized Semantic Preserving Hashing for Cross-Modal Retrieval(`GPSH`)[[Code]](https://github.com/devraj89/GPSH-algorithm)  
***2019 ICMR*** Adversary Guided Asymmetric Hashing for Cross-Modal Retrieval(`TFNH`)[[Code]](https://github.com/hutt94/TFNH)  
***2019 SIGIR*** Scalable Deep Multimodal Learning for Cross-Modal Retrieval(`SDML`)[[Code]](https://github.com/penghu-cs/SDML)  
***2019 SIGIR*** Deep Collaborative Discrete Hashing With Semantic-Invariant Structure Construction(`DCDH`)[[Code]](https://github.com/DarrenZZhang/DCDH)  
***2019 CVPR*** Deep Supervised Cross-modal Retrieval(`DSCMR`)[[Code]](https://github.com/penghu-cs/DSCMR)  
***2019 ICMR*** Adversary Guided Asymmetric Hashing for Cross-Modal Retrieval(`AGAH`)[[Code]](https://github.com/WendellGul/AGAH)  
***2019 TIP*** Discrete Latent Factor Model for Cross-Modal Hashing(`DLFH`)[[Code1]](https://github.com/jiangqy/DLFH-TIP2019)[[Code2]](https://github.com/BMC-SDNU/Cross-Modal-Hashing-Retrieval)  
***2019 TPAMI*** MTFH: A Matrix Tri-Factorization Hashing Framework for Efficient Cross-Modal Retrieval(`MTFH`)[[Code]](https://github.com/starxliu/MTFH)  
***2020 Neuro*** Self-Constraining and Attention-based Hashing Network for Bit-Scalable Cross-Modal Retrieval(`SCAHN`)[[Code]](https://github.com/SWU-CS-MediaLab/SCAHN)  
***2020 TKDE*** BATCH:A Scalable Asymmetric Discrete Cross-Modal Hashing(`BATCH`)[[Code1]](https://github.com/yxinwang/BATCH-TKDE2020)[[Code]](https://github.com/BMC-SDNU/Cross-Modal-Hashing-Retrieval)  
***2020 MM*** Supervised Hierarchical Deep Hashing for Cross-Modal Retrieval(`SHDCH`)[[Code]](https://github.com/SDU-MIMA/SHDCH)  
***2020 TKDE*** Deep Cross-Modal Hashing with Hashing Functions and Unified Hash Codes Jointly Learning(`DCHUC`)[[Code1]](https://github.com/rongchengtu1/DCHUC)[[Code2]](https://github.com/BMC-SDNU/Cross-Modal-Hashing-Retrieval)  
***2020 TIP*** Multi-task consistency-preserving adversarial hashing for corss-modal retrieval(`CPAH`)[[Code]](https://github.com/comrados/cpah)  
***2021 TCYB*** Fast Cross-Modal Hashing with Global and Local Similarity Embedding(`FCMH`)[[Code]](https://github.com/yxinwang/FCMH-TCyb2021)  
***2021 ICME*** Efficient Fine-Grained Visual-Text Search Using Adversarially-Learned Hash Codes(`ADV`)[[Code]](https://github.com/muziyongshixin/adv_cross_modal_hashing)  
***2021 SP*** Multi-Label Semantics Preserving based Deep Cross-Modal Hashing(`MLSPH`)[[Code]](https://github.com/SWU-CS-MediaLab/MLSPH)  
***2021 TNNLS*** FDDH: Fast Discriminative Discrete Hashing for Large-Scale Cross-Modal Retrieval(`FDDH`)[[Code]](https://github.com/starxliu/FDDH)  
***2021 TKDE*** Adaptive Label Correlation Based Asymmetric Discrete Hashing for Cross-modal Retrieval(`ALECH`)[[Code]](https://github.com/czhangnju/ALECH)  
***2022 MM*** Differentiable Cross-modal Hashing via Multimodal Transformers(`DCMHT`)[[Code]](https://github.com/kalenforn/DCHMT)  
***2022 Neuro*** Multi-label enhancement based self-supervised deep cross-modal hashing(`MESDCH`)[[Code]](https://github.com/SWU-CS-MediaLab/MESDCH)  
***2022 TMM*** Teacher-Student Learning: Efficient Hierarchical Message Aggregation Hashing for Cross-Modal Retrieval(`HMAH`)[[Code]](https://github.com/FutureTwT/HMAH)  
***2022 IS*** Semi-Supervised Cross-Modal Hashing with Multi-view Graph Representation(`MGCH`)[[Code]](https://github.com/AliceShen122/MGCH)  
***2022 TKDE*** Weakly-Supervised Enhanced Semantic-Aware Hashing for Cross-Modal Retrieval(`WASH`)[[Code]](https://github.com/czhangnju/WASH)  
***2022 TOIS*** Efficient Query-based Black-Box Attack against Cross-modal Hashing Retrieval(`EQB2A`)[[Code]](https://github.com/tswang0116/EQB2A)  
***2022 TCSVT*** A High-Dimensional Sparse Hashing Framework for Cross-Modal Retrieval(`HSCH`)[[Code]](https://github.com/yxinwang/HSCH-TCSVT)  
***2022 TNNLS*** Graph Convolutional Network Discrete Hashing for Cross-Modal Retrieval(`GCDH`)[[Code]](https://github.com/Zjut-MultimediaPlus/GCDH)  
***2022 TKDE*** Modality-Invariant Asymmetric Networks for Cross-Modal Hashing -- PyTorch Implementation(`MIAN`)[[Code]](https://github.com/E-Galois/MIAN)  
***2022 JoI*** A Framework for Enabling Unpaired Multi-Modal Learning for Deep Cross-Modal Hashing Retrieval(`UMML`)[[Code]](https://github.com/MikelWL/UMML)  
***2022 arXiv*** Prototype-Based Layered Federated Cross-Modal Hashing(`PLFedCMH`)[[Code]](https://github.com/CarreLiu/PLFedCMH)  
***2022 arXiv*** Adaptive Marginalized Semantic Hashing for Unpaired Cross-Modal Retrieval(`AMSH`)[[Code]](https://github.com/LKYLKYZ/AMSH)  
****
## 😍Graph  
### 😄Single-Modal  
* #### Unsupervised  
***2021 MM*** Two-pronged Strategy Lightweight Augmented Graph Network Hashing for Scalable Image Retrieval(`LAGNH`)[[Code1]](https://github.com/christinecui/LAGNH)[[Code2]](https://github.com/chenyd7/LGCNH)  
* #### Supervised  
***2020 TCYB*** Graph Convolutional Network Hashing(`GCN`)[[Code]](https://github.com/zxJohnFly/GCN)  
### 😄Cross-Modal  
* #### Unsupervised  
***2022 TMM*** Aggregation-Based Graph Convolutional Hashing for Unsupervised Cross-Modal Retrieval(`AGCH`)  
* #### Supervised  
***2021 MM*** Local Graph Convolutional Networks for Cross-Modal Hashing(`LGCNH`)[[Code]](https://github.com/chenyd7/LGCNH)  
***2019 IJCAI*** Graph Convolutional Network Hashing for Cross-Modal Retrieval(`GCH`)[[Code]](https://github.com/DeXie0808/GCH)  
***2020 ICIP*** Semi-Supervised_Graph_Convolutional_Hashing_Network_For_Large-Scale_Cross-Modal_Retrieval(`SGCN`)[[Code]](https://github.com/flyingjohn/Cross_Modal_GCN)  
***2021 MM*** Graph Convolutional Multi-modal Hashing for Flexible Multimedia Retrieval(`GCMH`)  
***2022 TMM*** Adaptive Label-Aware Graph Convolutional Networks for Cross-Modal Retrieval(`ALGCN`)[[Code]](https://github.com/LivXue/ALGCN)  
****
## 😍Online  
### 😄Single-Modal  
* #### Traditional-Supervised  
***2013 IJCAI*** Online hashing(`OKH`)[[Code]](https://github.com/chenshen03/OnlineHash)  
***2015 ICCV*** Adaptive hashing for fast similarity search(`AdaptHash`)[[Code]](https://github.com/chenshen03/OnlineHash)  
***2015 ICIP*** Online supervised hashing(`OSH`)[[Code]](https://github.com/chenshen03/OnlineHash)  
***2017 ICCV/2019 TPAMI*** Online Hashing with Mutual Information(`MIHash`)[[Code]](https://github.com/fcakir/mihash)  
***2018 MM*** Supervised Online Hashing via Hadamard Codebook Learning(`HCOH`)[[Code1]](https://github.com/TreezzZ/HCOH_Pytorch)[[Code2]](https://github.com/lmbxmu/mycode/tree/master/2018ACMMM_HCOH)  
***2019 AAAI*** Towards Optimal Discrete Online Hashing with Balanced Similarity(`BSODH`)[[Code]](https://github.com/lmbxmu/mycode/tree/master/2019AAAI_BSODH)  
***2019 AAAI*** Online Hashing with Efficient Updating of Binary Codes(`OHWEU`)[[Code]](https://github.com/zyweng2pku/online_hashing_with_effcient_updating)  
***2019 TPAMI*** Fast Class-wise Updating for Online Hashing(`FCOH`)  
***2019 CLUSTER*** Parallel image search application based on online hashing hierarchical ranking(`MAPREDUCE`)  
***2019 Neuro*** A fast online spherical hashing method based on data sampling for large scale image retrieval(`OSpH`)  
***2019 ACCESS*** Online Supervised Sketching Hashing for Large-Scale Image Retrieval(`OSSH`)  
***2020 TIP*** Similarity-Preserving Linkage Hashing for Online Image Retrieval(`SPLH`)  
***2020 SIGIR*** Online Collective Matrix Factorization Hashing for Large-Scale Cross-Media Retrieval(`OCMFH`)  
***2020 IJCV*** Hadamard Matrix Guided Online Hashing(`HMOH`)[[Code]](https://github.com/lmbxmu/mycode/tree/master/2020IJCV_HMOH)  
***2021 arXiv*** Online Hashing with Similarity Learning(`OHSL`)  
***2021 ICME*** Weakly-Supervised Online Hashing(`WHO`)  
***2021 TMM*** Online Hashing With Bit Selection for Image Retrieval(`OSelH`)  
***2021 JVCIR*** Label projection online hashing for balanced similarity(`LPOH`)  
***2021 AAAI*** Asynchronous Teacher Guided Bit-wise Hard Mining for Online Hashing(`ATHOH`)  
* #### Traditional-Unsupervised  
***2015 CVPR*** Online sketching hashing(`OSH`)[[Code]](https://github.com/cvpr2015-submission/online-sketching-hashing)  
***2021 TKDE*** Making Online Sketching Hashing Even Faster(`DFROSH`)  
* #### Deep-Supervised  
***2022 ISCI*** Online deep hashing for both uni-modal and cross-modal retrieval(`ODHUC`)  
### 😄Cross-Modal  
* #### Traditional-Supervised  
***2016 AAAI*** Online Cross-Modal Hashing for Web Image Retrieval(`CMH`)  
***2017 IJCAI*** Dynamic Multi-View Hashing for Online Image Retrieval(`DMVH`)  
***2019 SIGIR*** Online Multi-modal Hashing with Dynamic Query-adaption(`OMHDQ`)  
***2019 MM*** Flexible Online Multi-modal Hashing for Large-scale Multimedia Retrieval(`FOMH`)  
***2020 MM*** Label Embedding Online Hashing for Cross-Modal Retrieval(`LEMON`)[[Code]](https://github.com/yxinwang/LEMON-MM2020)  
***2021 ICME*** Efficient Online Label Consistent Hashing for Large-Scale Cross-Modal Retrieval(`OLCH`)  
***2022 AAAI*** Online Enhanced Semantic Hashing: Towards Effective and Efficient Retrieval for Streaming Multi-Modal Data(`OASIS`)  
***2022 ICME*** Online Robust Specific and Consistent Hashing(`ORSCH`)  
***2022 PR*** Discrete online cross-modal hashing(`DLFH`)  
***2022 TMM*** OMGH: Online Manifold-Guided Hashing for Flexible Cross-modal Retrieval(`OMGH`)  
***2022 TOIS*** Efficient Multi-modal Hashing with Online Query Adaption for Multimedia Retrieval(`MHOQA`)[[Code]](https://github.com/ChaoqunZheng/MH-OQA)  
***2023 arXiv*** Three-Step Hashing for Online Cross-Modal Retrieval(`THOR`)[[Code]](https://github.com/yw-zhan/THOR)  
#### Traditional-Unsupervised  
***2022 APIN*** Online unsupervised cross-view discrete hashing for large-scale retrieval(`OUCDH`)  
* #### Deep-Supervised  
***2022 KBS*** Deep online cross-modal hashing by a co-training mechanism(`DOCHCM`)  
****
## 😍Remote Sensing  
### 😄Single-Modal  
* #### Deep-Unsupervised 
***2022 TGRS*** Multisource Data Reconstruction-Based Deep supervised Hashing for Unisource Remote Sensing Image Retrieval (`MrHash`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10001754)[[Code]](https://github.com/sunyuxi/MrHash)
* #### Deep-Supervised 
***2020 TGRS*** Hashing Nets for Hashing: A Quantized Deep Learning to Hash Framework for Remote Sensing Image Retrieval(`QDLH`)[[Paper]](https://www2.umbc.edu/rssipl/people/aplaza/Papers/Journals/2020.TGRS.Hashing.pdf)
***2021 TGRS*** Deep Hash Learning for Remote Sensing Image Retrieval(`DHL`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9143474)[[Code1]](https://git.tu-berlin.de/rsim/duch)[[Code2]](https://github.com/smallsmallflypigtang/Deep-Hash-learning-for-Remote-Sensing-Image-Retrieval)
***2021 TGRS*** Deep Hashing Learning for Visual and Semantic Retrieval of Remote Sensing Images(`DHCNN`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9261143)
***2022 TGRS*** Asymmetric Hash Code Learning for Remote Sensing Image Retrieval(`AHCL`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9682689)[[Code]](https://github.com/weiweisong415/Demo_AHCL_for_TGRS2022)
***2022 TGRS*** Hashing for Localization (HfL): A Baseline for Fast Localizing Objects in a Large-Scale Scene(`THNet`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9552450)[[Code]]( https://github.com/lrhan/HfL)
***2022 TGRS*** Meta-Hashing for Remote Sensing Image Retrieval(`meta-hashing`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9654226)[[Code]](https://github.com/TangXu-Group/Meta-hashing)
***2023 TGRS*** Deep Saliency Smoothing Hashing for Drone Image Retrieval(`DSSH`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10065512)
***2023 TGRS*** Encrypting Hashing Against Localization(`EHaL`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10102104)[[Code]](https://github.com/JingpengHan/EHaL)
### 😄Cross-Modal  
* #### Deep-Unsupervised  
***2022 CVPR*** Deep Unsupervised Contrastive Hashing for Large-Scale Cross-Modal Text-Image Retrieval in Remote Sensing(`DUCH`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9746251)[[Code1]](https://github.com/smallsmallflypigtang/Deep-Hash-learning-for-Remote-Sensing-Image-Retrieval) [[Code2]](https://git.tu-berlin.de/rsim/duch)
***2022 ICIP*** An Unsupervised Cross-Modal Hashing Method Robust to Noisy Training Image-Text Correspondences in Remote Sensing(`CHNR`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9897500)[[Code]](https://git.tu-berlin.de/rsim/chnr)
* #### Deep-Supervised
***2020 TGRS*** Deep Cross-Modal Image–Voice Retrieval in Remote Sensing(`DIVR`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9044618)
***2022 TGRS*** Cohesion Intensive Hash Code Book Coconstruction for Efficiently Localizing Sketch Depicted Scenes[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9634055)
***2022 TGRS*** Deep Quadruple-Based Hashing for Remote Sensing Image-Sound Retrieval(`DQH`)[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9722869)
***2022 TGRS*** Multisensor Fusion and Explicit Semantic Preserving-Based Deep Hashing for Cross-Modal Remote Sensing Image Retrieval(`MsEspH`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9656147)
***2023 TGRS*** Fine Aligned Discriminative Hashing for Remote Sensing Image-Audio Retrieval(`FADH`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10106504)
****
## 😍Trajectory
### 😄Road
* #### Deep-Unsupervised
***2023 AAAI*** GRLSTM: Trajectory Similarity Computation with Graph-Based Residual LSTM(`GRLSTM`）[[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/25624/25396) [[Code]](https://github.com/slzhou-xy/GRLSTM
)
***2022 KDD*** Spatio-Temporal Trajectory Similarity Learning in Road Networks(`ST2Vec
`)[[Paper]](https://dl.acm.org/doi/pdf/10.1145/3534678.3539375)[[Code]](https://github.com/zealscott/ST2Vec
)
***2023 DASFAA*** Trajectory Representation Learning Based on Road Network Partition for Similarity Computation（`PT2vec`）[[Paper]](https://link.springer.com/content/pdf/10.1007/978-3-031-30637-2.pdf?pdf=button)
***2021 KDD*** A Graph-based Approach for Trajectory Similarity Computation in Spatial Networks(`GTS`)[[Paper]](https://dl.acm.org/doi/pdf/10.1145/3447548.3467337)
***2021 CIKM*** Robust Road Network Representation Learning: When Traffic Patterns Meet Traveling Semantics(`Toast`)[[Paper]](https://dl.acm.org/doi/pdf/10.1145/3459637.3482293)
### 😄Grid
* #### Deep-Unsupervised
***2022 CIKM*** Efficient Trajectory Similarity Computation with Contrastive Learning(`CL-TSim`)[[Paper]](https://dl.acm.org/doi/pdf/10.1145/3511808.3557308)[[Code]](https://github.com/LIWEIDENG0830/CL-TSim)
***2022 KDD*** TrajGAT: A Graph-based Long-term Dependency Modeling Approach for Trajectory Similarity Computation(`TrajGAT`)[[Paper]](https://dl.acm.org/doi/pdf/10.1145/3534678.3539358)[[Code]](https://github.com/HuHaonan-CHN/TrajGAT)
***2022 WWW*** Towards robust trajectory similarity computation: Representation-based spatio-temporal similarity quantification(`RSTS`)[[Paper]](https://link.springer.com/content/pdf/10.1007/s11280-022-01085-4.pdf?pdf=button)[[Code]](https://github.com/Like-China/TrajectorySim-RSTS-model)
***2019 ICDE*** Computing Trajectory Similarity in Linear Time: A Generic Seed-Guided Neural Metric Learning Approach(`NeuTraj`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8731427)[[Code]](https://github.com/yaodi833/NeuTraj)
***2018 ICDE*** Deep Representation Learning for Trajectory Similarity Computation(`t2vec`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8509283)[[Code]](https://github.com/boathit/t2vec)
***2022 TKDE*** Representation Learning With Multi-Level Attention for Activity Trajectory Similarity Computation(`AT2VEC+`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9143478)
***2022 CIKM*** Aries: Accurate Metric-based Representation Learning for Fast Top-k Trajectory Similarity Query (`Aries`)[[Paper]](https://dl.acm.org/doi/pdf/10.1145/3511808.3557239)
***2021 ICDE*** T3S: Effective Representation Learning for Trajectory Similarity Computation(`T3S`)[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9458934)
****
