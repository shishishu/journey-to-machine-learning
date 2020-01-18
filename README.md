## Way to Machine Learning

### General
I will share my learning path and it is meaningful as records personally. Hope it helps.

### Update
***
#### *Phase 3*

#### Jul 2019 to Dec 2019, 6 months

##### [Work at BILIBILI] Algorithm Engineer

##### [Algorithms] Video Content Understanding
- Classification with XGBoost, BERT (binary/multi-label)
- Fine tune large BERT models with multi-gpu support
- Extensive paper reading and summary sharing: [Pre-trained Language Models](https://github.com/shishishu/way-to-machine-learning/blob/master/docs/pretrained_language_models_201912.pptx)

##### [Engineering]
- Model: publish and online serving
- HiveQL: training data preparation and statistics data report
- GRPC

##### [Business] Recommend System
- Be familiar with Recall/Rank/Strategy modules gradually

##### [CS fundamentals] Data Structure
- [Data Structure I, by 邓金辉@THU](https://next.xuetangx.com/learn/THU08091000384/THU08091000384/1391601/article/1007134)
- [leetcode-python-java](https://github.com/shishishu/leetcode-python-java):
    - update continuously
    - interactive as jupyter notebook and implemented in Java also
    
##### [Programming] Java
- [Java基础入门笔记](https://github.com/JackChan1999/Java_Basic_Introduction)
- Leetcode practice


***
#### *Phase 2*

#### Jan 2019 to Feb 2019, 2 months
##### [Project] [广告点击率预测：Criteo CTR](https://www.kaggle.com/c/criteo-display-ad-challenge/overview)
- [Codes at Github, by lambdaji](https://github.com/lambdaji/tf_repos)
    - a good introduction to CTR field: mainstream models are covered, including FM, FFM, DeepFM, Wide&Deep and etc.
    - a good tutorial to tensorflow framework: codes are implemented by tensorflow and high-level APIs e.g. tf.Estimator and tf.Serving are used
- Papers reading: to understand CTR models systematically

##### [Project] [支付风险识别：ATEC Payrisk](https://dc.cloud.alipay.com/index#/topic/intro?id=9)
- Feature selection: avoid overfitting in test dataset
- Practice with XGBoost

##### [Course] [Tensorflow for Deep Learning Research, by Chip Huyen@Stanford](http://web.stanford.edu/class/cs20si/)

##### [Intern Hunting]

#### Mar 2019 to Jun 2019, 4 months
##### [Project] Captcha Recognition
- [python-captcha-recognition](https://github.com/shishishu/python-captcha-recognition): generate labels with OCR automatically and train MLP classifier to recognize captcha (accuracy: 60%)
- [pytorch-captcha-recognition](https://github.com/shishishu/pytorch-captcha-recognition): generate captcha-label pairs automatically and train ResNet model to recognize captcha (accuracy: 90%)

##### [Project] Anti-crawling Fontlib in Website
- [anti-crawl-fontlib-img](https://github.com/shishishu/anti-crawl-fontlib-img):
    - process WOFF file in anti-crawling and reconstruct fontlib (key-char pairs) for further text parsing dynamically
    - char is obtained via OCR method and accuracy could reach 90%
- [anti-crawl-fontlib-svg](https://github.com/shishishu/anti-crawl-fontlib-svg):
    - convert fontlib into SVG files and use unique d-path as retrieval feature
    - accuracy could reach almost 100% within 1s, 20x faster than previous OCR method

##### [Project] [tensorflow-nlp-sentiment-analysis](https://github.com/shishishu/tensorflow-nlp-sentiment-analysis)
- Sentiment analysis of restaurant reviews from Dianping, implemented by tensorflow (including estimator and serving)
- It is also a good tutorial for basic nlp models (e.g. LSTM and its variants) and multi-head attention from Transformers

##### [Course] Natural Language Processing with Deep Learning, by Manning@Stanford
- [Classic course by 2017](https://www.bilibili.com/video/av41393758?from=search&seid=1992633283967736843), both English and Chinese subtitles are included
- [Latest course by 2019](https://www.bilibili.com/video/av46216519?from=search&seid=1752508603086605546), English subtitles only

##### [Job Hunting]


***
#### *Phase 1*
#### Jul 2018 to Aug 2018, 2 months
##### [Course] Machine Learning, by Andrew Ng@Stanford
- [Online videos](https://www.bilibili.com/video/av9912938?from=search&seid=9203271708128696649)
    - both English and Chinese subtitles are included
    - total 20 hours
- [Coursera enrollment](https://www.coursera.org/learn/machine-learning)
    - take quizs after each unit
    - finish 8 programming tasks via Matlab

##### [Programming] [Python教程, by 廖雪峰](https://www.liaoxuefeng.com/wiki/1016959663602400)
- Chapter: [Python简介](https://www.liaoxuefeng.com/wiki/1016959663602400/1016959735620448) to [面向对象编程](https://www.liaoxuefeng.com/wiki/1016959663602400/1017495723838528)
- Learn and practice via Jupyter Notebook

##### [Programming] Numpy (in Python)

#### Sep 2018 to Oct 2018, 2 months
##### [Book] [统计学习方法, by 李航](https://book.douban.com/subject/10590856/)
- Basic theory of Machine Learning
- **Study and derive formuolas is strongly recommended**

##### [Book] [机器学习实战](https://book.douban.com/subject/24703171/)
- Codes in Python is included
- Select chapter and practice codes corresponding to 统计学习方法

##### [Programming] Pandas, sk-learn (in Python)

#### Nov 2018 to Dec 2018, 2 months
##### [Project] Kaggle mini-projects practice (5+)
- Start with [Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic)
- Target: go through the entire process, including feature engineering, modelling and evaluation

##### [Course] Data Structure I, by 邓金辉@THU
- [Online videos](https://www.xuetangx.com/courses/course-v1:TsinghuaX+30240184+sp/about)
- Data Structure II should be continued

##### [Book] [面向数据科学家的实用统计学](https://book.douban.com/subject/30354581/)


***
#### Refresh on Jul 2020 next time.

### More
- Let's play with data
- New perspective will be provided by Machine Learning
- Big thanks to Tao Li, Haha Hu, Jiajia Cong, Jianxiong Ma
