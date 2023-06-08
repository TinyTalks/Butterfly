# Butterfly: An Open NLP Research Project for Chinese Danmaku
# 中文弹幕文本NLP研究

<div align="center"><img src="https://github.com/TinyTalks/Butterfly/blob/main/TinyTalks.png" /></div>

## 背景
- Billbill弹幕语言和现象研究仍以定性为主
- Billbill弹幕研究缺少开源数据和任务数据
- 中文缺少弹幕领域的大模型复现资源和社区开源
- Billbill弹幕短文本是一种独特的短文本，属于单独的中文NLP领域
- Billbill弹幕是亚文化发源和演化重点，其研究对中国教育、舆情监控、社会传播等多个领域有着重大意义

## 目标
- 我们希望可以开辟弹幕文本领域，尤其是中文B站弹幕这一特殊文本领域的NLP研究。具体地，我们希望开源一套完整的爬虫系统和一个数亿级别的弹幕语料库，用以支持弹幕短文本语言模型研究；我们还希望开源弹幕领域的NLP任务数据，以探索中文短文本NLP任务的可行性，进而更好地服务中文NLP社区。
- 我们希望训练不同的弹幕预训练语言模型，验证他们在弹幕领域下游任务的有效性，作为巨人的肩膀。
- 我们希望探索在弹幕短文本NLP各个任务上的SOTA解决方案。
- 我们希望基于NLP和统计学理论从语言学视角对B站文本进行系统性的分析探讨，以推动B站文本这一中文SLD的语言评测和使用研究。
- 我们还希望我们的研究可以大大完成对弹幕文本的深层开发，以提升对此类社交媒体平台的舆情监控能力，进而推动中国亚文化、社会传播、青少年教育、群体、心理学、语言学等多个领域的研究发展，提供新的研究视域。

## 项目分支
### DDmkTCCorpus: Diachronic Danmaku Comments Corpus
- 项目描述：弹幕语料库构建与开源
- 项目地址：https://github.com/TinyTalks/DDmkTCCorpus
- 项目进度：开源鬼畜类、电竞类、动漫类、疫情类四个类别弹幕共约100m左右
- TODO: 数据标注

### ElephantDR: The Elephant in the Danmaku Room
- 项目描述：弹幕文本特征分析：语言学视角
- 项目地址：https://github.com/TinyTalks/ElephantDR
- 项目进度：完成弹幕文本的基本特征统计，新词现象的总结归纳
- TODO：进行中文通用文本特征统计并形成对比
