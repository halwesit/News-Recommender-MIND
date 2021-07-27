# Quick Start

In this directory, notebooks are provided to perform a quick demonstration of different algorithms such as Alternating Least Squares ([ALS](https://spark.apache.org/docs/latest/api/python/_modules/pyspark/ml/recommendation.html#ALS)) or Simple Algorithm for Recommendation ([SAR](https://github.com/Microsoft/Product-Recommendations/blob/master/doc/sar.md)). The notebooks show how to establish an end-to-end recommendation pipeline that consists of data preparation, model building, and model evaluation by using the utility functions ([reco_utils](../../reco_utils)).

| Notebook | Dataset | Environment | Description | 
| [nrms](nrms_MIND.ipynb) | MIND | Python CPU, GPU | Utilizing the Neural News Recommendation with Multi-Head Self-Attention (NRMS) [1] for news recommendation, in a Python+GPU (Tensorflow) environment.  

[1] _NRMS: Neural News Recommendation with Multi-Head Self-Attention_, Chuhan Wu, Fangzhao Wu, Suyu Ge, Tao Qi, Yongfeng Huang, Xing Xie. in Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing and the 9th International Joint Conference on Natural Language Processing (EMNLP-IJCNLP).<br>
