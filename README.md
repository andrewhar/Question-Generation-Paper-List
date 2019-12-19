# Question-Generation-Paper-List
A summary of must-read papers for Neural Question Generation (NQG)

- Contributed by **Liangming Pan** and **Yuxi Xie**.

## [Content](#content)

<table>
<tr><td colspan="2"><a href="#survey-papers">1. Survey</a></td></tr> 
<tr><td colspan="2"><a href="#models">2. Models</a></td></tr>
<tr>
    <td>&emsp;<a href="#basic-seq2seq-models">2.1 Basic Seq2Seq Models</a></td>
    <td>&ensp;<a href="#encoding-answers">2.2 Encoding Answers</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#linguistic-features">2.3 Linguistic Features</a></td>
    <td>&ensp;<a href="#question-specific-rewards">2.4 Question-specific Rewards</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#content-selection">2.5 Content Selection</a></td>
    <td>&ensp;<a href="#question-type-modeling">2.6 Question Type Modeling</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#encode-wider-contexts">2.7 Encode wider contexts</a></td>
    <td>&ensp;<a href="#other-directions">2.8 Other Directions</a></td>
</tr>
<tr><td colspan="2"><a href="#applications">2. Applications</a></td></tr> 
<tr>
    <td>&emsp;<a href="#difficulty-controllable-QG">2.1 Difficulty Controllable QG</a></td>
    <td>&ensp;<a href="#conversational-QG">2.2 Conversational QG</a></td>
</tr> 
<tr>
    <td>&emsp;<a href="#asking-special-questions">2.3 Asking special questions</a></td>
    <td>&ensp;<a href="#answer-unaware-QG">2.4 Answer-unaware QG</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#unanswerable-QG">2.5 Unanswerable QG</a></td>
    <td>&ensp;<a href="#combining-QA-&-QG">2.6 Combining QA & QG</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#QGf-from-knowledge-graphs">2.7 QG from knowledge graphs</a></td>
    <td>&ensp;<a href="#visual-question-generation">2.8 Visual Question Generation</a></td>
</tr> 
<tr><td colspan="2"><a href="#evaluation">3. Evaluation</a></td></tr>
<tr><td colspan="2"><a href="#resources">4. Resources</a></td></tr>
</table>

