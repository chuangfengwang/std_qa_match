# std_qa_match
A collection of classical solution for question match with standard question and answer.

(Chinese) 针对有标准问题的QA场景, 一个经典QA模型的集合

This repo is now **in preparing**



# What problem this repo solve?

## Scene
After-sales or customer service will often conclude questions that users often ask, which is called FAQ(Frequently Asked Questions). Those questions have standard ways to ask and answer using text. They account for 80% of all questions.

However, users will not ask questions in accordance with the standard questions, but will have some semantically similar changes. For example: How to refund tickets -> How should I refund tickets.

For the user's input question, automatically finding the appropriate standard problem becomes the core problem in this scenario.

## Problem form
**Basic form:** Given a short text input, select one or more most similar standard questions from the standard question list.

Other desired features:

+ When new standard questions are added, these new standard questions can be recalled without immediately retraining the model.
+ The inference time cannot be too slow to adapt to the realtime response online.

