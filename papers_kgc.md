# Knowledge Graph Completion

research papers related to **K**nowledge **G**raph **C**ompletion (KGC) task

**Keyword:** Knowledge Graph Completion; Link Prediction; Graph/Knowledge Embedding

<!-- TOC -->

- [Knowledge Graph Completion](#knowledge-graph-completion)
  - [Scholar](#scholar)
  - [Survey :D](#survey-d)
  - [Papers Must be Read :(](#papers-must-be-read-)
    - [Topic 1 - Knowledge Embedding](#topic-1---knowledge-embedding)
      - [TransX](#transx)
      - [Tensor Decomposition](#tensor-decomposition)
      - [Neural Network](#neural-network)
      - [Graph Neural Network](#graph-neural-network)
      - [Implementation Tricks](#implementation-tricks)
    - [Topic 2 - Path Reasoning](#topic-2---path-reasoning)
    - [Topic 3 - Rule](#topic-3---rule)
    - [Topic 4 - Sweety](#topic-4---sweety)
      - [Open set](#open-set)
      - [Sparse KG](#sparse-kg)
      - [Zero/One/Few-shot](#zeroonefew-shot)

<!-- /TOC -->

## Scholar
- Jian Tang [[homepage]](https://jian-tang.com/)

## Survey :D

- Knowledge Graph Completion: A Review. IEEE Access. 2020. [[paper]](https://ieeexplore.ieee.org/document/9220143)
- CoDEx: A Comprehensive Knowledge Graph Completion Benchmark. 2020. [[paper]](https://arxiv.org/abs/2009.07810)
- And **RELATED WORK** part in new papers ...



## Papers Must be Read :(

### Topic 1 - Knowledge Embedding

#### TransX

- **[TransE]**  Translating embeddings for modeling multi-relational data. NeurIPS. 2013. [[paper]](http://papers.nips.cc/paper/5071-translating-embeddings-for-modeling-multi-relational-data)
  - **[TransH]** Knowledge graph embedding by translating on hyperplanes. AAAI. 2014. [[paper]](http://www.aaai.org/ocs/index.php/AAAI/AAAI14/paper/view/8531)
  - **[TransR]** Learning Entity and Relation Embeddings for Knowledge Graph Completion. AAAI. 2015. [[paper]](http://www.aaai.org/ocs/index.php/AAAI/AAAI15/paper/view/9571)
  - **[TransD]** Knowledge Graph Embedding via Dynamic Mapping Matrix. ACL. 2015. [[paper]](https://doi.org/10.3115/v1/p15-1067)
- **[RotatE]** RotatE: Knowledge Graph Embedding by Relational Rotation in Complex Space. ICLR.2018. [[paper]](https://openreview.net/forum?id=HkgEQnRqYQ)


#### Tensor Decomposition 

- **[RESCAL]** Factorizing YAGO: scalable machine learning for linked data. WWW. 2012. [[paper]](https://doi.org/10.1145/2187836.2187874)
- **[DistMult]** Embedding Entities and Relations for Learning and Inference in Knowledge Bases. ICLR. 2015. [[paper]](http://arxiv.org/abs/1412.6575) 
  - **[ComplEx]** Complex Embeddings for Simple Link Prediction. ICML. 2016. [[paper]](http://proceedings.mlr.press/v48/trouillon16.html)
    - Canonical Tensor Decomposition for Knowledge Base Completion. ICML. 2018. [[paper]](http://proceedings.mlr.press/v80/lacroix18a.html)
- **[SimplE]** SimplE Embedding for Link Prediction in Knowledge Graphs. NeurlPS. 2018. [[paper]](http://papers.nips.cc/paper/7682-simple-embedding-for-link-prediction-in-knowledge-graphs)
  - *[CP]* The expression of a tensor or a polyadic as a sum of products.  Studies in Applied Mathematics.1927. [[paper]](https://onlinelibrary.wiley.com/doi/abs/10.1002/sapm192761164)
  - Knowledge Base Completion: Baselines Strike Back. Rep4NLP@ACL. 2017. [[paper]](https://doi.org/10.18653/v1/w17-2609)
- **[TuckER]** TuckER: Tensor Factorization for Knowledge Graph Completion. EMNLP. 2019. [[paper]](http://arxiv.org/abs/1901.09590)

#### Neural Network

- **[ConvE]** Convolutional 2D Knowledge Graph Embeddings. AAAI. 2018. [[paper]](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/17366)
- **[ConvKB]** A Novel Embedding Model for Knowledge Base Completion Based on Convolutional Neural Network. NAACL-HLT. 2018. [[paper]](https://doi.org/10.18653/v1/n18-2053)

#### Graph Neural Network
- **[SACN]** End-to-end Structure-Aware Convolutional Networks for Knowledge Base Completion. AAAI. 2018. [[paper]](http://arxiv.org/abs/1811.04441)
- Learning Attention-based Embeddings for Relation Prediction in Knowledge Graphs. ACL. 2019. [[paper]](https://link.zhihu.com/?target=https%3A//www.aclweb.org/anthology/P19-1466/)
- A2N: Attending to Neighbors for Knowledge Graph Inference. ACL. 2019. [[paper]](https://link.zhihu.com/?target=https%3A//www.aclweb.org/anthology/P19-1431)
- **[RGHAT]** Relational Graph Neural Network with Hierarchical Attention for Knowledge Graph Completion. AAAI. 2020. [[paper]](https://link.zhihu.com/?target=https%3A//ojs.aaai.org//index.php/AAAI/article/view/6508)

#### Implementation Tricks

- Realistic Re-evaluation of Knowledge Graph Completion Methods: An Experimental Study. SIGMOD. 2020. [[paper]](https://doi.org/10.1145/3318464.3380599)
- You CAN Teach an Old Dog New Tricks! On Training Knowledge Graph Embeddings. ICLR. 2020. [[paper]](https://openreview.net/forum?id=BkxSmlBFvr)

### Topic 2 - Path Reasoning

- **[PRA]** Random Walk Inference and Learning in A Large Scale Knowledge Base. EMNLP. 2011. [[paper]](https://www.aclweb.org/anthology/D11-1049/)
- **[SFE]** Efficient and Expressive Knowledge Base Completion Using Subgraph Feature Extraction. EMNLP. 2015. [[paper]](https://doi.org/10.18653/v1/d15-1173)
- **[Path-RNN]** Compositional Vector Space Models for Knowledge Base Completion. ACL. 2015. [[paper]](https://doi.org/10.3115/v1/p15-1016)
  - Chains of Reasoning over Entities, Relations, and Text using Recurrent Neural Networks. EACL. 2017. [[paper]](https://doi.org/10.18653/v1/e17-1013)
- **[CPRA]** Knowledge Base Completion via Coupled Path Ranking. ACL. 2016. [[paper]](https://www.aclweb.org/anthology/P16-1124)
- **[DeepPath]** DeepPath: A Reinforcement Learning Method for Knowledge Graph Reasoning. EMNLP. 2017. [[paper]](https://doi.org/10.18653/v1/d17-1060) 

### Topic 3 - Rule
- **[ProPPR]** Efficient inference and learning in a large knowledge base. Machine Learning. 2015. [[paper]](https://doi.org/10.1007/s10994-015-5488-x)
- **[AMIE]** AMIE: association rule mining under incomplete evidence in ontological knowledge bases. WWW. 2013. [[paper]](https://doi.org/10.1145/2488388.2488425)
  - **[AMIE+]** Fast rule mining in ontological knowledge bases with AMIE+. VLDB. 2015. [[paper]](https://doi.org/10.1007/s00778-015-0394-1)
  - **[AMIE3]** Fast and Exact Rule Mining with AMIE 3. ESWC. 2020. [[paper]](https://doi.org/10.1007/978-3-030-49461-2_3)
- **[RUDIK]** Robust Discovery of Positive and Negative Rules in Knowledge Bases. ICDE. 2018. [[paper]](https://doi.org/10.1109/ICDE.2018.00108)
- **[RLvLR]** Scalable Rule Learning via Learning Representation. IJCAI. 2018. [[paper]](https://www.ijcai.org/Proceedings/2018/297)
- **[AnyBURL]** Anytime Bottom-Up Rule Learning for Knowledge Graph Completion. IJCAI. 2019. [[paper]](https://www.ijcai.org/Proceedings/2019/435)


### Topic 4 - Sweety

#### Open set
- **[ConMask]** Open-World Knowledge Graph Completion. AAAI. 2018. [[paper]](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16055)
- **[OWE]** An Open-World Extension to Knowledge Graph Completion Models. AAAI. 2019. [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/4162)

#### Sparse KG
- **[DacKGR]** Dynamic Anticipation and Completion for Multi-Hop Reasoning over Sparse Knowledge Graph. EMNLP. 2020. [[paper]](https://www.aclweb.org/anthology/2020.emnlp-main.459)

#### Zero/One/Few-shot

