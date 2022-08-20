# 文本挖掘 Text Mining
* [文本数据预处理](https://nbviewer.org/github/CHUNHAN-FANG/Text_Mining/blob/main/文本数据预处理.ipynb)
：清洗去除非中文词及标点符号，保留指定特殊名词整体，使用停用词，分词
（[jieba分词](https://nbviewer.org/github/CHUNHAN-FANG/Text_Mining/blob/main/jieba_paddle.ipynb)）等

* [词云](https://nbviewer.org/github/CHUNHAN-FANG/Text_Mining/blob/main/词云.ipynb)
：分词后词频统计，词云自定义绘制

* [文本多分类](https://nbviewer.org/github/CHUNHAN-FANG/Text_Mining/blob/main/sklearn文本多分类.ipynb)
：基于sklearn的线性支持向量机模型，对旅游评论进行情感正负向分类

* 主题分析
  * [LDA模型](https://nbviewer.org/github/CHUNHAN-FANG/Text_Mining/blob/main/主题分析_LDA.ipynb)<br>
  潜在狄利克雷分布模型（Latent Dirichlet Allocation, LDA）于 2003 年由Blei 等人提出，是目前非监督机器学习领域的经典主题模型。<br>
  LDA 是一个多层次贝叶斯模型，将参数视为随机变量用超参数予以控制，体现彻底的概率统计思想，利用概率生成模型；该模型可从大量文本数据集中挖掘出潜在的主题信息，具有良好的扩展性。
  * [CorEx模型](https://nbviewer.org/github/CHUNHAN-FANG/Text_Mining/blob/main/主题分析_CorEx.ipynb)<br>
  CorEx 模型是一种通过关联解释（Correlation Explanation, CorEx）进行主题建模的方法，是一种学习文档中潜在主题的信息理论方法。CorEx 不同于LDA，它不假设潜在的生成模型，而是通过信息理论框架最大程度地学习信息主题。<br>
  2017 年 Gallagher 等提出加入少许先验知识的分层主题模型 CorEx，不同于主流的概率生成主题模型，CorEx 通过关联解释（Correlation Explanation）进行主题建模可产生丰富的主题，这些主题可以最大限度地提供一组文本数据的信息。CorEx 模型以轻量级的无监督式主题模型为基础，可扩展为分层主题建模与半监督式主题模型，支持通过锚定词（自由设置先验主题关键词）来集成领域知识，支持细粒度的主题分析。
  [Gallagher的CorEx介绍文档](https://nbviewer.org/github/CHUNHAN-FANG/Text_Mining/blob/main/Anchored_CorEx_Ryan%20J.%20Gallagher.ipynb)
<br><br>
* 小论文写作
  * [基于图文评论综合分析的上海迪士尼旅游形象感知研究] 2021.05
  * [新冠疫情下的微博内容主题挖掘—基于 LDA 与 CorEx 主题模型的文本内容细粒度分析] 2020.06
