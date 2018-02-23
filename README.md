# tv-script-generation

#### 项目来源： UDAcity 深度学习 P3 项目 ####

- 项目介绍：
  1. 使用tensorflow，构建一个text generation 的LSTM 浅层模型
  2. 利用项目提供的小量样本数据，完成电视剧剧本的生成
- 项目环境：
  - conda 3 --Jupyter Notebook
  - Python3.6.2
  - Tensorflow 1.4
  
### 1. 文件组成 ###

    dlnd_tv_script_generation.ipynb 为代码实施，依赖于Tensorflow
	
  	problem_unittests.py 和helper.py 为辅助assert代码


### 2. 环境要求 ###
   本项目依赖于以下python数据库：

    
    * tensorflow 1.4 深度学习框架
       
   
	ipynb文件运行环境：

    * Anaconda3 Python3.6
    
       
### 项目运行###
    
    GPU运行，训练时间约在秒级到分钟级
    
### 项目优化 ###
  
  模型参数可进一步优化，使得val_loss降至0.1以下.
