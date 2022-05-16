# 文本挖掘 Text Mining
* [文本数据预处理](https://nbviewer.org/github.com/CHUNHAN-FANG/Text_Mining/blob/main/文本数据预处理.ipynb)
：清洗去除非中文词及标点符号，保留指定特殊名词整体，使用停用词，分词
（[jieba分词](https://nbviewer.org/github.com/CHUNHAN-FANG/Text_Mining/blob/main/jieba_paddle.ipynb)）等

* [词云](https://nbviewer.org/github.com/CHUNHAN-FANG/Text_Mining/blob/main/词云.ipynb)
：分词后词频统计，词云自定义绘制

* [文本多分类](https://nbviewer.org/github.com/CHUNHAN-FANG/Text_Mining/blob/main/sklearn文本多分类.ipynb)
：基于sklearn的线性支持向量机模型，对旅游评论进行情感正负向分类

* 主题分析
  * [LDA模型](https://nbviewer.org/github.com/CHUNHAN-FANG/Text_Mining/blob/main/主题分析_LDA.ipynb)<br>
  潜在狄利克雷分布模型（Latent Dirichlet Allocation, LDA）于 2003 年由Blei 等人提出，是目前非监督机器学习领域的经典主题模型。<br>
  LDA 是一个多层次贝叶斯模型，将参数视为随机变量用超参数予以控制，体现彻底的概率统计思想，利用概率生成模型；该模型可从大量文本数据集中挖掘出潜在的主题信息，具有良好的扩展性。
  * [CorEx模型](https://nbviewer.org/github.com/CHUNHAN-FANG/Text_Mining/blob/main/主题分析_CorEx.ipynb)<br>
  CorEx 模型是一种通过关联解释（Correlation Explanation, CorEx）进行主题建模的方法，是一种学习文档中潜在主题的信息理论方法。CorEx 不同于LDA，它不假设潜在的生成模型，而是通过信息理论框架最大程度地学习信息主题。<br>
  2017 年 Gallagher 等提出加入少许先验知识的分层主题模型 CorEx，不同于主流的概率生成主题模型，CorEx 通过关联解释（Correlation Explanation）进行主题建模可产生丰富的主题，这些主题可以最大限度地提供一组文本数据的信息。CorEx 模型以轻量级的无监督式主题模型为基础，可扩展为分层主题建模与半监督式主题模型，支持通过锚定词（自由设置先验主题关键词）来集成领域知识，支持细粒度的主题分析。
  [Gallagher的CorEx介绍文档](https://nbviewer.org/github.com/CHUNHAN-FANG/Text_Mining/blob/main/Anchored_CorEx_Ryan%20J.%20Gallagher.ipynb)
<br><br>
* 小论文
  * [基于图文评论综合分析的上海迪士尼旅游形象感知研究](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/9d5a9e92-2337-4167-b037-d156654966bb/%E6%96%B9%E7%BA%AF%E6%B6%B5-%E5%9F%BA%E4%BA%8E%E5%9B%BE%E6%96%87%E8%AF%84%E8%AE%BA%E7%BB%BC%E5%90%88%E5%88%86%E6%9E%90%E7%9A%84%E4%B8%8A%E6%B5%B7%E8%BF%AA%E5%A3%AB%E5%B0%BC%E6%97%85%E6%B8%B8%E5%BD%A2%E8%B1%A1%E6%84%9F%E7%9F%A5%E7%A0%94%E7%A9%B6.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220516%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220516T175839Z&X-Amz-Expires=86400&X-Amz-Signature=20ff9c4d6578ef8b7014149423006f910a6e25c705d5cf164ff8e8237c5109d1&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22%25E6%2596%25B9%25E7%25BA%25AF%25E6%25B6%25B5-%25E5%259F%25BA%25E4%25BA%258E%25E5%259B%25BE%25E6%2596%2587%25E8%25AF%2584%25E8%25AE%25BA%25E7%25BB%25BC%25E5%2590%2588%25E5%2588%2586%25E6%259E%2590%25E7%259A%2584%25E4%25B8%258A%25E6%25B5%25B7%25E8%25BF%25AA%25E5%25A3%25AB%25E5%25B0%25BC%25E6%2597%2585%25E6%25B8%25B8%25E5%25BD%25A2%25E8%25B1%25A1%25E6%2584%259F%25E7%259F%25A5%25E7%25A0%2594%25E7%25A9%25B6.pdf%22&x-id=GetObject) 2021.05
  * [新冠疫情下的微博内容主题挖掘—基于 LDA 与 CorEx 主题模型的文本内容细粒度分析](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/3a0de925-813e-4435-b74d-d71724c43f92/%E6%96%B9%E7%BA%AF%E6%B6%B5_%E6%96%B0%E5%86%A0%E7%96%AB%E6%83%85%E4%B8%8B%E7%9A%84%E5%BE%AE%E5%8D%9A%E5%86%85%E5%AE%B9%E4%B8%BB%E9%A2%98%E6%8C%96%E6%8E%98%E5%9F%BA%E4%BA%8E_LDA_%E4%B8%8E_CorEx_%E4%B8%BB%E9%A2%98%E6%A8%A1%E5%9E%8B%E7%9A%84%E6%96%87%E6%9C%AC%E5%86%85%E5%AE%B9%E7%BB%86%E7%B2%92%E5%BA%A6%E5%88%86%E6%9E%90.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220516%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220516T180009Z&X-Amz-Expires=86400&X-Amz-Signature=e736b176de113a0e79fdb777515259d3afdd5da0571202af0e66360e6a6753c8&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22%25E6%2596%25B9%25E7%25BA%25AF%25E6%25B6%25B5_%25E6%2596%25B0%25E5%2586%25A0%25E7%2596%25AB%25E6%2583%2585%25E4%25B8%258B%25E7%259A%2584%25E5%25BE%25AE%25E5%258D%259A%25E5%2586%2585%25E5%25AE%25B9%25E4%25B8%25BB%25E9%25A2%2598%25E6%258C%2596%25E6%258E%2598%25E2%2580%2594%25E5%259F%25BA%25E4%25BA%258E%2520LDA%2520%25E4%25B8%258E%2520CorEx%2520%25E4%25B8%25BB%25E9%25A2%2598%25E6%25A8%25A1%25E5%259E%258B%25E7%259A%2584%25E6%2596%2587%25E6%259C%25AC%25E5%2586%2585%25E5%25AE%25B9%25E7%25BB%2586%25E7%25B2%2592%25E5%25BA%25A6%25E5%2588%2586%25E6%259E%2590.pdf%22&x-id=GetObject) 2020.06
