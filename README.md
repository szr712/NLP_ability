# 背景介绍
建立这个仓库是为了梳理自然语言处理(NLP)各个方面的知识，提升自己的核心竞争力。我觉得NLP是一个值得深耕的领域，所以希望可以不停的提升自己的段位！
  
## 深度学习自然语言处理

### 1.Transformer/Bert

| Transformer 相关知识                                         | 进度         |
| ------------------------------------------------------------ | ------------ |
| [史上最全Transformer面试题](./深度学习自然语言处理/Transformer/史上最全Transformer面试题.md) | 已完成并上传 |
| [答案解析(1)-史上最全Transformer面试题](./深度学习自然语言处理/Transformer/答案解析(1)—史上最全Transformer面试题：灵魂20问帮你彻底搞定Transformer.md) | 已经完成并上传 |
| [Pytorch代码分析--如何让Bert在finetune小数据集时更“稳”一点](./深度学习自然语言处理/Bert/Pytorch代码分析-如何让Bert在finetune小数据集时更“稳”一点.md)                            | 已经完成并上传 |
|[解决老大难问题-如何一行代码带你随心所欲重新初始化bert的某些参数(附Pytorch代码详细解读)](https://github.com/DA-southampton/NLP_ability/blob/master/%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E8%87%AA%E7%84%B6%E8%AF%AD%E8%A8%80%E5%A4%84%E7%90%86/Bert/%E8%A7%A3%E5%86%B3%E8%80%81%E5%A4%A7%E9%9A%BE%E9%97%AE%E9%A2%98-%E5%A6%82%E4%BD%95%E4%B8%80%E8%A1%8C%E4%BB%A3%E7%A0%81%E5%B8%A6%E4%BD%A0%E9%9A%8F%E5%BF%83%E6%89%80%E6%AC%B2%E9%87%8D%E6%96%B0%E5%88%9D%E5%A7%8B%E5%8C%96bert%E7%9A%84%E6%9F%90%E4%BA%9B%E5%8F%82%E6%95%B0(%E9%99%84Pytorch%E4%BB%A3%E7%A0%81).md)|已经完成并上传|
|[3分钟从零解读Transformer的Encoder](https://github.com/DA-southampton/NLP_ability/blob/master/%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E8%87%AA%E7%84%B6%E8%AF%AD%E8%A8%80%E5%A4%84%E7%90%86/Transformer/3%E5%88%86%E9%92%9F%E4%BB%8E%E9%9B%B6%E8%A7%A3%E8%AF%BBTransformer%E7%9A%84Encoder.md)|已经完成并上传|
|[原版Transformer的位置编码究竟有没有包含相对位置信息](https://github.com/DA-southampton/NLP_ability/blob/master/%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E8%87%AA%E7%84%B6%E8%AF%AD%E8%A8%80%E5%A4%84%E7%90%86/Transformer/%E5%8E%9F%E7%89%88Transformer%E7%9A%84%E4%BD%8D%E7%BD%AE%E7%BC%96%E7%A0%81%E7%A9%B6%E7%AB%9F%E6%9C%89%E6%B2%A1%E6%9C%89%E5%8C%85%E5%90%AB%E7%9B%B8%E5%AF%B9%E4%BD%8D%E7%BD%AE%E4%BF%A1%E6%81%AF.md)|已经完成并上传|
|[BN踩坑记--谈一下Batch Normalization的优缺点和适用场景](https://github.com/DA-southampton/NLP_ability/blob/master/%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E8%87%AA%E7%84%B6%E8%AF%AD%E8%A8%80%E5%A4%84%E7%90%86/Transformer/BN%E8%B8%A9%E5%9D%91%E8%AE%B0--%E8%B0%88%E4%B8%80%E4%B8%8BBatch%20Normalization%E7%9A%84%E4%BC%98%E7%BC%BA%E7%82%B9%E5%92%8C%E9%80%82%E7%94%A8%E5%9C%BA%E6%99%AF.md)|已经完成并上传|
|[谈一下相对位置编码](https://github.com/DA-southampton/NLP_ability/blob/master/%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E8%87%AA%E7%84%B6%E8%AF%AD%E8%A8%80%E5%A4%84%E7%90%86/Transformer/%E8%B0%88%E4%B8%80%E4%B8%8B%E7%9B%B8%E5%AF%B9%E4%BD%8D%E7%BD%AE%E7%BC%96%E7%A0%81.md)|已经完成并上传|
|[NLP任务中-layer-norm比BatchNorm好在哪里](https://github.com/DA-southampton/NLP_ability/blob/master/%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E8%87%AA%E7%84%B6%E8%AF%AD%E8%A8%80%E5%A4%84%E7%90%86/Transformer/NLP%E4%BB%BB%E5%8A%A1%E4%B8%AD-layer-norm%E6%AF%94BatchNorm%E5%A5%BD%E5%9C%A8%E5%93%AA%E9%87%8C.md)|已经完成并上传|
|[谈一谈Decoder模块](https://github.com/DA-southampton/NLP_ability/blob/master/%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E8%87%AA%E7%84%B6%E8%AF%AD%E8%A8%80%E5%A4%84%E7%90%86/Transformer/%E8%B0%88%E4%B8%80%E8%B0%88Decoder%E6%A8%A1%E5%9D%97.md)|已经完成并上传|
|[Transformer的并行化](https://github.com/DA-southampton/NLP_ability/blob/master/%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E8%87%AA%E7%84%B6%E8%AF%AD%E8%A8%80%E5%A4%84%E7%90%86/Transformer/Transformer%E7%9A%84%E5%B9%B6%E8%A1%8C%E5%8C%96.md)|已经完成并上传|
|[Transformer全部文章合辑](https://github.com/DA-southampton/NLP_ability/blob/master/%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E8%87%AA%E7%84%B6%E8%AF%AD%E8%A8%80%E5%A4%84%E7%90%86/Transformer/%E7%AD%94%E6%A1%88%E5%90%88%E8%BE%91.md)|已经完成并上传|

### 2.词向量-word embedding

- 词向量面试题梳理
| 词向量面试题梳理                    | 进度         |
  | -------------------------------------- | ------------ |
  | [史上最全词向量面试题-Word2vec/fasttext/glove/Elmo](https://github.com/DA-southampton/NLP_ability/blob/master/%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E8%87%AA%E7%84%B6%E8%AF%AD%E8%A8%80%E5%A4%84%E7%90%86/%E8%AF%8D%E5%90%91%E9%87%8F/%E5%8F%B2%E4%B8%8A%E6%9C%80%E5%85%A8%E8%AF%8D%E5%90%91%E9%87%8F%E9%9D%A2%E8%AF%95%E9%A2%98%E6%A2%B3%E7%90%86.md)| 已经完成并上传 |

- Word2vec

  | Word2vec相关知识                       | 进度         |
  | -------------------------------------- | ------------ |
  |[Word2vec两种训练模型详细解读-一个词经过模型训练可以获得几个词向量](https://github.com/DA-southampton/NLP_ability/blob/master/%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E8%87%AA%E7%84%B6%E8%AF%AD%E8%A8%80%E5%A4%84%E7%90%86/%E8%AF%8D%E5%90%91%E9%87%8F/%E8%81%8A%E4%B8%80%E4%B8%8BWord2vec-%E6%A8%A1%E5%9E%8B%E7%AF%87.md)|已经完成并上传|
  |[Word2vec两种优化方式细节详细解读](https://github.com/DA-southampton/NLP_ability/blob/master/%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E8%87%AA%E7%84%B6%E8%AF%AD%E8%A8%80%E5%A4%84%E7%90%86/%E8%AF%8D%E5%90%91%E9%87%8F/%E8%81%8A%E4%B8%80%E4%B8%8BWord2vec-%E8%AE%AD%E7%BB%83%E4%BC%98%E5%8C%96%E7%AF%87.md)|已经完成并上传|
  |[Word2vec-负采样和层序softmax与原模型是否等价](https://github.com/DA-southampton/NLP_ability/blob/master/%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E8%87%AA%E7%84%B6%E8%AF%AD%E8%A8%80%E5%A4%84%E7%90%86/%E8%AF%8D%E5%90%91%E9%87%8F/word2vec%E4%B8%A4%E7%A7%8D%E4%BC%98%E5%8C%96%E6%96%B9%E5%BC%8F%E7%9A%84%E8%81%94%E7%B3%BB%E5%92%8C%E5%8C%BA%E5%88%AB.md)|已经完成并上传|
  |[Word2vec为何需要二次采样以及相关细节详细解读](https://github.com/DA-southampton/NLP_ability/blob/master/%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E8%87%AA%E7%84%B6%E8%AF%AD%E8%A8%80%E5%A4%84%E7%90%86/%E8%AF%8D%E5%90%91%E9%87%8F/Word2vec%E4%B8%BA%E4%BB%80%E4%B9%88%E9%9C%80%E8%A6%81%E4%BA%8C%E6%AC%A1%E9%87%87%E6%A0%B7%EF%BC%9F.md)|已经完成并上传|
  | 基于自己语料训练词向量的各种细节和经验 |  |

- Fasttext

  | Fasttext相关知识            | 进度       |
  | --------------------------- | ---------- |
  | Fasttext源码详细解读(C++版) |  |
  | Fasttext各种细节的详细解读  |   |

- Glove

  | Glove相关知识             | 进度         |
  | ------------------------- | ------------ |
  | GLove细节详细解读         |      |
  | Glove训练词向量代码及解读 |  |

### 3 句向量-sentence embedding

无监督模式：

- 统计词袋模型表示句子向量

  | 统计词袋模型相关知识 | 进度 |
  | -------------------- | ---- |
  | One-hot/TF-IDF       |      |

- 词向量词袋模型

  | 词向量词袋模型相关知识             | 进度 |
  | ---------------------------------- | ---- |
  | 平均/tf-idf 词向量(word2vec/glove) |      |

- Doc2vec

- SIF

  | SIF 相关知识                  | 进度         |
  | ----------------------------- | ------------ |
  | SIF论文详细解读               |  |
  | SIF在中文文本上代码及效果解读 |  |

- WMD

[WMD的简单理解(不涉及优化加速)](https://github.com/DA-southampton/NLP_ability/blob/master/%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E8%87%AA%E7%84%B6%E8%AF%AD%E8%A8%80%E5%A4%84%E7%90%86/%E5%8F%A5%E5%90%91%E9%87%8F/WMD%E7%9A%84%E7%AE%80%E5%8D%95%E7%90%86%E8%A7%A3(%E4%B8%8D%E6%B6%89%E5%8F%8A%E4%BC%98%E5%8C%96%E5%8A%A0%E9%80%9F).md)

- Skip-Thought vecotrs

- Quick-Thought Vectors

- Power Mean 均值模型

有监督：

- Cove

- InferSent

- Bert

  | Bert表示句向量 相关知识    | 进度           |
  | -------------------------- | -------------- |
  | Bert表示句向量效果详细解读 |  |

### 文本相似度
  | 文本相似度 相关知识    | 进度           |
  | -------------------------- | -------------- |
  | 基本相似度模型介绍 |  |

### 4. 机器翻译

| 机器翻译相关知识                      | 进度         |
| ------------------------------------- | ------------ |
| OpenNMT源代码解读(pytorch版)          |        |
| 手撕Seq2seq-attention机器翻译代码     |  |
| 基于seq2seq机器翻译的各种优化策略解读 |  |
| subword相关论文详细解读               |  |
| ConS2S论文详细解读                    |  |
| GNMT论文详细解读                      |  |
| Seq2seq过程图画版详细解读             |  |

### 5. 命名体识别

| 命名体识别相关资源         | 进度         |
| -------------------------- | ------------ |
| HMM/CRF 详细解读           |  |
| BiLstm-CRF详细解读         |  |
| 手撕BiLSTM-CRF代码         |      |
| 词典匹配命名体识别详细解读 |  |
| 命名体识别最新进展         |      |

### 6. 文本分类

| 文本分类相关知识                         | 进度         |
| ---------------------------------------- | ------------ |
| TextCNN论文详细解读                      |  |
| 手撕 TextCNN/Fasttext/Albert 文本分类    |  |
| TextCNN/Fasttext/Albert 实际工作应用经验 |  |
| 多标签文本分类                           |     |
| 文本分类各种优化策略和方法               |    |

### 7. 关键词提取

| 关键词提取相关知识      | 进度         |
| ----------------------- | ------------ |
| TFIDF模型提取关键词解读 | |
| TextRank提取关键词      |  |
| 各种dirty工作技巧       |  |


## 搜索
| 搜索相关知识                   | 进度         |
  | -------------------------------------- | ------------ |
  | [各种关于搜索的好文章资源总结-看到比较不错的就放上来](https://github.com/DA-southampton/NLP_ability/blob/master/%E6%90%9C%E7%B4%A2/%E6%90%9C%E7%B4%A2%E8%B5%84%E6%BA%90%E6%80%BB%E7%BB%93-%E6%8C%81%E7%BB%AD%E6%9B%B4%E6%96%B0.md)           |  |


## 推荐系统

| 推荐系统相关知识                       | 进度         |
  | -------------------------------------- | ------------ |
  | [各种关于推荐的好文章资源总结-看到比较不错的就放上来](https://github.com/DA-southampton/NLP_ability/blob/master/%E6%8E%A8%E8%8D%90/%E6%8E%A8%E8%8D%90%E8%B5%84%E6%BA%90%E6%9B%B4%E6%96%B0.md)                  |  |



## 模型部署

### 1.Kafka

### 2.Docker

### 3.Elasticsearch

### 4.Flask+nginx

### 5. Grpc

### 6. TensorRT

## 数据结构
主要是刷leetcode，和剑指offer，刷题不在多，在思路，在质量
