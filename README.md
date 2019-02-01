﻿# 智能聊天机器人

通过RASA官方文档建立的智能聊天机器人

## 技术栈
RASA-NLU：用于自然语言理解的库，具有意图分类和实体提取
        识别结构化数据，根据培训数据了解用户信息，可以根据预定义意图解释意义。

Core（DM）：基于机器学习的对话管理的聊天机器人框架
        基于NLU的输入和历史对话，训练数据，Core决定接下来的对话内容。

## 怎么运行？
python版本：2.7

安装依赖:requirement

运行命令：makefile

## 运行结果
#####human：你好

######小冰冰：你好，欢迎骚扰智能聊天机器人！Hey there! Tell me your name.

#####human：我是张三丰

######小冰冰：嗨，张三丰！我是小冰冰哦~😯

#####human：我是谁？

######小冰冰：你是大名鼎鼎的张三丰！

