文本分类 阅读笔记
====

综述
-----
1，http://t.cn/RKoli7R?u=1402400261&m=4129293221331938&cu=2634934091（墙外）  https://pan.baidu.com/s/1qY6XKWO（墙内）  shadow  to deep nn,主要是讲深度学习，对比了网络模型中的Embedding、Deep representation（rnn、cnn）、Fully connected part（bn、dropout等等）<br>
2，https://zhuanlan.zhihu.com/p/25928551  主要是深度学习，传统的分类方法提了下，看到的比较完整的一份综述<br>


实际应用：
-----
1，http://blog.csdn.net/han_xiaoyang/article/details/50616559  nb应用在文本分类中 从问题出发，讲解很详细<br>
2，http://www.wildml.com/2015/09/recurrent-neural-networks-tutorial-part-1-introduction-to-rnns/  讲rnn、lstm、gru的tutorial<br>
3,http://nadbordrozd.github.io/blog/2017/08/12/looking-for-the-text-top-model/  文本分类实验集合 （代码写得很漂亮）<br>
4，http://www.jeyzhang.com/cnn-learning-notes-1.html cnn相关介绍<br>

论文：
-----
1，https://www.aclweb.org/anthology/P12-2018 Stanford NLP Group 2012年 传统分类方法 nb、mnb、svm、nbsvm等对比<br>
  nbsvm代码可参考 https://github.com/sidaw/nbsvm（可惜是matlab，但是readme中有python版本链接地址）<br>
2，https://arxiv.org/abs/1408.5882 kim的 cnn文本分类 <br>
  代码地址可参考 https://github.com/dennybritz/cnn-text-classification-tf（tensorflow）  这个是静态的输入<br>
  https://github.com/yoonkim/CNN_sentence（theano） 静态和动态输入都有 ps：选择深度学习框架也是一门学问，偏爱谷歌<br>
3，http://aclweb.org/anthology/P14-1062 牛津大学 dcnn  动态k-max plooling以及unfolding策略<br>
   代码地址可参考 https://github.com/lc222/Dynamic-CNN-Sentence-Classification-TF 代码流程与论文流程是一致的<br/>
4，http://aclweb.org/anthology/I17-1026  对比cnn的一些参数对文本分类的影响 从输入到卷积核大小、卷积核个数等等 实验做的真的多 最后给出了一些实践技巧 例如卷积核的大小和卷积核的个数选择等等<br>


未完待续....
-----

