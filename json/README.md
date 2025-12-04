# 格式化文档/QA

用于[群机器人](https://github.com/tbjuechen/hias-postgraduate-help-bot)聊天模块知识库构建，要求严格遵循以下格式：

## QA格式

```json
{
  "question": "杭高去年ai复试线是多少？",
  "answer": "智能学院人工智能方向复试线：350分",
  "metadata": {
    "tags": ["杭高", "考研"],
    "author": "可选"
  }
}
```

用于机器人回答few-shot训练

字段解释：

- question：问题文本
- answer：问题回复
- metadata：问答元数据

## 知识文档格式

```json
{
  "title": "文档标题",
  "path": "文档路径",
  "metadata": {
    "tags": ["tag1", "tag2"],
    "author": "可选"
  }
}
```

用于机器人prompt构建

字段解释：

- title：文档标题
- content：文档正文
- metadata：问答元数据
