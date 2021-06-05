

# 微博文本分析和可视化





## 1.  数据预处理

1. **prepro.py、pre_graph.py、senti_pre.py**

   为了应对各种分析需求，需要数据预处理，具体所需数据文件类型和输出的结果数据结构见这三个py文件


2. **zh_wiki.py、langconv.py**  

   这两个py文件是用于繁体转简体的无需修改


--------------------------从这里往下开始运行就行--------------------------------------------

# 2.  数据分析和可视化

1. **词云：wc.py**（需要跑完prepro.py）
   结果：jinkou_comment.png    jinkou_content.png
2. **热度地图：** **map.py**（需要跑完prepro.py）
   结果：map.html
3. **转发、评论、点赞时间序列：** **line.py**（需要跑完senti_pre.py 和 senti_analy.py）
   结果：line.html
4. **微博评论关系图：** **graph.py**（需要跑完2113pre_graph.py）
   结果：graph.html   graph.png
5. **文本聚类：** **cluster_tfidf.py** 和 **cluster_w2v.py**（需要跑完prepro.py）
   结果： cluster_tfidf.png   cluster_w2v.png
6. **LDA主题模型分析：** **LDA.py**（需要跑完senti_pre.py）**tree.py**（需要跑完senti_analy.py）
   结果：tree.png   tree.html
7. **情感分析（词典）：** **senti_analy.py**（需要跑完senti_pre.py）**3Dbar.py**（需要跑完senti_analy.py）**pie.py**（需要跑完senti_analy.py）
   结果：3dbar.png    3dbar1.png    pie.html
8. **文本相似度分析：similar.py**（仅供参考）
   结果：控制台显示
    















