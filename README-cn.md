# std_qa_match
A collection of classical solution for question match with standard question and answer

针对有标准问题的QA场景, 一个经典QA模型的集合

# 这个 repo 解决什么问题
## 1. 场景
售后或者客服常常会总结出用户经常问到问题, 称为FAQ (Frequently Asked Questions), 这些问题有标准的问法和回答. 它们能占到所有被问问题的80%(二八定律).

但是,用户并不会按照标准问题的问法来提问,而是会有一些语义相似的改变. 例如: 机票怎么退 -> 怎么退机票.

对于用户的输入问题, 自动化地找到合适的标准问题, 就成为这个场景下需要解决的核心问题.

## 2. 问题形式 

**基本形式:** 给定一个短句表示的文本输入, 从标准问题列表里选出一个或多个最相近的标准问题.

还期望的其他特性
+ 新增标准问题时,不用立即重新训练模型,就能召回这些新的标准问题
+ 推理时间不可以太慢,以适应线上的即时响应


# 项目结构


# 参考或引用的项目

sentence-transformer
