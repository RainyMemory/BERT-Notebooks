# BERT-Notebooks

## Huggingface 预训练BERT模型的使用

- 对应文件`HuggingfaceNote.ipynb`
- 对Huggingface提供的transformers库的预训练BERT的使用进行简单呈现
- 主要涉及内容为如何使用tokenizer以及如何直接载入预训练模型进行实验

## Data Analysis 简单推特情感分析

- 对应文件`DataAnalysis.ipynb`
- 主要侧重于对推特内容的分析，查看与预处理
- 展示如何载入预训练BERT并自定义模型结构
- 展示如何将输入的推特文本转化为BERT的输入格式

### 其他相关链接

- 更细致的模型搭建与训练，Sentiment Analysis 推特情感分析（kaggle）：https://www.kaggle.com/nifler/sentiment-analysis-with-sentiment140-data

## Fake & Real News 真假新闻判定

- 对应文件`playWithFakeRealNews.ipynb`
- 根据DataExplore中`newsExplore.ipynb`文件的数据观察结果进行了特征提取
- 构建了数个模型进行分类任务：
  - SML模型如：RandomForest，DecisionTree，LinearSVC
  - RNN模型
  - 预训练BERT

### 其他相关链接

- 更详细的模型搭建训练，Distinguish fake & real news 真假新闻判别（kaggle）：https://www.kaggle.com/nifler/distinguish-fake-real-news
