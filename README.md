# WeRateDog-data-wrangle
Wrangle twitter account 'WeRateDog' data 


How to run the file:

- Download the [WeRateDog](https://github.com/WoHotan/WeRateDog-data-wrangle/tree/master/WeRateDog)
- Run the [WeRateDog/wrangle_act.ipynb](https://github.com/WoHotan/WeRateDog-data-wrangle/blob/master/WeRateDog/wrangle_act.ipynb) via jupyter notebook.

- You must input your tweepy API key replace * in the file.Or,you can ignore the data gather procedure,use [tweet_json.txt](https://github.com/WoHotan/WeRateDog-data-wrangle/blob/master/WeRateDog/tweet_json.txt),the data all we need was contain in [WeRateDog](https://github.com/WoHotan/WeRateDog-data-wrangle/tree/master/WeRateDog)


- The file [wrangle_report.pdf](https://github.com/WoHotan/WeRateDog-data-wrangle/blob/master/WeRateDog/wrangle_report.pdf) record the process of cleaning WeRateDog data.

## 项目概述
### 简介
  现实世界的数据一般不干净。使用 Python 和 Python 库，收集各种来源和形式的数据，评估质量和清洁度，然后进行清洗。在 Jupyter 记事本中记录清洗过程，然后使用 Python (及其库)  进行分析和可视化，展示清洗过程。

  将要清洗 (分析和可视化) 的数据集是推特用户 [@dog_rates](https://twitter.com/dog_rates) 的档案, 也叫做 [WeRateDogs](https://en.wikipedia.org/wiki/WeRateDogs)。推特用户 WeRateDogs 以诙谐幽默的方式对人们的宠物狗评级。这些评级通常以 10 作为分母。但是分子呢？分子一般大于 10。 11/10、12/10、13/10 等，为什么呢？因为 "[Brent 它们是好狗。](http://knowyourmeme.com/memes/theyre-good-dogs-brent)" WeRateDogs 拥有四百多万关注者，曾受到国际媒体的报道。

  - 需要在电脑上用 Jupyter 记事本操作。
  - 需要安装下列文件包 。可以通过 conda 或 pip 安装这些文件包。
    - numpy
    - requests
    - tweepy
    - json
## 项目动机
  清洗 WeRateDogs 推特数据，创建有趣可靠的分析和可视化。
## 项目细节
  在这个项目中的任务如下：

  清洗数据包括：
  -  收集数据
  - 评估数据
  - 清洗数据
  ### 评估项目数据
   收集上述数据的每个内容后，从视觉上和程序上，对质量和清洁度进行数据评估。
   在你的 wrangle_act.ipynb Jupyter Notebook 中查找和记录质量问题 和 2 个清洁度问题。

  ### 清洗项目数据
   评估时清洗记录的每个问题。在 wrangle_act.ipynb 完成清洗。
  ### 存储、分析和可视化项目数据
   在 CSV 文件中存储洁净的数据，命名为 twitter_archive_master.csv。

   在 wrangle_act.ipynb Jupyter Notebook 中对清洗后的数据进行分析和可视化。

  ### 项目汇报
  - wrangle_act.ipynb：用于收集、评估、清理、分析和可视化数据代码
  
  - wrangle_report.pdf：数据整理步骤的文档：收集，评估和清理
  
  - act_report.pdf：观察并分析最终数据的文档
  
  - twitter_archive_enhanced.csv：给定的文件
  
  - image_predictions.tsv：以编程方式下载的文件
  - tweet_json.txt：通过API构建的文件
  - twitter_archive_master.csv：合并和清理数据
