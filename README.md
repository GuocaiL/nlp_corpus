# product_testdata_kg

产品标注测试数据集

数据说明及统计结果：https://wiki.4paradigm.com/pages/viewpage.action?pageId=78133799

- open_ner_data为网上开放的ner数据集，已将不同的数据格式转化为要求的数据格式，格式转换脚本为data_transfer.py
- diversity_calculation.py为数据集样本多样性的计算，参考页面https://wiki.4paradigm.com/pages/viewpage.action?pageId=79057881
- 使用时需要添加sgns.baidubaike.bigram-char模型，该模型已经上传到gpu23的公共路径下。# re_ner_data
# nlp_corpus
