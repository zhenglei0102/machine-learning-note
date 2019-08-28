1、生成式模型和判别式模型
==
生成式模型先对x和y联合分布进行建模，然后通过贝叶斯公式求得条件概率（在x发生的条件下y发生的概率）最后选择使得条件概率最大的y。 <br>
判别式模型（discriminative model）则会对条件概率直接建模。 <br>

生成式模型 <br>
--
>>朴素贝叶斯 <br>
>>K紧邻（KNN） <br>
>>混合高斯模型 <br>
>>隐马尔科夫模型（HMM） <br>
>>贝叶斯网络 <br>
>>Sigmoid Belief Networks  <br>
>>马尔科夫随机场（Markov Random Fields） <br>
>>深度信念网络（DBN)<br>

判别式模型 <br>
--
>>线性回归（Linear Regression） <br>
>>逻辑斯蒂回归（Logistic Regression） <br>
>>神经网络（NN） <br>
>>支持向量机（SVM） <br>
>>高斯过程（Gaussian Process） <br>
>>条件随机场（CRF） <br>
>>CART(Classification and Regression Tree)  <br>
