This is an experimental Tensorflow implementation of Lattice LSTM - Chinese NER Using Lattice LSTM. For details about Lattice LSTM please refer to the paper [Chinese NER Using Lattice LSTM](https://arxiv.org/pdf/1805.02023.pdf) by Yue Zhang and Jie Yang.

Requirement:
======
	Python: 3.5
	TensorFlow: 1.5

Input format:
======
CoNLL format (prefer BIOES tag scheme), with each character its label for one line. Sentences are splited with a null line.

	美	B-LOC
	国	E-LOC
	的	O
	华	B-PER
	莱	I-PER
	士	E-PER

	我	O
	跟	O
	他	O
	谈	O
	笑	O
	风	O
	生	O 

Pretrained Embeddings:
====
The pretrained character and word embeddings are the same with the embeddings in the baseline of [RichWordSegmentor](https://github.com/jiesutd/RichWordSegmentor)

Character embeddings: [gigaword_chn.all.a2b.uni.ite50.vec](https://pan.baidu.com/s/1pLO6T9D)

Word(Lattice) embeddings: [ctb.50d.vec](https://pan.baidu.com/s/1pLO6T9D)

How to run the code?
====
1.
2.
3.


Resume NER data 
====
Crawled from the Sina Finance, it includes the resumes of senior executives from listed companies in the Chinese stock market. Details can be found in our paper.
