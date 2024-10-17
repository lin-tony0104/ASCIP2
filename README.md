# 老師版本的ASC_Admission_LRU

# 執行程式
- python run.py
- 輸入cache_size(0.5% : 21990232555)
- 選擇使用的policy 輸入0或1
- 選擇使用的trace 輸入0

# note
- 修改主要都在lib/ASC_IP.py
- ASC_IP改的都是debug資訊。


# TRACE
trace下載網址:https://drive.google.com/file/d/17lv8Zd6DG1TyBdJw1WlGV25heeicDuYp/view?usp=sharing

trace位置 "D:/all_Trace/ASC-IP/wiki2018"

trace格式 : 每一行是一個request，且每行內容為 id , size

註:原始格式為 : 每一行是一個request，且每行內容為 time , id , size , extra_feature
原始版本網址 : https://github.com/sunnyszy/lrb
