# 100 Must-Read NLP Papers

This is a list of 100 important natural language processing (NLP) papers that serious students and researchers working in the field should probably know about and read. This list is compiled by [Masato Hagiwara](http://masatohagiwara.net/). I welcome any feedback on this list.

This list is originally based on the answers for a Quora question I posted years ago: [What are the most important research papers which all NLP students should definitely read?](https://www.quora.com/What-are-the-most-important-research-papers-which-all-NLP-students-should-definitely-read). I thank all the people who contributed to the original post.

This list is far from complete or objective, and is evolving, as important papers are being published year after year. Please let me know via [pull requests](https://github.com/mhagiwara/100-nlp-papers/pulls) and [issues](https://github.com/mhagiwara/100-nlp-papers/issues) if anything is missing.

A paper doesn't have to be a peer-reviewed conference/journal paper to appear here. We also include tutorial/survey-style papers and blog posts that are often easier to understand than the original papers.

## Machine Learning

* [Avrim Blum and Tom Mitchell: Combining Labeled and Unlabeled Data with Co-Training, 1998.](https://www.cs.cmu.edu/~avrim/Papers/cotrain.pdf)

* [John Lafferty, Andrew McCallum, Fernando C.N. Pereira: Conditional Random Fields: Probabilistic Models for Segmenting and Labeling Sequence Data, ICML 2001.](https://repository.upenn.edu/cgi/viewcontent.cgi?article=1162&context=cis_papers)

* [Charles Sutton, Andrew McCallum. An Introduction to Conditional Random Fields for Relational Learning.](https://people.cs.umass.edu/~mccallum/papers/crf-tutorial.pdf)

* [Kamal Nigam, et al.: Text Classification from Labeled and Unlabeled Documents using EM. Machine Learning, 1999.](https://www.ri.cmu.edu/pub_files/pub1/nigam_k_1999_1/nigam_k_1999_1.pdf)

* [Kevin Knight: Bayesian Inference with Tears, 2009.](https://www.socsci.uci.edu/~lpearl/courses/readings/Knight2009_BayesWithTears.pdf)

* [Marco Tulio Ribeiro et al.: "Why Should I Trust You?": Explaining the Predictions of Any Classifier, KDD 2016.](https://arxiv.org/pdf/1602.04938.pdf)

* [Marco Tulio Ribeiro et al.: Beyond Accuracy: Behavioral Testing of NLP Models with CheckList](https://aclanthology.org/2020.acl-main.442.pdf)

## Neural Models

* [Richard Socher, et al.: Dynamic Pooling and Unfolding Recursive Autoencoders for Paraphrase Detection, NIPS 2011.](https://papers.nips.cc/paper/2011/file/3335881e06d4d23091389226225e17c7-Paper.pdf)

* [Ronan Collobert et al.: Natural Language Processing (almost) from Scratch, J. of Machine Learning Research, 2011.](https://www.jmlr.org/papers/volume12/collobert11a/collobert11a.pdf)

* [Richard Socher, et al.: Recursive Deep Models for Semantic Compositionality Over a Sentiment Treebank, EMNLP 2013.](https://aclanthology.org/D13-1170.pdf)

* [Xiang Zhang, Junbo Zhao, and Yann LeCun: Character-level Convolutional Networks for Text Classification, NIPS 2015.](https://proceedings.neurips.cc/paper/2015/file/250cf8b51c773f3f8dc8b4be867a9a02-Paper.pdf)

* [Yoon Kim: Convolutional Neural Networks for Sentence Classification, 2014.](https://arxiv.org/pdf/1408.5882.pdf)

* [Christopher Olah: Understanding LSTM Networks, 2015.](https://colah.github.io/posts/2015-08-Understanding-LSTMs/)

* [Matthew E. Peters, et al.: Deep contextualized word representations, 2018.](https://arxiv.org/pdf/1802.05365.pdf)

* [Jacob Devlin, et al.: BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding, 2018.](https://arxiv.org/pdf/1810.04805.pdf)

* [Yihan Liu et al. RoBERTa: A Robustly Optimized BERT Pretraining Approach, 2020.](https://arxiv.org/abs/1907.11692)

## Clustering & Word/Sentence Embeddings

* [Peter F Brown, et al.: Class-Based n-gram Models of Natural Language, 1992.](https://www.cs.cmu.edu/~roni/11761/PreviousYearsHandouts/classlm.pdf)

* [Tomas Mikolov, et al.: Efficient Estimation of Word Representations in Vector Space, 2013.](https://arxiv.org/pdf/1301.3781.pdf)

* [Tomas Mikolov, et al.: Distributed Representations of Words and Phrases and their Compositionality, NIPS 2013.](https://proceedings.neurips.cc/paper/2013/file/9aa42b31882ec039965f3c4923ce901b-Paper.pdf)

* [Quoc V. Le and Tomas Mikolov: Distributed Representations of Sentences and Documents, 2014.](https://arxiv.org/pdf/1405.4053.pdf)

* [Jeffrey Pennington, et al.: GloVe: Global Vectors for Word Representation, 2014.](https://aclanthology.org/D14-1162.pdf)

* [Ryan Kiros, et al.: Skip-Thought Vectors, 2015.](https://arxiv.org/pdf/1506.06726.pdf)

* [Piotr Bojanowski, et al.: Enriching Word Vectors with Subword Information, 2017.](https://arxiv.org/pdf/1607.04606.pdf)

* [Daniel Cer et al.: Universal Sentence Encoder, 2018.](https://arxiv.org/abs/1803.11175)

## Topic Models

* [Thomas Hofmann: Probabilistic Latent Semantic Indexing, SIGIR 1999.](https://sigir.org/wp-content/uploads/2017/06/p211.pdf)

* [David Blei, Andrew Y. Ng, and Michael I. Jordan: Latent Dirichlet Allocation, J. Machine Learning Research, 2003.](https://www.jmlr.org/papers/volume3/blei03a/blei03a.pdf)

## Language Modeling

* [Joshua Goodman: A bit of progress in language modeling, MSR Technical Report, 2001.](https://arxiv.org/pdf/cs/0108005.pdf)

* [Stanley F. Chen and Joshua Goodman: An Empirical Study of Smoothing Techniques for Language Modeling, ACL 2006.](https://dash.harvard.edu/bitstream/handle/1/25104739/tr-10-98.pdf;jsessionid=0F01586D4D238B2EC40A63094F9B50FC?sequence=1)

* [Yee Whye Teh: A Hierarchical Bayesian Language Model based on Pitman-Yor Processes, COLING/ACL 2006.](http://www.gatsby.ucl.ac.uk/~ywteh/research/compling/acl2006.pdf)

* [Yee Whye Teh: A Bayesian interpretation of Interpolated Kneser-Ney, 2006.](https://www.stats.ox.ac.uk/~teh/research/compling/hpylm.pdf)

* [Yoshua Bengio, et al.: A Neural Probabilistic Language Model, J. of Machine Learning Research, 2003.](https://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf)

* [Andrej Karpathy: The Unreasonable Effectiveness of Recurrent Neural Networks, 2015.](https://web.stanford.edu/class/cs379c/archive/2018/class_messages_listing/content/Artificial_Neural_Network_Technology_Tutorials/KarparthyUNREASONABLY-EFFECTIVE-RNN-15.pdf)

* [Yoon Kim, et al.: Character-Aware Neural Language Models, 2015.](https://arxiv.org/pdf/1508.06615.pdf)

* [Alec Radford, et al.: Language Models are Unsupervised Multitask Learners, 2018.](https://d4mucfpksywv.cloudfront.net/better-language-models/language_models_are_unsupervised_multitask_learners.pdf)

## Segmentation, Tagging, Parsing

* [Donald Hindle and Mats Rooth. Structural Ambiguity and Lexical Relations, Computational Linguistics, 1993.](https://aclanthology.org/J93-1005.pdf)

* [Adwait Ratnaparkhi: A Maximum Entropy Model for Part-Of-Speech Tagging, EMNLP 1996.](https://aclanthology.org/W96-0213.pdf)

* [Eugene Charniak: A Maximum-Entropy-Inspired Parser, NAACL 2000.](https://www.ling.upenn.edu/courses/cogs502/CharniakNAACL2000.pdf)

* [Michael Collins: Discriminative Training Methods for Hidden Markov Models: Theory and Experiments with Perceptron Algorithms, EMNLP 2002.](https://aclanthology.org/W02-1001.pdf)

* [Dan Klein and Christopher Manning: Accurate Unlexicalized Parsing, ACL 2003.](https://nlp.stanford.edu/~manning/papers/unlexicalized-parsing.pdf)

* [Dan Klein and Christopher Manning: Corpus-Based Induction of Syntactic Structure: Models of Dependency and Constituency, ACL 2004.](https://aclanthology.org/P04-1061.pdf)

* [Joakim Nivre and Mario Scholz: Deterministic Dependency Parsing of English Text, COLING 2004.](https://aclanthology.org/C04-1010.pdf)

* [Ryan McDonald et al.: Non-Projective Dependency Parsing using Spanning-Tree Algorithms, EMNLP 2005.](https://aclanthology.org/H05-1066.pdf)

* [Daniel Andor et al.: Globally Normalized Transition-Based Neural Networks, 2016.](https://arxiv.org/pdf/1603.06042.pdf)

* [Oriol Vinyals, et al.: Grammar as a Foreign Language, 2015.](https://proceedings.neurips.cc/paper/2015/file/277281aada22045c03945dcb2ca6f2ec-Paper.pdf)

## Sequential Labeling & Information Extraction

* [Marti A. Hearst: Automatic Acquisition of Hyponyms from Large Text Corpora, COLING 1992.](https://aclanthology.org/C92-2082.pdf)

* [Collins and Singer: Unsupervised Models for Named Entity Classification, EMNLP 1999.](https://aclanthology.org/W99-0613.pdf)

* [Patrick Pantel and Dekang Lin, Discovering Word Senses from Text, SIGKDD, 2002.](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.130.6056&rep=rep1&type=pdf)

* [Mike Mintz et al.: Distant supervision for relation extraction without labeled data, ACL 2009.](https://aclanthology.org/P09-1113.pdf)

* [Zhiheng Huang et al.: Bidirectional LSTM-CRF Models for Sequence Tagging, 2015.](https://arxiv.org/pdf/1508.01991.pdf)

* [Xuezhe Ma and Eduard Hovy: End-to-end Sequence Labeling via Bi-directional LSTM-CNNs-CRF, ACL 2016.](https://arxiv.org/pdf/1603.01354.pdf)

## Machine Translation & Transliteration, Sequence-to-Sequence Models

* [Peter F. Brown et al.: A Statistical Approach to Machine Translation, Computational Linguistics, 1990.](https://aclanthology.org/J90-2002.pdf)

* [Kevin Knight, Graehl Jonathan. Machine Transliteration. Computational Linguistics, 1992.](https://aclanthology.org/J98-4003.pdf)

* [Dekai Wu: Inversion Transduction Grammars and the Bilingual Parsing of Parallel Corpora, Computational Linguistics, 1997.](https://aclanthology.org/J97-3002.pdf)

* [Kevin Knight: A Statistical MT Tutorial Workbook, 1999.](https://www.cis.uni-muenchen.de/~fraser/readinggroup/knight_1999_TUTORIAL_model3.pdf)

* [Kishore Papineni, et al.: BLEU: a Method for Automatic Evaluation of Machine Translation, ACL 2002.](https://aclanthology.org/P02-1040.pdf)

* [Philipp Koehn, Franz J Och, and Daniel Marcu: Statistical Phrase-Based Translation, NAACL 2003.](https://aclanthology.org/N03-1017.pdf)

* [Philip Resnik and Noah A. Smith: The Web as a Parallel Corpus, Computational Linguistics, 2003.](https://aclanthology.org/J03-3002.pdf)

* [Franz J Och and Hermann Ney: The Alignment-Template Approach to Statistical Machine Translation, Computational Linguistics, 2004.](https://aclanthology.org/J04-4002.pdf)

* [David Chiang. A Hierarchical Phrase-Based Model for Statistical Machine Translation, ACL 2005.](https://aclanthology.org/P05-1033.pdf)

* [Ilya Sutskever, Oriol Vinyals, and Quoc V. Le: Sequence to Sequence Learning with Neural Networks, NIPS 2014.](https://papers.nips.cc/paper/2014/file/a14ac55a4f27472c5d894ec1c3c743d2-Paper.pdf)

* [Oriol Vinyals, Quoc Le: A Neural Conversation Model, 2015.](https://arxiv.org/pdf/1506.05869.pdf)

* [Dzmitry Bahdanau, et al.: Neural Machine Translation by Jointly Learning to Align and Translate, 2014.](https://arxiv.org/pdf/1409.0473.pdf)

* [Minh-Thang Luong, et al.: Effective Approaches to Attention-based Neural Machine Translation, 2015.](https://arxiv.org/pdf/1508.04025.pdf)

* [Rico Sennrich et al.: Neural Machine Translation of Rare Words with Subword Units. ACL 2016.](https://arxiv.org/pdf/1508.07909.pdf)

* [Yonghui Wu, et al.: Google's Neural Machine Translation System: Bridging the Gap between Human and Machine Translation, 2016.](https://arxiv.org/pdf/1609.08144.pdf)

* [Melvin Johnson, et al.: Google's Multilingual Neural Machine Translation System: Enabling Zero-Shot Translation, 2016.](https://arxiv.org/abs/1611.04558)

* [Jonas Gehring, et al.: Convolutional Sequence to Sequence Learning, 2017.](https://arxiv.org/pdf/1705.03122.pdf)

* [Ashish Vaswani, et al.: Attention Is All You Need, 2017.](https://arxiv.org/pdf/1706.03762.pdf)

## Coreference Resolution

* [Vincent Ng: Supervised Noun Phrase Coreference Research: The First Fifteen Years, ACL 2010.](https://aclanthology.org/P10-1142.pdf)

* [Kenton Lee at al.: End-to-end Neural Coreference Resolution, EMNLP 2017.](https://arxiv.org/pdf/1707.07045.pdf)

## Automatic Text Summarization

* Kevin Knight and Daniel Marcu: Summarization beyond sentence extraction. Artificial Intelligence 139, 2002.

* [James Clarke and Mirella Lapata: Modeling Compression with Discourse Constraints. EMNLP-CONLL 2007.](https://aclanthology.org/D07-1001.pdf)

* [Ryan McDonald: A Study of Global Inference Algorithms in Multi-Document Summarization, ECIR 2007.](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.94.4583&rep=rep1&type=pdf)

* [Wen-tau Yih et al.: Multi-Document Summarization by Maximizing Informative Content-Words. IJCAI 2007.](https://www.ijcai.org/Proceedings/07/Papers/287.pdf)

* [Alexander M Rush, et al.: A Neural Attention Model for Sentence Summarization. EMNLP 2015.](https://aclanthology.org/D15-1044.pdf)

* [Abigail See et al.: Get To The Point: Summarization with Pointer-Generator Networks. ACL 2017. ](https://www.aclweb.org/anthology/P17-1099/)

## Question Answering and Machine Comprehension

* [Pranav Rajpurkar et al.: SQuAD: 100,000+ Questions for Machine Comprehension of Text. EMNLP 2015.](https://arxiv.org/pdf/1606.05250.pdf)

* [Minjoon Soo et al.: Bi-Directional Attention Flow for Machine Comprehension. ICLR 2015.](https://arxiv.org/pdf/1611.01603.pdf)

## Generation, Reinforcement Learning

* [Jiwei Li, et al.: Deep Reinforcement Learning for Dialogue Generation, EMNLP 2016.](https://arxiv.org/pdf/1606.01541.pdf)

* [Marc’Aurelio Ranzato et al.: Sequence Level Training with Recurrent Neural Networks. ICLR 2016.](https://arxiv.org/pdf/1511.06732.pdf)

* [Samuel R Bowman et al.: Generating sentences from a continuous space, CoNLL 2016.](https://www.aclweb.org/anthology/K16-1002/)

* [Lantao Yu, et al.: SeqGAN: Sequence Generative Adversarial Nets with Policy Gradient, AAAI 2017.](https://www.aaai.org/Conferences/AAAI/2017/PreliminaryPapers/12-Yu-L-14344.pdf)
