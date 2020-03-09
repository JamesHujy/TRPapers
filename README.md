# Updating-Work-on-Text-Reasoning

## [Content](#Content)

<a href="#Related-Work">Related Work</a>
<table>
<tr><td colspan="2"><a href="#Review">1. Review</a></td></tr> 
<tr><td colspan="2"><a href="#Methods">2. Methods</a></td></tr>
<tr>
    <td>&emsp;<a href="#Logical-Reasoning">2.1 Logical Reasoning</a></td>
    <td>&ensp;<a href="#Multi-hop-Reasoning">2.2 Multi-hop Reasoning</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#Rule-Learning">2.3 Rule Learning</a></td>
    <td>&ensp;<a href="#Relation-Extraction">2.4 Relation Extraction</a></td>
    
</tr>
<tr>
<td>&ensp;<a href="#Fact-Verification">2.5 Fact Verification</a></td>
<td>&emsp;<a href="#Knowledge-Distillation">2.6 Knowledge Distillation</a></td>

</tr>
<tr><td colspan="2"><a href="#Datasets">3. Datasets</a></td></tr> 
<tr><td colspan="2"><a href="#Tutorials">4. Tutorials</a></td></tr> 
</table>

<a href="#Plan">Plan</a>

## [Related Work](#Content)
### [Review](#Content)
1. **A Review of Relational Machine Learning for Knowledge Graphs** *Maximilian Nickel, Kevin Murphy, Volker Tresp, Evgeniy Gabrilovich* [paper](https://arxiv.org/abs/1503.00759)
1. **What Can Neural Networks Reason About?** **ICLR 2020 spotlight** *Keyulu Xu, Jingling Li, Mozhi Zhang, Simon S. Du, Ken-ichi Kawarabayashi, Stefanie Jegelka* [paper](https://openreview.net/forum?id=rJxbJeHFPS)
1. **On the Capabilities and Limitations of Reasoning for Natural Language Understanding** *Daniel Khashabi, Erfan Sadeqi Azer, Tushar Khot, Ashish Sabharwal, Dan Roth* [paper](https://arxiv.org/pdf/1901.02522.pdf)
1. **Turning 30: New Ideas in Inductive Logic Programming** *Andrew Cropper, Sebastijan Dumančić, Stephen H. Muggleton* [paper](https://arxiv.org/abs/2002.11002v2)

### [Methods](#Content)

#### [Logical Reasoning](#Content)
1. **Probabilistic Logic Neural Networks for Reasoning.** *Meng Qu, Jian Tang.* NeurIPS 2019. [paper](https://arxiv.org/pdf/1906.08495.pdf)
1. **Neural Symbolic Reader: Scalable Intergration of Distributed and Symbolic Representations for Reading Comprehension.** *Xinyuan Chen, Chen Liang, Adams Wei Yu, Denny Zhou, Dawn Song, Quoc V. Le* ICLR 2020. [paper](https://openreview.net/pdf?id=ryxjnREFwH) [code](https://github.com/yuweihao/reclor) [website](http://whyu.me/reclor/) [note](https://github.com/JamesHujy/Updating-Work-on-Text-Reasoning/blob/master/note/NeRd_Note.md)
1. **A Semantic Loss Function for Deep Learning with Symbolic Knowledge** *Jingyi Xu, Zilu Zhang, Tal Friedman, Yitao Liang, Guy Van den Broeck* ICML 2018. [paper](https://arxiv.org/abs/1711.11157)
1. **Neural Module Networks for Reasoning over Text** *Nitish Gupta1, Kevin Lin2, Dan Roth, Sameer Singh & Matt Gardner* ICLR 2020
[paper](https://openreview.net/pdf?id=SygWvAVFPr)
1. **Neural Logic Machines** *Honghua Dong, Jiayuan Mao, Tian Lin, Chong Wang, Lihong Li, Denny Zhou* ICLR 2019 [paper](https://arxiv.org/abs/1904.11694)
1. **Efficient Probabilistic Logic Reasoning with Graph Neural Networks** *Yuyu Zhang, Xinshi Chen, Yuan Yang, Arun Ramamurthy, Bo Li, Yuan Qi, Le Song* ICLR 2020 [paper](https://arxiv.org/pdf/2001.11850.pdf) 
1. **The Logical Expressiveness of Graph Neural Network** *Pablo Barcelo, Egor V. Kostylev, Mikael Monet, Jorge Perez, Juan Reutter, Juan-Pablo Silva* ICLR 2020 [paper](https://openreview.net/pdf?id=r1lZ7AEKvB)
2. **Transformers as Soft Reasoners over Language** *Peter Clark, Oyvind Tafjord, Kyle Richardson* [paper](https://arxiv.org/pdf/2002.05867.pdf) [demo](https://rule-reasoning.apps.allenai.org/)

#### [Rule Learning](#Content)
1. **(NLIL) Learn to Explain Efficiently via Neural Logic Inductive Learning** *Yuan Yang, Le Song* ICLR 2020 [paper](https://arxiv.org/pdf/1910.02481.pdf)
2. **Scalable Rule Learning via Learning Representation** *Pouya Ghiasnezhad Omran, Kewen Wang, Zhe Wang* IJCAI 2018 [paper](https://www.ijcai.org/Proceedings/2018/0297.pdf) 
3. **Iteratively Learning Embeddings and Rules for Knowledge Graph Reasoning** *Wen Zhang, Bibek Paudel, Liang Wang, Jiaoyan Chen, Hai Zhu, Wei Zhang, Abraham Bernstein, Huajun Chen* [paper](https://arxiv.org/pdf/1903.08948.pdf) 
4. **Differentiable Reasoning on Large Knowledge Bases and Natural Language** *Pasquale Minervini, Matko Bošnjak, Tim Rocktäschel, Sebastian Riedel, Edward Grefenstette* [paper](https://arxiv.org/pdf/1912.10824.pdf) 
3. **Learning Explanatory Rules from Noisy Data.** *Richard Evans, Edward Grefenstette.* [paper](https://www.ijcai.org/Proceedings/2018/0792.pdf)
1. **(NeuralLP) Differentiable Learning of Logical Rules for Knowledge Base Reasoning** *Fan Yang, Zhilin Yang, William W. Cohen* NIPS 2017 [paper](https://arxiv.org/abs/1702.08367)

#### [Multi-hop Reasoning](#Content)
1. **Learning to Retrieve Reasoning Paths over Wikipedia Graph for Question Answering** *Akari Asai, Kazuma Hashimoto, Hannaneh Hajishirzi, Richard Socher, Caiming Xiong.* ICLR 2020 [paper](https://arxiv.org/abs/1911.10470) [code](https://github.com/AkariAsai/learning_to_retrieve_reasoning_paths)
2. **Transformer-XH:Multi-Evidence Reasoning with eXtra Hop Attention** *Chen Zhao, Chenyan Xiong, Corby Rosset, Xia Song, Paul Bennett, Saurabh Tiwary.* ICLR 2020 [paper](https://openreview.net/pdf?id=r1eIiCNYwS)
1. **Multi-hop Reading Comprehension across Multiple Documents by Reasoning over Heterogeneous Graphs.** *Ming Tu, Guangtao Wang, Jing Huang, Yun Tang, Xiaodong He, Bowen Zhou.* ACL 2019. [paper](https://www.aclweb.org/anthology/P19-1260.pdf) [code](https://github.com/JD-AI-Research-Silicon-Valley/HDEGraph)
2. **Cognitive Graph for Multi-Hop Reading Comprehension at Scale** *Ming Ding, Chang Zhou, Qibin Chen, Hongxia Yang, Jie Tang.* ACL 2019 [paper](https://arxiv.org/pdf/1905.05460.pdf)
1. **Dynamically Fused Graph Network for Multi-hop Reasoning.** *Yunxuan Xiao, Yanru Qu, Lin Qiu, Hao Zhou, Lei Li, Weinan Zhang, Yong Yu* ACL 2019. [paper](https://www.aclweb.org/anthology/P19-1617.pdf)
1. **A Multi-Type Multi-Span Network for Reading Comprehension that Requires Discrete Reasoning.** *Minghao Hu, Yuxing Peng, Zhen Huang, Dongsheng Li.* EMNLP 2019. [paper](https://www.aclweb.org/anthology/D19-1170.pdf) [code](https://github.com/huminghao16/MTMSN)
1. **Multi-range Reasoning for Machine Comprehension.** *Yi Tay, Luu Anh Tuan, and Siu Cheung Hui* [paper](https://arxiv.org/pdf/1803.09074.pdf) 
1. **Differentiable Reasoning Over A Virtual Knowledge Base** *Bhuwan Dhingra, Manzil Zaheer, Vidhisha Balachandran, Graham Neubig, Ruslan Salakhutdinov1, William W. Cohen.* ICLR 2020 [paper](https://openreview.net/pdf?id=SJxstlHFPH)
1. **Scalable Neural Methods for Reasoning With a Symbolic Knowledge Base** *William W. Cohen, Haitian Sun, R. Alex Hofer, Matthew Siegler* ICLR 2020 [paper](https://arxiv.org/abs/2002.06115)
1. **Knowledge Guided Text Retrieval and Reading for Open Domain Question Answering** *Sewon Min, Danqi Chen, Luke Zettlemoyer, Hannaneh Hajishirzi* [paper](https://arxiv.org/abs/1911.03868)

#### [Relation Extraction](#Content)

1. **(OpenIE) Leveraging Linguistic Structure For Open Domain Information Extraction** *Gabor Angeli, Melvin Johnson Premkumar, Christopher D. Manning* [paper](https://nlp.stanford.edu/pubs/2015angeli-openie.pdf)

#### [Knowledge Distillation](#Content)
1. **Deep Neural Networks with Massive Learned Knowledge** *Zhiting Hu, Zichao Yang, Ruslan Salakhutdinov, Eric Xing* EMNLP 2016 [paper](https://www.aclweb.org/anthology/D16-1173/)

1. **Deep Generative Models with Learnable Knowledge Constraints** *Zhiting Hu, Zichao Yang, Ruslan Salakhutdinov, Xiaodan Liang, Lianhui Qin, Haoye Dong, Eric Xing* NIPS 2018 [paper](https://arxiv.org/abs/1806.09764)

1. **Toward Controlled Generation of Text** *Zhiting Hu, Zichao Yang, Xiaodan Liang,  Ruslan Salakhutdinov, Eric P. Xing* ICML 2017 [paper](https://arxiv.org/abs/1703.00955)

1. **Harnessing Deep Neural Networks with Logic Rules** *Zhiting Hu, Xuezhe Ma, Zhengzhong Liu, Eduard Hovy, Eric Xing* 2016 ACL [paper](https://arxiv.org/abs/1603.06318)

#### [Fact Verification](#Content)
1. **GEAR: Graph-based Evidence Aggregating and Reasoning
for Fact Verification** *Jie Zhou, Xu Han, Cheng Yang, Zhiyuan Liu, Lifeng Wang, Changcheng Li, Maosong Sun.* ACL 2019 [paper](https://www.aclweb.org/anthology/P19-1085.pdf)

### [Datasets](#Content)

1. **DROP: A Reading Comprehension Benchmark Requiring Discrete Reasoning Over Paragraphs.** *Dheeru Dua, Yizhong Wang, Pradeep Dasigi, Gabriel Stanovsky, Sameer Singh, and Matt Gardner.* NAACL 2019. [paper](aclweb.org/anthology/N19-1246.pdf) [data](https://s3-us-west-2.amazonaws.com/allennlp/datasets/drop/drop_dataset.zip) [website](https://allennlp.org/drop) 
2. **HotpotQA: A Dataset for Diverse, Explainable Multi-hop Question Answering** *Zhilin Yang, Peng Qi, Saizheng Zhang, Yoshua Bengio, William W. Cohen, Ruslan Salakhutdinov, Christopher D. Manning.* EMNLP 2018 [paper](https://arxiv.org/pdf/1809.09600.pdf) [website](https://hotpotqa.github.io/)
1. **ReClor: A Reading Comprehension Dataset Requiring Logical Reasoning.** 
*Weihao Yu, Zihang Jiang, Yanfei Dong, Jiashi Feng.* ICLR 2020. [paper](https://arxiv.org/pdf/2002.04326.pdf) [code](https://github.com/yuweihao/reclor) [website](http://whyu.me/reclor/) [note](https://github.com/JamesHujy/Updating-Work-on-Text-Reasoning/blob/master/note/ReClor_Note.md)
1. **RC-QED: Evaluating Natural Language Derivations in Multi-Hop Reading Comprehension** *Naoya Inoue, Pontus Stenetorp, Kentaro Inui* [paper](https://arxiv.org/pdf/1910.04601.pdf)
1. **Counterfactual Story Reasoning and Generation** *Lianhui Qin, Antoine Bosselut, Ari Holtzman, Chandra Bhagavatula, Elizabeth Clark, Yejin Choi* EMNLP 2019 [paper](https://arxiv.org/abs/1909.04076)
1. **Abductive Commonsense Reasoning** *Chandra Bhagavatula, Ronan Le Bras, Chaitanya Malaviya, Keisuke Sakaguchi, Ari Holtzman, Hannah Rashkin, Doug Downey, Scott Wen-tau Yih, Yejin Choi* [paper](https://arxiv.org/abs/1908.05739) [website](https://leaderboard.allenai.org/anli/submissions/public)
2. **PIQA: Reasoning about Physical Commonsense in Natural Language.** *Yonatan Bisk, Rowan Zellers, Ronan Le Bras, Jianfeng Gao, Yejin Choi.* AAAI 2020 [paper](https://arxiv.org/pdf/1911.11641.pdf)
3. **CLUTRR: A Diagnostic Benchmark for Inductive Reasoning from Text.** *Koustuv Sinha, Shagun Sodhani, Jin Dong, Joelle Pineau, William L. Hamilton* EMNLP 2019 [paper](https://www.aclweb.org/anthology/D19-1458.pdf) [code](https://github.com/facebookresearch/clutrr) [website](https://www.cs.mcgill.ca/~ksinha4/introducing-clutrr/)
9. **COSMOS QA: Machine Reading Comprehension with Contextual Commonsense Reasoning** *Lifu Huang, Ronan Le Bras, Chandra Bhagavatula, Yejin Choi* EMNLP 2019 [paper](https://www.aclweb.org/anthology/D19-1243.pdf) [website](https://wilburone.github.io/cosmos/)

### [Tutorials](#Content)
1. **Mining Knowledge Graphs from Text** *Jay Pujara, Sameer Singh* [website](https://kgtutorial.github.io/)
1. **Logic and Proof** *Jeremy Avigad, Robert Y. Lewis, and Floris van Doorn* [website](https://leanprover.github.io/logic_and_proof/index.html)
2. **Graph Neural Networks for Natural Language Processing** *Shikhar Vashishth, Y. Naganand, Partha Talukdar* EMNLP 2019 Tutorial [slides](https://shikhar-vashishth.github.io/assets/pdf/emnlp19_tutorial.pdf)


## [Plan](#Content)
#### Week 0 (2020.02.17-2020.02.23) 
* Search relative method and dataset

#### Week 1 (2020.02.24-2020.03.01)
* Organizing the papers we have read and prepare for presenting them.    
* Focus on the logical reasoning and keep on reading papers.

#### Week 2 (2020.03.02-2020.03.08)
* Meeting online and discuss what have done
* Focus on logical reasoning on rules expressed by natural language.
* Potentially start with open information extraction, build a logic graph or transfer it into a formula and then reason on it.
