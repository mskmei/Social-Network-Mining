### 数据集下载

+ Ego-facebook : http://snap.stanford.edu/data/ego-Facebook.html
+ Cora : https://linqs-data.soe.ucsc.edu/public/lbc/cora.tgz

### 情况说明

+ 共实现了社区发现、网络分析、链接预测、节点分类任务

+ 环境配置
```
!pip install torch-scatter torch-sparse torch-cluster torch-spline-conv torch-geometric -f https://data.pyg.org/whl/torch-1.13.0+cu116.html
```

+ 运行时，节点分类任务中的模型超参数（学习率等）和优化器类型（ SGD/Adam optimizer等）需自己指定
