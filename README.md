# CommunityDetection
[![Python](https://img.shields.io/badge/Python-3.6-blue.svg)](https://www.python.org/)
[![field](https://img.shields.io/badge/Field-Complex%20Network-brightgreen.svg)](https://en.wikipedia.org/wiki/Community_structure)  
△.这些内容是我研究社区发现时的一些实验代码，主要基于```networkx```。**\*部分代码借鉴了网友的分享，已给出参考来源。**  
△.将这些代码分享出来，一是为了给刚刚进行复杂网络社区发现相关研究的朋友带来一些便利，二是以备日后不时之需。  
△.受限于学术水平与编程能力，若代码有错误或不足之处，欢迎朋友们的指正！  
△.**目前上传的算法大多为早期经典算法，未来在适当的时候会上传一些近期文献所提出的算法。**  
## 内容
### 社区发现算法
算法名称 | 参考文献 | 代码参考链接
---- | ---- | ----
GN(Girvan&Newman) | [《Community structure in social and biological networks》](https://arxiv.org/abs/cond-mat/0112110) | [zzz24512653](https://github.com/zzz24512653/CommunityDetection/blob/master/algorithm/GN.py)
Spectral Clustering | [《A tutorial on spectral clustering》](https://arxiv.org/abs/0711.0189) | [waleking](https://blog.csdn.net/waleking/article/details/7584084)


### 社区发现评价指标
#### 1. 模块度(Modularity)
![modularity](https://github.com/QinY-Stat/CommunityDetection/blob/master/images/modularity.png)  
其中m为图的边数，A为图的邻接矩阵，ki表示节点i的度，
      
