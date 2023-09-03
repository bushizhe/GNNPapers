## ICLR2023

### Learning MLPs on Graphs: A Unified View of Effectiveness, Robustness, and Efficiency
GNN在非欧式结构数据上表现出惊人的性能，但由于多跳数据依赖导致扩展性受限，很难部署于实际场景中。现有方法试图通过使用来自预训练的GNN的标签仅在结点内容特征上训练MLP来解决GNN扩展性问题。
尽管MLP的性能可以显著提高，但实践中MLP很难优于GNN，原因有二：（1）缺乏图结构信息（2）结点噪声敏感。

该文提出一种Noise-robust Structure-aware MLPs on Graphs(NOSMOG)克服上述问题。首先，使用位置特征补全结点内容，以帮助MLP获得图结构信息；其次，设计了一种新的表示相似蒸馏策略，
将结构结点相似性注入到MLP中；最后，引入对抗特征增强，以确保对特征噪声的稳定学习进一步提升性能。实验表明，NOSMOG在7个数据集的transductive和inductive设置下都取得了优于GNN的效果。

### MLPInit: Embarrassingly Simple GNN Training Acceleration with MLP Initialization 

### Effects of Graph Convolutions in Multi-layer Networks

### Learnable Graph Convolutional Attention Networks

### Learning Fair Graph Representations via Automated Data Augmentations

### Spectral Augmentation for Self-Supervised Learning on Graphs

### Automated Data Augmentations for Graph Classification

### Serving Graph Compression for Graph Neural Networks（GNN压缩）


### AutoGT: Automated Graph Transformer Architecture Search

### NAGphormer: A Tokenized Graph Transformer for Node Classification in Large Graphs

### Specformer: Spectral Graph Neural Networks Meet Transformers 

### ExpressivE: A Spatio-Functional Embedding For Knowledge Graph Completion


## 
|Title|Published|Paper|Code|
|----|-----|-----|-----|
|DropEdge: Towards Deep Graph Convolutional Networks on Node Classification|ICLR2020|[paper](https://arxiv.org/pdf/1907.10903.pdf)|[DropEdge](https://github.com/DropEdge/DropEdge)|
|Simple and Deep Graph Convolutional Networks|PMLR2020|[paper](https://arxiv.org/pdf/2007.02133.pdf)|[GCNII](https://github.com/chennnM/GCNII)|


## Graph AutoEncoder
|Title|Published|Paper|Code|
|----|----|----|-----|
|GraphMAE: Self-Supervised Masked Graph Autoencoders|KDD22|[paper](https://arxiv.org/abs/2205.10803)|[GraphMAE](https://github.com/THUDM/GraphMAE)|
|GraphMAE2: A Decoding-Enhanced Masked Self-Supervised Graph Learner|WWW23|[paper](https://arxiv.org/abs/2304.04779)|[GraphMAE2](https://github.com/THUDM/GraphMAE2)|


### 
