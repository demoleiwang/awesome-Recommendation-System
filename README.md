# awesome-Recommendation-System

This repo is a collection of AWESOME things about general recommendation and sequential recommendation, including papers, code, etc. Feel free to star and fork.

<!-- Some of these papers are summarized with tables in Google Sheet. Please find the link here: [Summary](https://docs.google.com/spreadsheets/d/1X_aQ-80YNt_jjbfXzs3JreoDxJW3zAs-L1ElV6NuJgc/edit?usp=sharing) -->


![](https://img.shields.io/github/last-commit/demoleiwang/awesome-Recommendation-System?color=green) ![](https://img.shields.io/badge/PaperNumber-48-brightgreen) ![](https://img.shields.io/badge/PRs-Welcome-red) 

<!-- 

* **[[]]()** x. x. [[code](x)] 

    *x* 

-->

## Sequential Recommendation

### WSDM 2021 (1)

* **[[SINE'21]](https://arxiv.org/pdf/2102.09267.pdf)** **Sparse**-Interest Network for Sequential Recommendation. WSDM 2021. 

    *Qiaoyu Tan, Jianwei Zhang, Jiangchao Yao, Ninghao Liu, Jingren Zhou, Hongxia Yang, Xia Hu.* 
    
### WWW 2021 (3)

* **[[ACVAE'21]](https://arxiv.org/pdf/2103.10693.pdf)** **Adversarial** and **Contrastive** Variational Autoencoder for Sequential Recommendation. WWW 2021. [[code](https://github.com/ACVAE/ACVAE-PyTorch)] 

    *Zhe Xie, Chengxuan Liu, Yichi Zhang, Hongtao Lu, Dong Wang, Yue Ding.* 

* **[[FAT'21]](https://arxiv.org/pdf/2011.00422.pdf)** **Future**-Aware Diverse Trends Framework for Recommendation. WWW 2021. [[code](x)] 

    *Yujie Lu, Shengyu Zhang, Yingxuan Huang, Luyao Wang, Xinyao Yu, Zhou Zhao, Fei Wu.* 

* **[[RetaGNN'21]](https://arxiv.org/pdf/2101.12457.pdf)** RetaGNN: **Relational Temporal** Attentive **Graph** Neural Networks for Holistic Sequential Recommendation. WWW 2021. [[code]](https://github.com/retagnn/RetaGNN)

    *Cheng Hsu, Cheng-Te Li* 

### SIGIR 2021 (8)

* **[[CoCoRec'21]](https://www.cs.virginia.edu/~hw5x/paper/SIGIR2021_SeqRec_Cai.pdf)** Category-aware Collaborative Sequential Recommendation. SIGIR 2021. [[code](https://github.com/RenqinCai/CoCoRec)] 

    *Renqin Cai , Jibang Wu , Aidan San , Chong Wang , Hongning Wang.* 

* **[[SURGE'21]](https://arxiv.org/pdf/2106.14226.pdf)** Sequential Recommendation with Graph Neural Networks. SIGIR 2021. [[code](https://github.com/tsinghua-fib-lab/SIGIR21-SURGE)] 

    *Jianxin Chang, Chen Gao, Yu Zheng, Yiqun Hui, Yanan Niu, Yang Song, Depeng Jin, Yong Li.* 

* **[[StackRec'21]](https://arxiv.org/pdf/2012.07598)** StackRec: Efficient Training of Very Deep Sequential Recommender Models by Iterative Stacking. SIGIR 2021. [[code](https://github.com/wangjiachun0426/StackRec)] 

    *Jiachun Wang, Fajie Yuan, Jian Chen, Qingyao Wu, Min Yang, Yang Sun, Guoxiao Zhang.* 

* **[[CASR'21]](http://yongfeng.me/attach/wang-sigir2021.pdf)** Counterfactual Data-Augmented Sequential Recommendation. SIGIR 2021. [[code](x)] 

    *Zhenlei Wang , Jingsen Zhang , Hongteng Xu , Xu Chen , Yongfeng Zhang , Wayne Xin Zhao , Ji-Rong Wen.* 

* **[[CauseRec'21]](https://arxiv.org/pdf/2109.05261)** CauseRec: Counterfactual User Sequence Synthesis for Sequential Recommendation. SIGIR 2021. [[code](https://github.com/gzy-rgb/CauseRec)] 

    *Shengyu Zhang, Dong Yao, Zhou Zhao, Tat-seng Chua, Fei Wu.* 

* **[[ASReP'21]](https://dl.acm.org/doi/pdf/10.1145/3404835.3463036)** Augmenting sequential recommendation with pseudo-prior items via reversely pre-training transformer. SIGIR 2021. [[code](https://github.com/DyGRec/ASReP)] 

    *Zhiwei Liu, Ziwei Fan, Yu Wang, Philip S Yu.* 

* **[[CoSeRec'21]](https://arxiv.org/pdf/2108.06479)** Contrastive self-supervised sequential recommendation with robust augmentation. SIGIR 2021. [[code](https://github.com/YChen1993/CoSeRec)] 

    *Zhiwei Liu, Yongjun Chen, Jia Li, Philip S Yu, Julian McAuley, Caiming Xiong.* 

* **[[MetaTL]](https://arxiv.org/pdf/2107.06427)** Sequential Recommendation for Cold-start Users with Meta Transitional Learning. SIGIR 2021.  

    *Jianling Wang, Kaize Ding, James Caverlee.* 

### CIKM 2021 (8)

* **[[DT4SRec'21]](https://arxiv.org/pdf/2106.06165.pdf)** Modeling Sequences as Distributions with Uncertainty for Sequential Recommendation. CIKM 2021. [[code](https://github.com/DyGRec/DT4SR)] 

    *Ziwei Fan, Zhiwei Liu, Shen Wang, Lei Zheng, Philip S Yu.* 

* **[[Seq2Bubbles'21]](https://qitianwu.github.io/assets/Seq2Bubble.pdf)** Seq2Bubbles: Region-Based Embedding Learning for User Behaviors in Sequential Recommenders. CIKM 2021. 

    *Qitian Wu, Chenxiao Yang, Shuodian Yu, Xiaofeng Gao, Guihai Chen* 

* **[[TCT'21]](https://arxiv.org/pdf/2108.06625)** Continuous-Time Sequential Recommendation with Temporal Graph Collaborative Transformer. CIKM 2021. [[code](https://github.com/DyGRec/TGSRec)] 

    *Ziwei Fan, Zhiwei Liu, Jiawei Zhang, Yun Xiong, Lei Zheng, Philip S. Yu.* 

* **[[STEN'21]](https://xinxin-me.github.io/papers/CIKM21.pdf)** Extracting Attentive Social Temporal Excitation for Sequential Recommendation. CIKM 2021. 

    *Yunzhe Li , Yue Ding , Bo Chen , Xin Xin , Yule Wang , Yuxiang Shi , Ruiming Tang , Dong Wang.* 

* **[[H2SeqRec'21]](https://arxiv.org/pdf/2108.08134)** Hyperbolic Hypergraphs for Sequential Recommendation. CIKM 2021. [[code](https://github.com/Abigale001/h2seqrec)] 

    *Yicong Li, Hongxu Chen, Xiangguo Sun, Zhenchao Sun, Lin Li, Lizhen Cui, Philip S. Yu, Guandong Xu.* 

* **[[DRL-SRe'21]](https://arxiv.org/pdf/2109.11790)** Learning Dual Dynamic Representations on Time-Sliced User-Item Interaction Graphs for Sequential Recommendation. CIKM 2021. [[code](https://github.com/weizhangltt/dual-recommend)] 

    *Zeyuan Chen, Wei Zhang, Junchi Yan, Gang Wang, Jianyong Wang.* 

* **[[LSAN'21]](https://arxiv.org/pdf/2108.11333.pdf)** Lightweight Self-Attentive Sequential Recommendation. CIKM 2021. [[code](x)] 

    *Yang Li, Tong Chen, Peng-Fei Zhang, Hongzhi Yin.* 

* **[[locker'21]](https://cseweb.ucsd.edu/~jmcauley/pdfs/cikm21.pdf)** Locker: Locally Constrained Self-Attentive Sequential Recommendation. CIKM 2021. [[code](https://github.com/AaronHeee/LOCKER)] 

    *Zhankui He , Handong Zhao , Zhe Lin , Zhaowen Wang , Ajinkya Kale , Julian Mcauley.* 


### WWW 2022 (4)

* **[[STOSA'22]](https://arxiv.org/pdf/2201.06035.pdf)** Sequential Recommendation via Stochastic Self-Attention. WWW 2022. [[code](https://github.com/zfan20/STOSA)] 

    *Ziwei Fan, Zhiwei Liu, Yu Wang, Alice Wang, Zahra Nazari, Lei Zheng, Hao Peng, Philip S Yu.* 


* **[[ICLRec'22]](https://arxiv.org/pdf/2202.02519.pdf)** Intent Contrastive Learning for Sequential Recommendation. WWW 2022. [[code](https://github.com/salesforce/ICLRec)] 

    *Yongjun Chen, Zhiwei Liu, Jia Li, Julian McAuley, Caiming Xiong.* 
    
* **[[FMLP-Rec'22]](https://arxiv.org/pdf/2202.13556.pdf)** Filter-enhanced MLP is All You Need for Sequential Recommendation. WWW 2022. [[code](https://arxiv.org/abs/2202.13556)] 

    *Kun Zhou, Hui Yu, Wayne Xin Zhao, Ji-Rong Wen.* 

* **[[STARec'22]](https://arxiv.org/pdf/2202.03097.pdf)** Learn over Past, Evolve for Future: Search-based Time-aware Recommendation with Sequential Behavior Data. WWW 2022.

### SIGIR 2022 (10)

* **[[DCN'22]](https://dl.acm.org/doi/pdf/10.1145/3477495.3531918)** Dual Contrastive Network for Sequential Recommendation. SIGIR 2022 (SHORT). [[code](x)] 

    *Guanyu Lin , Chen Gao , Yinfeng Li , Yu Zheng , Zhiheng Li , Depeng Jin , Yong Li.* 

* **[[ESI'22]](https://arxiv.org/pdf/2204.10851.pdf)** Exploiting Session Information in BERT-based Session-aware Sequential Recommendation. SIGIR 2022 (SHORT). [[code](https://github.com/theeluwin/session-aware-bert4rec)] 

    *Jinseok Seol, Youngrok Ko, Sang-goo Lee.* 

* **[[ELECRec'22]](https://arxiv.org/pdf/2204.02011.pdf)** ELECRec: Training Sequential Recommenders as Discriminators. SIGIR 2022 (SHORT). [[code](https://github.com/YChen1993/ELECRec)] 

    *Yongjun Chen, Jia Li, Caiming Xiong* 

* **[[CAFE'22]](https://arxiv.org/pdf/2204.01839.pdf)** Coarse-to-Fine Sparse Sequential Recommendation. SIGIR 2022.

    *Jiacheng Li, Tong Zhao, Jin Li, Jim Chan, Christos Faloutsos, George Karypis, Soo-Min Pantel, Julian McAuley.* 

* **[[IPSRec]](https://dl.acm.org/doi/pdf/10.1145/3477495.3531756)** Item-Provider Co-learning for Sequential Recommendation. SIGIR 2022. [[code](https://github.com/siat-nlp/IPSRec)] 

    *Lei Chen , Jingtao Ding , Min Yang , Chengming Li , Chonggang Song , Lingling Yi.* 

* **[[DPP'22]](https://dl.acm.org/doi/pdf/10.1145/3477495.3531965)** Determinantal Point Process Likelihoods for Sequential Recommendation. SIGIR 2022. [[code](https://github.com/l-lyl/DPPLikelihoods4SeqRec)] 

    *Yuli Liu , Christian Walder , Lexing Xie.* 

* **[[Ada-Ranker'22]](https://arxiv.org/pdf/2205.10775.pdf)** Ada-Ranker: A Data Distribution Adaptive Ranking Paradigm for Sequential Recommendation. SIGIR 2022. [[code](https://github.com/RUCAIBox/Ada-Ranker)] 

    *Kaiyuan Li,Pengfei Wang,Chenliang Li.* 

* **[[MARIS'22]](https://dl-acm-org.libproxy.smu.edu.sg/doi/pdf/10.1145/3477495.3532022)** Multi-Agent RL-based Information Selection Framework for Sequential Recommendation. SIGIR 2022.

    *Kaiyuan Li, Pengfei Wang, Chenliang Li* 

* **[[DIF-SR'22]](https://arxiv.org/pdf/2204.11046)** Decoupled Side Information Fusion for Sequential Recommendation. SIGIR 2022. [[code](https://github.com/AIM-SE/DIF-SR)] 

    *Yueqi Xie, Peilin Zhou, Sunghun Kim.* 

* **[[MGNM'22]](https://arxiv.org/pdf/2205.01286.pdf)** When Multi-Level Meets Multi-Interest: A Multi-Grained Neural Model for Sequential Recommendation. SIGIR 2022. [[code](https://github.com/WHUIR/MGNM)] 

    *Yu Tian, Jianxin Chang, Yannan Niu, Yang Song, Chenliang Li.* 

### kdd 2022 (4)

* **[[IPS'22]](https://dl.acm.org/doi/pdf/10.1145/3534678.3539430)** Debiasing the Cloze Task in Sequential Recommendation with Bidirectional Transformers. KDD 2022. [[code](https://github.com/KhalilDMK/DebiasedBERT4Rec)] 

    *Khalil Damak , Sami Khenissi , Olfa Nasraoui.* 

* **[[PARSRec'22]](https://dl.acm.org/doi/pdf/10.1145/3534678.3539432)** PARSRec: Explainable Personalized Attention-fused Recurrent Sequential Recommendation Using Session Partial Actions. KDD 2022. [[code](https://github.com/ehgh/PARSRec)] 

    *Ehsan Gholami , Mohammad Motamedi , Ashwin Aravindakshan.* 

* **[[UniSRec'22]](https://dl.acm.org/doi/pdf/10.1145/3534678.3539381)** Towards Universal Sequence Representation Learning for Recommender Systems. KDD 2022. [[code](https://dl.acm.org/doi/pdf/10.1145/3534678.3539381)] 

    *Yupeng Hou , Shanlei Mu , Wayne Xin Zhao , Yaliang Li , Bolin Ding , Ji-Rong Wen.* 
    
* **[[MBHT'22]]()** Multi-Behavior Hypergraph-Enhanced Transformer for Sequential Recommendation. KDD 2022. [[code](https://github.com/yuh-yang/MBHT-KDD22)] 

    *Yuhao Yang , Chao Huang , Lianghao Xia , Yuxuan Liang , Yanwei Yu , Chenliang Li.* 


### CIKM 2022 (6)

* **[[ContrastVAE'22]](https://arxiv.org/pdf/2209.00456.pdf)** ContrastVAE: **Contrastive Variational** **AutoEncoder** for Sequential Recommendation. CIKM 2022. [[code](https://github.com/YuWang-1024/ContrastVAE)] 

    *Yu Wang, Hengrui Zhang, Zhiwei Liu, Liangwei Yang, Philip S Yu.* 

* **[[EC4SRec'22]](https://arxiv.org/pdf/2209.01347)** **Explanation Guided Contrastive** Learning for Sequential Recommendation. CIKM 2022. [[code](https://github.com/demoleiwang/EC4SRec)] 

    *Lei Wang, Ee-Peng Lim, Zhiwei Liu, Tianxiang Zhao.* 

* **[[MCLSR'22]](https://arxiv.org/pdf/2208.13007.pdf)** **Multi-level Contrastive** Learning Framework for Sequential Recommendation. CIKM 2022. 

    *Ziyang Wang, Huoyu Liu, Wei Wei, Yue Hu, Xian-Ling Mao, Shaojian He, Rui Fang, Dangyang chen.* 

* **[[TLSRec'22]](https://arxiv.org/pdf/2208.04760.pdf)** Time Lag Aware Sequential Recommendation. CIKM 2022. [[code](x)] 

    *Lihua Chen, Ning Yang, Philip S Yu.* 

* **[[SAM'22]](https://arxiv.org/pdf/2208.04022.pdf)** **Sparse** Attentive Memory Network for Click-through Rate Prediction with **Long** Sequences. CIKM 2022. [[code](https://github.com/waldenlqy/SAM)] 

    *Qianying Lin, Wen-Ji Zhou, Yanshi Wang, Qing Da, Qing-Guo Chen, Bing Wang.* 


* **[[CBiT'22]](https://arxiv.org/pdf/2208.03895.pdf)** Contrastive Learning with **Bidirectional** Transformers for Sequential Recommendation. CIKM 2022. [[code](https://github.com/hw-du/CBiT/tree/master)] 

    *Hanwen Du, Hui Shi, Pengpeng Zhao, Deqing Wang, Victor S.Sheng, Yanchi Liu, Guanfeng Liu, Lei Zhao.* 


 
### TOIS (3)

* **[[MDSR'22]](https://staff.fnwi.uva.nl/m.derijke/wp-content/papercite-data/pdf/chen-2022-multi-interest.pdf)** Multi-interest Diversification for End-to-end Sequential Recommendation. TOIS 2022. [[code](x)] 
    
* **[[metaCSR'22]](https://arxiv.org/pdf/2110.09083)** Learning to Learn a Cold-start Sequential Recommender. TOIS. [[code](x)] 

    *Xiaowen Huang, Jitao Sang, Jian Yu, Changsheng Xu.* 
    
* **[[ContraRec'22]](https://dl.acm.org/doi/pdf/10.1145/3522673)** Sequential Recommendation with **Multiple Contrast** Signals. TOIS 2022. [[code](https://github.com/THUwangcy/ReChorus/blob/master/README.md)] 



### Others (1)

* **[[GenNi'22]](https://arxiv.org/pdf/2208.03645.pdf)** **Generating** **Negative** **Samples** for Sequential Recommendation. 2022. 

    *Yongjun Chen, Jia Li, Zhiwei Liu, Nitish Shirish Keskar, Huan Wang, Julian McAuley, Caiming Xiong.* 
    
    :) uninformative negatives => generating negative samples