## [Survey papers](#content)
1. **Recent Advances in Neural Question Generation.** arxiv 2018. [paper](https://arxiv.org/pdf/1905.08949.pdf)
    
    *Liangming Pan, Wenqiang Lei, Tat-Seng Chua, Min-Yen Kan.* 

## [Models](#content)   

### [Basic Seq2Seq Models](#basic-models)

1. **Learning to ask: Neural question generation for reading comprehension.** ACL, 2017. [paper](https://www.aclweb.org/anthology/P17-1123.pdf)

    *Xinya Du, Junru Shao, Claire Cardie.*

2. **Neural question generation from text: A preliminary study.** NLPCC 2017. [paper](https://www.researchgate.net/profile/Franco_Scarselli/publication/4202380_A_new_model_for_earning_in_raph_domains/links/0c9605188cd580504f000000.pdf)

    *Qingyu Zhou, Nan Yang, Furu Wei, Chuanqi Tan, Hangbo Bao, Ming Zhou.*

### [Encoding Answers](#answer-encoding)

1. **Improving Neural Question Generation Using Answer Separation.** AAAI 2019. [paper](https://arxiv.org/pdf/1809.02393.pdf) [code](https://github.com/yanghoonkim/NQG_ASs2s)

    *Yanghoon Kim, Hwanhee Lee, Joongbo Shin, Kyomin Jung.*

2. **Improving Question Generation with Sentence-level Semantic Matching and Answer Position Inferring.** AAAI, 2020. [paper](https://arxiv.org/pdf/1912.00879.pdf)
   
   *Xiyao Ma, Qile Zhu, Yanlin Zhou, Xiaolin Li, Dapeng Wu*

### [Linguistic Features](#linguistic-features)

1. **Learning to Generate Questions by Learning What not to Generate.** WWW 2019. [paper](https://arxiv.org/pdf/1902.10418.pdf) [code](https://github.com/BangLiu/QG)

    *Bang Liu, Mingjun Zhao, Di Niu, Kunfeng Lai, Yancheng He, Haojie Wei, Yu Xu.*

### [Question-specific Rewards](#RL-rewards)

### [Content Selection](#content-selection)

1. **Answer-based Adversarial Training for Generating Clarification Questions.** NAACL, 2019. [paper](https://arxiv.org/pdf/1904.02281.pdf) [code](https://github.com/raosudha89/clarification_question_generation_pytorch)
   
   *Rao S, Daumé III H.*

2. **Learning to Generate Questions by Learning What not to Generate.** WWW 2019. [paper](https://arxiv.org/pdf/1902.10418.pdf) [code](https://github.com/BangLiu/QG)

    *Bang Liu, Mingjun Zhao, Di Niu, Kunfeng Lai, Yancheng He, Haojie Wei, Yu Xu.*

### [Question Type Modeling](#question-type-modeling)

### [Encode wider contexts](#encode-wider-contexts)

### [Other Directions](#other-model)

## [Applications](#applications)

### [Difficulty Controllable QG](#difficulty-controllable-QG)

1. **Easy-to-Hard: Leveraging Simple Questions for Complex Question Generation.** arxiv 2019. [paper](https://arxiv.org/pdf/1912.02367.pdf)

    *Jie Zhao, Xiang Deng, Huan Sun.*

2. **Difficulty Controllable Generation of Reading Comprehension Questions.** IJCAI, 2019. [paper](https://www.ijcai.org/proceedings/2019/0690.pdf)
   
   *Yifan Gao, Lidong Bing, Wang Chen, Michael R. Lyu, Irwin King* 

### [Conversational QG](#conversational-QG)

1. **Learning to Ask Questions in Open-domain Conversational Systems with Typed Decoders.** ACL, 2018. [paper](https://arxiv.org/pdf/1805.04843.pdf) [code](https://github.com/victorywys/Learning2Ask_TypedDecoder) [dataset]( http://coai.cs.tsinghua.edu.cn/hml/dataset/)
   
   *Yansen Wang, Chenyi Liu, Minlie Huang, Liqiang Nie*

2. **Interconnected Question Generation with Coreference Alignment and Conversation Flow Modeling.** ACL 2019. [paper](https://arxiv.org/pdf/1906.06893.pdf) [code](https://github.com/Evan-Gao/conversational-QG)
   
   *Yifan Gao, Piji Li, Irwin King, Michael R. Lyu*

3. **Reinforced Dynamic Reasoning for Conversational Question Generation.** ACL 2019. [paper](https://www.aclweb.org/anthology/P19-1203) [code](https://github.com/ZJULearning/ReDR) [dataset](https://stanfordnlp.github.io/coqa/)
   
   *Boyuan Pan, Hao Li, Ziyu Yao, Deng Cai, Huan Sun*

4. **Towards Answer-unaware Conversational Question Generation.** ACL Workshop 2019. [paper](https://www.aclweb.org/anthology/D19-5809.pdf)
   
   *Mao Nakanishi, Tetsunori Kobayashi, Yoshihiko Hayashi*

### [Asking special questions](#asking-special-questions)

1. **A Multi-language Platform for Generating Algebraic Mathematical Word Problems.** arxiv, 2019. [paper](https://arxiv.org/pdf/1912.01110.pdf)
   
   *Vijini Liyanage, Surangika Ranathunga*

2. **Asking the Crowd: Question Analysis, Evaluation and Generation for Open Discussion on Online Forums.** ACL, 2019. [paper](https://www.aclweb.org/anthology/P19-1497.pdf)
   
   *Zi Chai, Xinyu Xing, Xiaojun Wan, Bo Huang*

3. **Conclusion-Supplement Answer Generation for Non-Factoid Questions.** AAAI, 2020. [paper](https://arxiv.org/pdf/1912.00864.pdf)
   
   *Makoto Nakatsuji, Sohei Okui*

4. **Answer-based Adversarial Training for Generating Clarification Questions.** NAACL, 2019. [paper](https://arxiv.org/pdf/1904.02281.pdf) [code](https://github.com/raosudha89/clarification_question_generation_pytorch)
   
   *Rao S, Daumé III H.*

### [Answer-unaware QG](#answer-unaware-QG)

### [Unanswerable QG](#unanswerable-QG)

### [Combining QA & QG](#Combining-QA-&-QG)

1. **Generating Highly Relevant Questions.** EMNLP, 2019. [paper](https://arxiv.org/abs/1910.03401)
   
   *Jiazuo Qiu, Deyi Xiong*

### [QG from knowledge graphs](#QG-from-knowledge-graphs)

### [Visual Question Generation](#visual-question-generation)

## [Evaluation](#evaluation) 

## [Resources](#resources)

