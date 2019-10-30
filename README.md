## Paperlist
2016 [Structured sequence modeling with graph convolutional recurrent networks](https://arxiv.org/pdf/1612.07659.pdf) Youngjoo Seo, Michael Defferrard, Pierre Vandergheynst and Xavier Bresson
- Idea: GCN to obtain node embeddings and LSTM to learn the dynamism
- Datasets: 
  - moving-MNIST dataset
  - Penn Treebank dataset
- Tasks:
  - Sequence Modeling
  - Natural Language Modeling

2017 [Dynamic graph convolutional networks](https://arxiv.org/pdf/1704.06199.pdf) Franco Manessia, Alessandro Rozza and Mario Manzo
- Idea: GCN to obtain node embeddings and LSTM to learn the dynamism
- Datasets: 
  - DBLP dataset
  - CAD-120 dataset
- Tasks:
  - vertex-focused classification
  - graph-focused classification

2019 [EvolveGCN: Evolving Graph Convolutional Networks for Dynamic Graphs](https://arxiv.org/pdf/1902.10191.pdf) Aldo Pareja, Giacomo Domeniconi, Jie Chen, Tengfei Ma, Toyotaro Suzumura, Hiroki Kanezashi, Tim Kaler and Charles E. Leisersen
- Idea: use a GRU to update the GCN model (network parameters) at every time step
- Datasets:
  - Bitcoin-OTC 
  - Bitcoin-Alpha 
  - AMLSim
- Tasks:
  - Node Classification
  - Edge Classification
  - Link Prediction

2019 ICLR [DyRep: Learning Representations over Dynamic Graphs](https://openreview.net/pdf?id=HyePrhR5KX) Rakshit Trivedi, Mehrdad Farajtabar, Prasenjeet Biswal and Hongyuan Zha
- Idea: temporal point process model(event sequence + continuous time)
- Datasets:
  - Social Evolution Dataset
  - Github Dataset 
- Tasks: 
  - Dynamic Link Prediction
  - Event Time Prediction
  
2019 IJCAI [Exploiting Interaction Links for Node Classification with Deep Graph Neural Networks](https://www.ijcai.org/proceedings/2019/0447.pdf) Hogun Park and Jennifer Neville
- Idea: GNN-LSTM for temporal embedding(Temporal Encoder), and NN/GN for Neighbor Encoder
- Datasets
  - DBLP
  - Facebook
  - IMDB_G IMDB_R
- Tasks:
  - Node Classification
  
2019 ICLR(submision) [Link Prediction in Hypergraphs using Graph Convolutional Networks](https://openreview.net/forum?id=ryeaZhRqFm)  
- Idea: Hypergraph (directed,undirected, unlabelled) link prediction using GCN
- Datasets
  - DBLP
  - CORA
- Tasks
  - Link Prediction
  
2019 [Temporal Neighbourhood Aggregation: Predicting Future Links in Temporal Graphs via Recurrent Variational Graph Convolutions](https://arxiv.org/pdf/1908.08402.pdf)
- Idea: encoder-decoder architecture. use GCN to learn the topology, GRU to learn the temporal information and variational sampling to create more robust and meaningful vertex level representations
- Datasets
  - Bitcoina
  - wiki
  - UCI
- Tasks
  - Link Prediction
  
2019 [GCN-GAN: A Non-linear Temporal Link Prediction Model for Weighted Dynamic Networks](https://arxiv.org/pdf/1901.09165.pdf)
- Idea: GCN+LSTM+GAN
- Datasets
  - UCSB
  - KAIST
  - BJ-Taxi
  - NumFabric
- Tasks
  - Link Prediction
  
## Some Regularly Used Datasets and Tasks in Dynamic Setting
### Datasets
- DBLP(2017CIKM, 2018AAAI, 2018KDD) [xml](https://dblp.uni-trier.de/xml/)
- Facebook(2016TKDE, 2018IJCAI, 2018AAAI)
- arxiv(2016TKDE, 2018KDD)
- wiki(2018WWW, 2018AAAI)
- YouTube(2016TKDE, 2018TKDE)

**这里有三个网址可找到公开网络**

[Koblenz Network Collection](http://konect.uni-koblenz.de/)

[Stanford Large Network Dataset Collection](http://snap.stanford.edu/data/index.html)

[Network Repository](http://networkrepository.com/)
### Tasks
- link prediction(2016TKDE, 2017ICML, 2018AAAI, 2018WWW, 2018KDD, 2018TKDE)  
> 用t时刻得到的两个节点的embeddings来预测t+1时刻这两个节点是否有边  
- node classification(2017CIKM, 2018KDD, 2018AAAI, 2018IJCAI)  
> 用t时刻得到的节点embedding作为节点特征来确定节点的标签  
- node recommendation(2018TKDE, 2018KDD)  
> 用t时刻得到的节点embeddings来确定与某一特定节点最可能相连的节点集合
