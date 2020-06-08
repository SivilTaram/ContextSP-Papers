# Awesome ContextSP Papers

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A collection of papers about different subareas on Context-dependent Semantic Parsing (also known as Contextual Semantic Parsing, Conversational NLIDB, Dialogue SQL Generation and etc).

## Content

| Main | Sub | Decsription |
|:---|:---|:---|
| [Dataset](#dataset) | [Full Supervision](#full-supervision) | Provide supervision from NL to logic form (SQL, code) |
|  | [Weak Supervision](#weak-supervision) | Provide supervision from NL to answer (or state) |
|  | [Auxiliary Supervision](#auxiliary-supervision) | Provide supervision from incomplete NL to rewritten ones |
| [Method](#method) | [NL To SQL](#nl-to-sql) | Translating dialogue Utterances to SQL |
| | [NL To Instruction](#nl-to-instruction) | Translating dialogue Utterances to Instruction |
| | [NL To Code](#nl-to-code) | Translating uttearnces in programmtic context to code |
| | [NL To Answer](#nl-to-answer) | Translating dialogue utterances to answer directly |
| | [NL To NL](#nl-to-nl) | Rewriting incomplete dialogue utterances to complete ones |



## Dataset

### Full Supervision

1. **Expanding the Scope of the ATIS Task: The ATIS-3 Corpus** HLT 1994. [paper](https://www.aclweb.org/anthology/H94-1010.pdf)
    *Deborah A. Dahl, Madeleine Bates, Michael Brown, William Fisher, Kate Hunicke-Smith, David Pallett, Christine Pao, Alexander Rudnicky, Elizabeth Shriberg*

1. **Mapping Language to Code in Programmatic Context** EMNLP 2018. [paper](https://arxiv.org/pdf/1808.09588.pdf)

    *Srinivasan Iyer, Ioannis Konstas, Alvin Cheung, Luke Zettlemoyer*

1.  **SParC: Cross-Domain Semantic Parsing in Context** ACL 2019. [paper](https://arxiv.org/pdf/1906.02285.pdf)

    *Tao Yu, Rui Zhang, Michihiro Yasunaga, Yi Chern Tan, Xi Victoria Lin, Suyi Li, Heyang Er, Irene Li, Bo Pang, Tao Chen, Emily Ji, Shreya Dixit, David Proctor, Sungrok Shim, Jonathan Kraft, Vincent Zhang, Caiming Xiong, Richard Socher, Dragomir Radev*

1.  **CoSQL: A Conversational Text-to-SQL Challenge Towards Cross-Domain Natural Language Interfaces to Databases** EMNLP 2019. [paper](https://arxiv.org/pdf/1909.05378.pdf)

    *Tao Yu, Rui Zhang, He Yang Er, Suyi Li, Eric Xue, Bo Pang, Xi Victoria Lin, Yi Chern Tan, Tianze Shi, Zihan Li, Youxuan Jiang, Michihiro Yasunaga, Sungrok Shim, Tao Chen, Alexander Fabbri, Zifan Li, Luyao Chen, Yuwen Zhang, Shreya Dixit, Vincent Zhang, Caiming Xiong, Richard Socher, Walter S Lasecki, Dragomir Radev*

### Weak Supervision

1. **Simpler Context-Dependent Logical Forms via Model Projections** ACL 2016. [paper](https://www.aclweb.org/anthology/P16-1138.pdf)

    *Reginald Long, Panupong Pasupat, Percy Liang*

1. **Search-based Neural Structured Learning for Sequential Question Answering** ACL 2017. [paper](https://www.aclweb.org/anthology/P17-1167.pdf)
  
   *Mohit Iyyer, Wen-tau Yih, Ming-Wei Chang*

### Auxiliary Supervision

1. **FANDA: A Novel Approach to Perform Follow-up Query Analysis** AAAI 2019. [paper](https://arxiv.org/pdf/1901.08259.pdf)

    *Qian Liu, Bei Chen, Jian-Guang Lou, Ge Jin, Dongmei Zhang*


## Method

### NL To SQL

1. **Learning Context-Dependent Mappings from Sentences to Logical Form** ACL 2009. [paper](https://www.aclweb.org/anthology/P09-1110.pdf)

    *Luke Zettlemoyer, Michael Collins*

1. **Learning to Map Context-Dependent Sentences to Executable Formal Queries** NAACL 2018. [paper](https://www.aclweb.org/anthology/N18-1203.pdf)

    *Alane Suhr, Srinivasan Iyer, Yoav Artzi*

1. **Editing-Based SQL Query Generation for Cross-Domain Context-Dependent Questions** EMNLP 2019. [paper](https://arxiv.org/pdf/1909.00786.pdf)

    *Rui Zhang, Tao Yu, He Yang Er, Sungrok Shim, Eric Xue, Xi Victoria Lin, Tianze Shi, Caiming Xiong, Richard Socher, Dragomir Radev*

1. **How Far are We from Effective Context Modeling? An Exploratory Study on Semantic Parsing in Context** IJCAI 2020. [paper](https://arxiv.org/pdf/2002.00652.pdf)

   *Qian Liu, Bei Chen, Jiaqi Guo, Jian-Guang Lou, Bin Zhou, Dongmei Zhang*

### NL To Instruction

1. **Situated Mapping of Sequential Instructions to Actions with Single-step Reward Observation** ACL 2018. [paper](https://www.aclweb.org/anthology/P18-1193.pdf)

    *Alane Suhr, Yoav Artzi*
    
### NL To Code

1. **Coupling Retrieval and Meta-Learning for Context-Dependent Semantic Parsing** ACL 2019. [paper](https://arxiv.org/pdf/1906.07108.pdf)

    *Daya Guo, Duyu Tang, Nan Duan, Ming Zhou, Jian Yin*
    
### NL To Answer

1. **TAPAS: Weakly Supervised Table Parsing via Pre-training** ACL 2020. [paper](https://arxiv.org/pdf/2004.02349.pdf)

    *Jonathan Herzig, Paweł Krzysztof Nowak, Thomas Müller, Francesco Piccinno, Julian Martin Eisenschlos*

### NL To NL

1. **A Split-and-Recombine Approach for Follow-up Query Analysis** EMNLP 2019. [paper](https://www.aclweb.org/anthology/D19-1535.pdf)

    *Qian Liu, Bei Chen, Haoyan Liu, Jian-Guang Lou, Lei Fang, Bin Zhou, Dongmei Zhang*
