# Security and Privacy in Distributed/Collaborated/Federated/Split/Multi-Agent Learning

## Survey Paper

Title | Publication  | Team/Authors | Date | Methods
 :------: | :------: | :------: | :------: | :------: 
 [Strategies and Principles of Distributed Machine Learning on Big Data](https://arxiv.org/abs/1512.09295) | Engineering | CMU | 2016 |  
 [No peek: A survey of private distributed deep learning](https://arxiv.org/abs/1812.03288) | Arxiv | Massachusetts Institute of Technology | 2018 | 
 [Federated machine learning: Concept and applications](https://arxiv.org/abs/1902.04885) | ACM TIST | Hong Kong University of Science and Technology | 2019 | 
 [On safeguarding privacy and security in the framework of federated learning](https://arxiv.org/abs/1909.06512) | IEEE Network | Nanjing University of Science and Technology | 2020 | 
 [Threats to federated learning: A survey](https://arxiv.org/abs/2003.02133) | Arxiv| National University of Singapore | 2020 |
 [An Overview of Federated Deep Learning Privacy Attacks and Defensive Strategies](https://arxiv.org/abs/2004.04676) |  Federated Learning Systems | Delft University of Technology | 2020 | 
 [When machine learning meets privacy: A survey and outlook](https://arxiv.org/abs/2011.11819) | ACM Computing Surveys | University of Technology Sydney | 2021 | 

 
## Attack/Threat Model

Title | Publication  | Team/Authors | Date | Methods
 :------: | :------: | :------: | :------: | :------: 
 [Deep models under the GAN: information leakage from collaborative deep learning](https://arxiv.org/abs/1702.07464) | ACM CCS| Stevens Institute of Technology | 2017 | Genergate training data using the adverisal global model
 [Membership inference attacks against machine learning models](https://arxiv.org/abs/1610.05820) | IEEE S&P | Cornell Tech | 2017 |
 [Practical Black-Box Attacks against Machine Learning](https://arxiv.org/abs/1602.02697) | ASIA CCS | Pennsylvania State University | 2017 |
 [Exploiting unintended feature leakage in collaborative learning](https://arxiv.org/abs/1805.04049) | IEEE S&P | UCL | 2018 |
[The Hidden Vulnerability of Distributed Learning in Byzantium](http://proceedings.mlr.press/v80/mhamdi18a.html) | ICML | EPFL, Switzerland | 2018 |
 [How To Backdoor Federated Learning](https://arxiv.org/abs/1807.00459) | ICAIS |  Cornell University | 2019 | Model poisoning attack
 [Analyzing Federated Learning through an Adversarial Lens](http://proceedings.mlr.press/v97/bhagoji19a.html) | ICML | Princeton University | 2019 | Model poisoning attack by estimating the models of the benign clients
[Beyond Inferring Class Representatives: User-Level Privacy Leakage from Federated Learning](https://arxiv.org/abs/1812.00535) |  IEEE INFOCOM  | Wuhan University | 2019 |
 [Local Model Poisoning Attacks to Byzantine-robust Federated Learning](https://www.usenix.org/conference/usenixsecurity20/presentation/fang) | USENIX Security | Iowa State University | 2020 |  Client collusion for the untargeted model poisoning attack
[Can we use split learning on 1d cnn models for privacy preserving training?](https://arxiv.org/abs/2003.12365) |  ASIA CCS  | Data61, CSIRO Australia and Cyber Security CRC | 2020 | Adopt DP or add hidden layers 
[Feature Inference Attack on Model Predictions in Vertical Federated Learning](https://arxiv.org/abs/2010.10152) |  IEEE ICDE  | National University of Singapore | 2021 | Infer participants' features based on GAN
[Label Leakage and Protection in Two-party Split Learning](https://arxiv.org/abs/2102.08504) |  Arxiv  | ByteDance Inc. | 2021 | Infer labels by the norm of gradient
 
## Framework Design

Title | Publication  | Team/Authors | Date | Methods
 :------: | :------: | :------: | :------: | :------: 
 [Split learning for health: Distributed deep learning without sharing raw patient data](https://arxiv.org/abs/1812.00564)  | Arxiv | Massachusetts Institute of Technology | 2019 |
 [Privacy Preserving Vertical Federated Learning for Tree-based Models](https://arxiv.org/abs/2008.06170)  | Proc. VLDB Endow. | National University of Singapore | 2020 |
 [Secure Bilevel Asynchronous Vertical Federated Learning with Backward Updating](https://arxiv.org/abs/2103.00958)  | AAAI | Xidian University | 2021 | Bilevel Asynchronous Parallel Architecture

## Homomorphic Encryption

Title | Publication  | Team/Authors | Date | Methods
 :------: | :------: | :------: | :------: | :------:
 [Privacy-preserving deep learning via additively homomorphic encryption](https://ieeexplore.ieee.org/abstract/document/8241854) | IEEE TIFS | National Institute of Information and Communications Technology, Tokyo | 2017 | 
 [Verifynet: Secure and verifiable federated learning](https://ieeexplore.ieee.org/abstract/document/8765347) | IEEE TIFS | University of Electronic Science and Technology of China | 2019 | 
 [Additively Homomorphical Encryption based Deep Neural Network for Asymmetrically Collaborative Machine Learning](https://arxiv.org/abs/2007.06849) | Arxiv | Chinese University of Hong Kong | 2020 | 
 [Scalable privacy-preserving distributed learning](https://arxiv.org/abs/2005.09532) | PETS | École Polytechnique Fédérale de Lausanne | 2021 | 
 [Privacy-Enhanced Federated Learning against Poisoning Adversaries](https://ieeexplore.ieee.org/abstract/document/9524709) | IEEE TIFS | University of Electronic Science and Technology of China | 2021 | 

## Secure MPC

Title | Publication  | Team/Authors | Date | Methods
 :------: | :------: | :------: | :------: | :------: 
 [Practical secure aggregation for privacy-preserving machine learning](https://dl.acm.org/doi/10.1145/3133956.3133982) | ACM CCS | Google | 2017 |  Secret Sharing, Key Agreement, Authenticated Encryption
 [QUOTIENT: Two-party secure neural network training and prediction](https://dl.acm.org/doi/10.1145/3319535.3339819) | ACM CCS| University of Oxford | 2019 |
 [XONN: XNOR-based oblivious deep neural network inference](https://arxiv.org/abs/1902.07342) | USENIX Security | UC San Diego | 2019 | Secret Sharing, Oblivious Transfer, Garbled Circuits
 [SecureNN: 3-party secure computation for neural network training](https://sciendo.com/article/10.2478/popets-2019-0035) | PETS | Princeton University | 2019 | 
 [Practical two-party privacy-preserving neural network based on secret sharing](https://arxiv.org/abs/2104.04709) | Arxiv | Jilin University | 2021 | Secret Sharing, Oblivious Transfer
 
## Differential Privacy
### Model Shuffle
Title | Publication  | Team/Authors | Date | Methods
 :------: | :------: | :------: | :------: | :------:
 [On the renyi differential privacy of the shuffle model](https://arxiv.org/abs/2105.05180) | CCS Best Paper Reward  | UCLA/Google | 2021 |
 [FLAME: Differentially private federated learning in the shuffle model](https://www.aaai.org/AAAI21Papers/AAAI-4838.LiuR.pdf) | AAAI  | Renmin University of China | 2021 |
 [Shuffled model of differential privacy in federated learning](https://ieeexplore.ieee.org/abstract/document/9517906) | AISTATS  | UCLA/Google | 2021 |
 [Differentially private federated learning with shuffling and client self-sampling](https://ieeexplore.ieee.org/abstract/document/9517906) | IEEE ISIT  | UCLA | 2021 |
 [Shuffled model of federated learning: Privacy, accuracy and communication trade-offs](https://arxiv.org/abs/2008.07180) | IEEE Journal on Selected Areas in Information Theory | UCLA/Google | 2021 |
### Others
Title | Publication  | Team/Authors | Date | Methods
 :------: | :------: | :------: | :------: | :------: 
 [Distributed deep learning under differential privacy with the teacher-student paradigm](https://www.aaai.org/ocs/index.php/WS/AAAIW18/paper/viewPaper/16631) | AAAI  | Nanyang Technological University | 2018 |
 [Minimax-optimal privacy-preserving sparse pca in distributed systems](http://proceedings.mlr.press/v84/ge18a.html) | ICAIS | Princeton University | 2018 |
 [Differentially private malicious agent avoidance in multiagent advising learning](https://ieeexplore.ieee.org/abstract/document/8685696) | IEEE Transactions on Cybernetics | University of Technology Sydney | 2019 |
 [DP-ADMM: ADMM-based distributed learning with differential privacy](https://arxiv.org/abs/1808.10101) | IEEE TIFS | Oklahoma State University | 2019 |
 [Hybrid Differentially Private Federated Learning on Vertically Partitioned Data](https://arxiv.org/abs/2009.02763) | Arxiv | Tencent | 2020 |
 [Federated learning with differential privacy: Algorithms and performance analysis](http://128.84.4.18/abs/1911.00222) | IEEE TIFS | Nanjing University of Science and Technology | 2020 |
 [Arbitrarily strong utility-privacy tradeoff in multi-agent systems](https://ieeexplore.ieee.org/abstract/document/9167255) | IEEE TIFS | Nanyang Technological University | 2020 |
 [Federated learning with sparsification-amplified privacy and adaptive optimization](https://www.ijcai.org/proceedings/2021/0202.pdf) |IJCAI|The University of Texas at San Antonio|2021| Random sparsifier to reduce transmission overhead and enhance privacy
 
 ## Robust Aggregation

Title | Publication  | Team/Authors | Date | Methods
 :------: | :------: | :------: | :------: | :------: 
 [Machine learning with adversaries: Byzantine tolerant gradient descent](https://dl.acm.org/doi/abs/10.5555/3294771.3294783) | NIPS | EPFL, Switzerland | 2017 |
 [Robust aggregation for federated learning](https://arxiv.org/abs/1912.13445) | Arxiv | University of Washington | 2019 |
 [Cronus: Robust and Heterogeneous Collaborative Learning with Black-Box Knowledge Transfer](https://arxiv.org/abs/1912.11279) | Arxiv | National University of Singapore | 2019 |
 [Byzantine-robust federated machine learning through adaptive model averaging](https://arxiv.org/abs/1909.05125) | Arxiv | Imperial College London | 2019 |
 [Attack-resistant federated learning with residual-based reweighting](https://arxiv.org/abs/1912.11464) | Arxiv | HKUST | 2019 |
 [A Little Is Enough: Circumventing Defenses For Distributed Learning](https://arxiv.org/abs/1902.06156) | NeurIPS| Bar Ilan University | 2019 |
 [FederBoost: Private Federated Learning for GBDT](https://arxiv.org/abs/2011.02796) | Arxiv| Zhejiang University | 2020 |
 [Shielding collaborative learning: Mitigating poisoning attacks through client-side detection](https://arxiv.org/abs/1910.13111) | IEEE TDSC | Wuhan University | 2020 |
 [Byzantine-robust federated learning through spatial-temporal analysis of local model updates](https://arxiv.org/abs/2107.01477) | Arxiv | University of Tennessee | 2021 |
 [Manipulating the byzantine optimizing model poisoning attacks and defenses for federated learning](https://www.ndss-symposium.org/wp-content/uploads/ndss2021_6C-3_24498_paper.pdf) | NDSS | University of Massachusetts Amherst | 2021 |
 [FLTrust: Byzantine-robust federated learning via trust bootstrapping](https://arxiv.org/abs/2012.13995) | NDSS | Duke University | 2021 |
 
 ## Adversarial Training

Title | Publication  | Team/Authors | Date | Methods
 :------: | :------: | :------: | :------: | :------: 
 [On the Convergence and Robustness of Adversarial Training](https://people.eng.unimelb.edu.au/baileyj/papers/ICML_Adversarial_full_reducedsize.pdf) | ICML | JD | 2021 |
 
 

