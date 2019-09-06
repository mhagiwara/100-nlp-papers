# 100 Must-Read NLP Papers

This is a list of 100 important natural language processing (NLP) papers that serious students and researchers working in the field should probably know about and read. This list is compiled by [Masato Hagiwara](http://masatohagiwara.net/). I welcome any feedback on this list.

This list is originally based on the answers for a Quora question I posted years ago: [What are the most important research papers which all NLP studnets should definitely read?](https://www.quora.com/What-are-the-most-important-research-papers-which-all-NLP-students-should-definitely-read). I thank all the people who contributed to the original post.

This list is far from complete or objective, and is evolving, as important papers are being published year after year. Please let me know via [pull requests](https://github.com/mhagiwara/100-nlp-papers/pulls) and [issues](https://github.com/mhagiwara/100-nlp-papers/issues) if anything is missing.

Also, I didn't try to include links to original papers since it is a lot of work to keep dead links up to date. I'm sure you can find most (if not all) of the papers listed here via a single Google search by their titles.

A paper doesn't have to be a peer-reviewed conference/journal paper to appear here. We also include tutorial/survey-style papers and blog posts that are often easier to understand than the original papers.

## Clustering & Word Embeddings

* Peter F Brown, et al.: Class-Based n-gram Models of Natural Language, 1992.

* Tomas Mikolov, et al.: Efficient Estimation of Word Representations in Vector Space, 2013.

* Tomas Mikolov, et al.: Distributed Representations of Words and Phrases and their Compositionality, NIPS 2013.

* Quoc V. Le and Tomas Mikolov: Distributed Representations of Sentences and Documents, 2014.

* Jeffrey Pennington, et al.: GloVe: Global Vectors for Word Representation, 2014.

* Ryan Kiros, et al.: Skip-Thought Vectors, 2015.

* Piotr Bojanowski, et al.: Enriching Word Vectors with Subword Information, 2017.

## Language Modeling

* Joshua Goodman: A bit of progress in language modeling, MSR Technical Report, 2001.

* Stanley F. Chen and Joshua Goodman: An Empirical Study of Smoothing Techniques for Language Modeling, ACL 2006.

* Yee Whye Teh: A Hierarchical Bayesian Language Model based on Pitman-Yor Processes, COLING/ACL 2006.

* Yee Whye Teh: A Bayesian interpretation of Interpolated Kneser-Ney, 2006.

* Yoshua Bengio, et al.: A Neural Probabilistic Language Model, J. of Machine Learning Research, 2003.

* Andrej Karpathy: The Unreasonable Effectiveness of Recurrent Neural Networks, 2015.

* Yoon Kim, et al.: Character-Aware Neural Language Models, 2015.

## Segmentation, Tagging, Parsing

* Donald Hindle and Mats Rooth. Structural Ambiguity and Lexical Relations, Computational Linguistics, 1993.

* Adwait Ratnaparkhi: A Maximum Entropy Model for Part-Of-Speech Tagging, EMNLP 1996.

* Michael Collins: Discriminative Training Methods for Hidden Markov Models: Theory and Experiments with Perceptron Algorithms, EMNLP 2002.

* Dan Klein and Christopher Manning: Accurate Unlexicalized Parsing, ACL 2003.

* Dan Klein and Christopher Manning: Corpus-Based Induction of Syntactic Structure: Models of Dependency and Constituency, ACL 2004.

* Joakim Nivre and Mario Scholz: Deterministic Dependency Parsing of English Text, COLING 2004.

* Ryan McDonald et al.: Non-Projective Dependency Parsing using Spanning-Tree Algorithms, EMNLP 2005.

* Daniel Andor et al.: Globally Normalized Transition-Based Neural Networks, 2016.

* Oriol Vinyals, et al.: Grammar as a Foreign Language, 2015.

## Sequential Labeling & Information Extraction

* Marti A. Hearst: Automatic Acquisition of Hyponyms from Large Text Corpora, COLING 1992.

* Collins and Singer: Unsupervised Models for Named Entity Classification, EMNLP 1999.

* Patrick Pantel and Dekang Lin, Discovering Word Senses from Text, SIGKDD, 2002.

* Mike Mintz et al.: Distant supervision for relation extraction without labeled data, ACL 2009.

* Zhiheng Huang et al.: Bidirectional LSTM-CRF Models for Sequence Tagging, 2015.

## Machine Learning

* Avrim Blum and Tom Mitchell: Combining Labeled and Unlabeled Data with Co-Training, 1998.

* John Lafferty, Andrew McCallum, Fernando C.N. Pereira: Conditional Random Fields: Probabilistic Models for Segmenting and Labeling Sequence Data, ICML 2001.

* Charles Sutton, Andrew McCallum. An Introduction to Conditional Random Fields for Relational Learning.

* Kamal Nigam, et al.: Text Classification from Labeled and Unlabeled Documents using EM. Machine Learning, 1999.

* Kevin Knight: Bayesian Inference with Tears, 2009.

## Topic Models

* Thomas Hofmann: Probabilistic Latent Semantic Indexing, SIGIR 1999.

* David Blei, Andrew Y. Ng, and Michael I. Jordan: Latent Dirichlet Allocation, J. Machine Learning Research, 2003.

## Machine Translation & Transliteration, Sequence-to-Sequence Models

* Peter F. Brown et al.: A Statistical Approach to Machine Translation, Computational Linguistics, 1990.

* Kevin Knight, Graehl Jonathan. Machine Transliteration. Computational Linguistics, 1992.

* Dekai Wu: Inversion Transduction Grammars and the Bilingual Parsing of Parallel Corpora, Computational Linguistics, 1997.

* Kevin Knight: A Statistical MT Tutorial Workbook, 1999.

* Kishore Papineni, et al.: BLEU: a Method for Automatic Evaluation of Machine Translation, ACL 2002.

* Philipp Koehn, Franz J Och, and Daniel Marcu: Statistical Phrase-Based Translation, NAACL 2003.

* Philip Resnik and Noah A. Smith: The Web as a Parallel Corpus, Computational Linguistics, 2003.

* Franz J Och and Hermann Ney: The Alignment-Template Approach to Statistical Machine Translation, Computational Linguistics, 2004.

* David Chiang. A Hierarchical Phrase-Based Model for Statistical Machine Translation, ACL 2005.

* Ilya Sutskever, Oriol Vinyals, and Quoc V. Le: Sequence to Sequence Learning with Neural Networks, NIPS 2014.

* Oriol Vinyals, Quoc Le: A Neural Conversation Model, 2015.

* Dzmitry Bahdanau, et al.: Neural Machine Translation by Jointly Learning to Align and Translate, 2014.

* Minh-Thang Luong, et al.: Effective Approaches to Attention-based Neural Machine Translation, 2015.

* Yonghui Wu, et al.: Google's Neural Machine Translation System: Bridging the Gap between Human and Machine Translation, 2016.

* Jonas Gehring, et al.: Convolutional Sequence to Sequence Learning, 2017.

* Ashish Vaswani, et al.: Attention Is All You Need, 2017.


## Automatic Text Summarization

* Kevin Knight and Daniel Marcu: Summarization beyond sentence extraction. Artificial Intelligence 139, 2002.

* James Clarke and Mirella Lapata: Modeling Compression with Discourse Constraints. EMNLP-CONLL 2007.

* Ryan McDonald: A Study of Global Inference Algorithms in Multi-Document Summarization, ECIR 2007.

* Wen-tau Yih et al.: Multi-Document Summarization by Maximizing Informative Content-Words. IJCAI 2007.

* Alexander M Rush, et al.: A Neural Attention Model for Sentence Summarization. EMNLP 2015.

## Neural Models

* Richard Socher, et al.: Dynamic Pooling and Unfolding Recursive Autoencoders for Paraphrase Detection, NIPS 2011.

* Ronan Collobert et al.: Natural Language Processing (almost) from Scratch, J. of Machine Learning Research, 2011.

* Richard Socher, et al.: Recursive Deep Models for Semantic Compositionality Over a Sentiment Treebank, EMNLP 2013.

* Xiang Zhang, Junbo Zhao, and Yann LeCun: Character-level Convolutional Networks for Text Classification, NIPS 2015.

* Yoon Kim: Convolutional Neural Networks for Sentence Classification, 2014.

* Christopher Olah: Understanding LSTM Networks, 2015.

* Matthew E. Peters, et al.: Deep contextualized word representations, 2018.

* Jacob Devlin, et al.: BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding, 2018.

## Generation, Reinforcement Learning

* Jiwei Li, et al.: Deep Reinforcement Learning for Dialogue Generation, EMNLP 2016.

* Lantao Yu, et al.: SeqGAN: Sequence Generative Adversarial Nets with Policy Gradient, AAAI 2017.
