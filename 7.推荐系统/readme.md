 **使用说明**
 _环境_：python3.6+
        paddlepaddle
        numpy  

 **推荐系统组成**
- checkpoint文件夹 模型训练参数
- dataset文件夹 数据集
- DataProcess.py 数据处理
- DataProcessClass 数据处理类
- MovieRecommandSModel 电影推送模型
- MovieRecommandSmodelTrain 模型训练
- RecommandExample 电影推荐实例
- mov_feat.pkl 训练好的电影特征，方便离线使用
- usr_feat.pkl 训练好的用户特征，方便离线使用

### 推荐系统的产生背景

推荐系统详细说明地址：https://www.paddlepaddle.org.cn/tutorials/projectdetail/2166620

互联网和信息计算的快速发展，衍生了海量的数据，我们已经进入了一个信息爆炸的时代，每时每刻都有海量信息产生，然而这些信息并不全是个人所关心的，用户从大量的信息中寻找对自己有用的信息也变得越来越困难。另一方面，信息的生产方也在绞尽脑汁的把用户感兴趣的信息送到用户面前，每个人的兴趣又不尽相同，所以可以实现千人千面的推荐系统应运而生。简单来说，推荐系统是根据用户的浏览习惯，确定用户的兴趣，通过发掘用户的行为，将合适的信息推荐给用户，满足用户的个性化需求，帮助用户找到对他胃口但是不易找到的信息或商品。

推荐系统在互联网和传统行业中都有着大量的应用。在互联网行业，几乎所有的互联网平台都应用了推荐系统，如资讯新闻/影视剧/知识社区的内容推荐、电商平台的商品推荐等；在传统行业中，有些用于企业的营销环节，如银行的金融产品推荐、保险公司的保险产品推荐等。

常用的推荐系统算法

1.协同过滤推荐
2.基于内容过滤推荐
3.组合推荐


 