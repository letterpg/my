一./predata_fuzzywuzzy

    1. 象excel那样加行加列,汇总sum
    2. apply的使用,导入一行,获得某一列的处理后结果
    3. fuzzywuzzy库处理相似字符串
       fuzzywuzzy是利用字符串编辑距离来对相似度进行衡量,从a变到b需要几步,步数越少分数越高
    4. 1,2,3月每个地方的销售额,按州做统计,但州名可能有拼写错误

    pandas.reindex, pandas.apply , pandas.read_excel

二./predata_tel

    1. 电话用户的流失 yes or no
    2. 用户的年龄,婚否,收入,教育程度,退休否,性别,固定资产
    3. 用LabelEncoder将分类字符串变为数字
    4. 年龄分组,pd.cut
    5. 数值取对数后再做MinMaxScaler()处理
    6. 对分类数据再做onehot编码 pd.get_dummies
    7. 用train_test_split将数据分为train和test
    8. 随机森林的featureimportances可以得到特征的重要度

    pd.cut, pd.get_dummies, LabelEncoder, 

三./

