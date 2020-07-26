＃100必须阅读的NLP论文

这是100篇重要的自然语言处理（NLP）论文的列表，认真研究该领域的学生和研究人员可能应该了解和阅读。此列表由[Masato Hagiwara]（http://masatohagiwara.net/）汇编。我欢迎对此列表提出任何反馈。

此列表最初基于我几年前发布的Quora问题的答案：[所有NLP学生绝对应该阅读的最重要的研究论文是什么？]（https://www.quora.com/What-are-the -最重要的研究论文，所有NLP学生都应明确阅读）。我感谢为原始帖子做出贡献的所有人员。

这份清单远非完整或客观，而且随着年复一年发表重要论文而不断发展。请通过[拉取请求]（https://github.com/mhagiwara/100-nlp-papers/pulls）和[问题]（https://github.com/mhagiwara/100-nlp-papers/issues）通知我），如果有什么遗漏。

另外，我也没有尝试包含原始论文的链接，因为要使无效链接保持最新状态需要进行大量工作。我相信您可以通过一次Google搜索（按标题）找到此处列出的大多数（如果不是全部）论文。

论文不必是经过同行评审的会议/期刊论文即可出现在这里。我们还包括教程/调查式论文和博客文章，这些文章通常比原始论文更容易理解。

##机器学习

* Avrim Blum和Tom Mitchell：将带标签的和未带标签的数据与共同训练相结合，1998年。

* John Lafferty，Andrew McCallum，Fernando C.N. Pereira：条件随机字段：用于分割和标记序列数据的概率模型，ICML 2001。

* Charles Sutton，Andrew McCallum。关系学习的条件随机场简介。

* Kamal Nigam等人：使用EM从标签和未标签文档中进行文本分类。机器学习，1999年。

凯文·奈特（Kevin Knight）：《眼泪的贝叶斯推断》，2009年。

* Marco Tulio Ribeiro等人：“我为什么要相信你？”：解释任何分类器的预测，KDD 2016。

##神经模型

*理查德·索彻（Richard Socher）等人：《用于释义检测的动态池化和展开递归自动编码器》，NIPS 2011。

* Ronan Collobert等人：《自然语言处理》（几乎），摘自Scratch，J. of Machine Learning Research，2011年。

*理查德·索彻（Richard Socher）等人：《情感树库中语义组成的递归深度模型》，EMNLP，2013年。

*张翔，赵俊波和Yann LeCun：用于文本分类的字符级卷积网络，NIPS 2015。

* Yoon Kim：卷积神经网络的句子分类，2014年。

* Christopher Olah：《了解LSTM网络》，2015年。

*马修·彼得斯（Matthew E.Peters）等：深层语境化词语表示法，2018年。

* Jacob Devlin等人：BERT：用于语言理解的深度双向变压器的预训练，2018年。

##聚类和词嵌入

* Peter F Brown等：自然语言的基于类的n元语法模型，1992年。

* Tomas Mikolov等人：“向量空间中单词表示的有效估计”，2013年。

* Tomas Mikolov等人：《单词和短语的分布式表示及其组成》，NIPS 2013。

* Quoc V. Le和Tomas Mikolov：句子和文档的分布式表示，2014年。

*杰弗里·彭宁顿（Jeffrey Pennington）等人：《格洛夫：全球语言表达载体》，2014年。

* Ryan Kiros等人：《 Skip-Thought Vectors》，2015年。

* Piotr Bojanowski等人：《利用子词信息丰富词向量》，2017年。

##主题模型

托马斯·霍夫曼（Thomas Hofmann）：概率潜在语义索引，SIGIR，1999年。

* David Blei，Andrew Y.Ng和Michael I.Jordan：Latent Dirichlet Allocation，《机器学习研究》，2003年。

##语言建模

* Joshua Goodman：语言建模方面的一些进步，MSR技术报告，2001年。

* Stanley F. Chen和Joshua Goodman：语言建模平滑技术的实证研究，ACL 2006。

* Yee Whye Teh：基于Pitman-Yor流程的分层贝叶斯语言模型，COLING / ACL 2006。

* Yee Whye Teh：对内插式Kneser-Ney的贝叶斯解释，2006年。

* Yoshua Bengio等人：《神经概率语言模型》，机器学习研究杂志，2003年。

* Andrej Karpathy：循环神经网络的不合理有效性，2015年。

* Yoon Kim等人：《角色识别神经语言模型》，2015年。

##细分，标记，解析

唐纳德·欣德尔（Donald Hindle）和Mats Rooth。结构歧义和词汇关系，计算语言学，1993年。

*等待Ratnaparkhi：用于词性标记的最大熵模型，EMNLP 1996。

Eugene Charniak：最大熵启发式解析器，NAACL 2000。

* Michael Collins：隐马尔可夫模型的判别训练方法：Perceptron算法的理论和实验，EMNLP 2002。

* Dan Klein和Christopher Manning：准确的非词法分析，ACL 2003。

* Dan Klein和Christopher Manning：基于语料库的句法结构归纳：依赖和C模型
