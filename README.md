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
  
## Some Regularly Used Datasets and Tasks in Dynamic Setting
### Datasets

**这里有两个网址可找到公开网络**  
[Stanford Large Network Dataset Collection](http://snap.stanford.edu/data/index.html)

[Koblenz Network Collection](http://konect.uni-koblenz.de/)

### Tasks
- link prediction
