## Welcome to Yi Li's academic home page！

<table border="0">
  <tr>
    <td width="75%">
      <h1>李一</h1>
      <p><b>性别：男  年龄：21</b></p>
      <p><b>东北大学信息科学与工程学院自动化专业</b></p>
      <p><b>联系方式：18203563369（同微信）    邮箱：yilineu@163.com</b></p>
      <p><b>辽宁省沈阳市和平区文化路三巷11号   邮编：110819</b></p>
    </td>
    <td width="25%">
      <img src="https://github.com/yileezhuiri/yilineu.github.io/blob/gh-pages/img/YiLi.jpg" width="100%">      
    </td>
  </tr>
</table>

## 个人简历
李一，男，本科就读于东北大学信息学院自动化专业，学业绩点：91.281/100，近五学期排名：9/248

本科主要从事1.基于迁移学习的青光眼多模态智能诊断系统，2.基于Alpha Zero算法的五子棋、Hex棋博弈，3.基于MCTSnet的双人完美博弈游戏的研究，获批研究资金3万元。已向Neurocomputing（中科院分区1区，IF=5.719）、BioMedical Engineering OnLine（中科院分区3区，IF=2.905），ICANN(CCF-C类）期刊会议发表和投稿SCI三篇论文，已公开一种基于迁移学习的青光眼多模态智能识别方法的发明专利，已授权一种视频图像采集三维位移平台的实用新型专利。

作为负责人和队长，曾获第十五届中国大学生计算机博弈大赛国家级一等奖，美国大学生数学建模竞赛H奖，全国大学生数学竞赛三等奖等国家级奖项5项，曾获第七届互联网+大学生创新创业大赛辽宁省金奖（50强），主持省级大创一项，辽宁省光电设计竞赛二等奖，全国大学生数学建模竞赛省级三等奖，共青团中央“创青春”铜奖等省级奖项9项。

2019-2020学年，绩点排名3/498，荣获东北大学优秀学生一等奖学金，“优秀学生”荣誉称号，有色金属研究院奖学金。
2020-2021学年，绩点排名9/248，荣获东北大学优秀学生二等奖学金，“学术特长优秀个人”荣誉称号，未来技术学院卓越奖学金。

## 最新消息
1."A faster tree-parallelized Monte-carlo tree search network for two-player adversarial games."已投稿Neurocomputing！

Graphical Abstract
<img src="https://github.com/yileezhuiri/yilineu.github.io/blob/gh-pages/img/per.png" width="100%">  

Abstract
Monte Carlo Tree Search (MCTS) has achieved significant success on many challenging planning problems. Its integration with neural networks applied to games such as Go, Chess and Japanese Shogi, has successfully achieved results that outperform human experts. 
This demonstrates the versatility and effectiveness of MCTS with adaptive rules.Nowadays, the challenge is how to plan without domain-specific knowledge, including perfect simulation of the environment dynamics and careful adaptation of artificial rules to the domain.
In this paper, we propose a model-based full Monte Carlo tree search network algorithm that substitutes all manual rules for the  MCTS main steps with corresponding sub-networks.
These sub-networks manipulate internally the statistics of each node,  enabling adaptive learning of domain knowledge.
In particular, a environment network is introduced to improve performance. 
The parameters of the network are trained end-to-end using Policy-based reinforcement learning.
In the Sokoban and Maze, F-MCTSnet achieves state-of-the-art performance with improved efficiency of parallel search and reduced performance loss compared to MCTSnet.

## 研究方向
1.深度学习。图像处理、实例分割的深度神经网络设计与理论研究，多模态神经网络在青光眼等眼科的应用。

2.机器博弈。结合Model-based Reinforcement Learning，研究MCTS与MCTSnet在完美和非完美规划问题下的求解。

3.嵌入式技术。基于嵌入式平台和硬件电路设计，研究智能设备的相关技术。 

## 研究经历

### 1.基于迁移学习的青光眼多模态智能诊断研究

#### 负责人/队长 主要负责多模态神经网络的构建

#### 合作单位：沈阳市第四人民医院青光眼科室和白内障科室（东北地区眼科排名第一），中国医科大学盛京医院

#### 启动资金：2万元（东北大学金种子计划）

Graphical Abstract
<img src="https://github.com/yileezhuiri/yilineu.github.io/blob/gh-pages/img/chart.jpg" width="100%">  

项目简介：
青光眼是全球排名第一的不可逆性致盲眼病，特征识别是青光眼诊断的关键步骤，要求具有较高的准确性和可解释性。虽然许多计算机辅助方法，特别是深度学习方法在青光眼诊断方面取得了令人惊叹的成就，但基于单模态的深度学习方法在临床使用中的准确性仍然不准确，并且受到数据质量和类型的影响。

我作为团队负责人，与沈阳第四人民医院青光眼科室、中国医科大学盛京医院等合作，构建患者多模态青光眼数据集，其中包括青光眼的五个最重要的亚型。每个病人包括电子医疗记录和至少三种医疗图像。我们提出了一个新的多模态卷积神经网络，其结构由三个主要分支组成，分别处理病人元数据、基于领域的青光眼特征和医疗图像。
应用梯度加权类激活映射方法，使模型能够实现高精确度和良好的可解释性。由于医学图像数据库的数量较少，网络使用了迁移学习方法。

项目获得东北大学大学生创新创业金种子资金2万元支持（全校仅10支队伍），多模态神经网络已初步完成临床实验，取得优良的效果。


#### 数据集示例
<img src="https://github.com/yileezhuiri/yilineu.github.io/blob/gh-pages/img/DATAsur.png" width="100%">  

该数据库包含了青光眼患者的原始电子病志和医学影像数据。电子病历包含了人体年龄、性别、主诉、当前病史、既往病史、视力、眼压、各种专科检查和诊断等文本信息。
医学影像数据由2758张图像组成。它包括五类标签，包括正常、原发性开角型青光眼、原发性闭角型青光眼、闭角型青光眼，继发性开角型青光眼，和继发性闭角型青光眼。在临床实践中遇到的所有青光眼疾病中，超过95%的疾病属于这五种疾病之一。所有数据均由六位 专业医生审核。值得注意的是，这些数据的构建是根据 遵循《赫尔辛基宣言》的原则。


### 2.基于Alpha Zero的五子棋、Hex棋博弈研究

### 3.基于MCTSnet的完美问题求解

### 4.参与国防项目17X项目的申请










You can use the [editor on GitHub](https://github.com/yileezhuiri/yilineu.github.io/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/yileezhuiri/yilineu.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
