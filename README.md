# 项目文件说明
HUAWEI-change
│  coreMethods-parameter.pkl：关键方法识别模型的参数
│  dataset.py：commit message生成需要的语料库
│  generation-parameter.pkl：commit message生成模型的参数
│  model.py：commit message生成模型的结构
│  output.py：项目输出文件
│  演示.exe：演示deemo
│  
├─code2vec：code2vec模型
├─core_methods：关键方法识别模型相关
│      baseline-noGCN.py：不使用GCN的对比实验。
│      baseline-rf.py：使用随机森林的对比实验
│      dataset_process.py：数据集的一些处理的函数
│      fourth.py：两层GCN模型
│      main.py：模型的训练部分
│      model.py：整体模型架构
│      node.py：方法节点的定义
│      second.py：编程过程中用于功能测验的模型
│      third.py：关键度计算
│      
└─message_generation：commit message生成模型相关
    │  transformer-example.py：transformer的示例
    │  try.py
    │  
    ├─.data
    │  └─multi30k
    │          mmt_task1_test2016.tar.gz
    │          test2016.de
    │          test2016.en
    │          test2016.fr
    │          train.de
    │          train.en
    │          training.tar.gz
    │          val.de
    │          val.en
    │          validation.tar.gz
    │          
    └─main：transformer模型相关
        │  model.py：修改后的transformer模型
        │  path-message.data：message生成的相关数据集
