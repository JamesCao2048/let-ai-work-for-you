# Prompts 示例库

> 本目录收录书中提到的完整 Prompt 示例，供读者直接使用或参考。

## 📁 目录结构

```
/prompts/
├── README.md                    # 本文件
├── ch10-basic-prompts.md       # Ch10：基础 Prompt 模板
├── ch11-info-processing.md     # Ch11：信息处理 Prompts
└── templates/                  # 通用模板
    ├── summarize.md
    ├── brainstorm.md
    └── code-review.md
```

## 🎯 使用说明

每个 Prompt 文件都包含：
1. **使用场景**：什么时候用这个 Prompt
2. **完整文本**：可直接复制的 Prompt
3. **变量说明**：需要替换的占位符（如 `{文章内容}`）
4. **效果示例**：真实的输入输出案例

## 🔖 快速索引

### 信息处理类
- **文章摘要**：`templates/summarize.md`
- **知识提炼**：`ch11-info-processing.md`

### 创意生成类
- **头脑风暴**：`templates/brainstorm.md`
- **写作辅助**：（即将添加）

### 代码相关
- **代码审查**：`templates/code-review.md`

## 💡 贡献指南

如果您改进了某个 Prompt 或创建了新的有效 Prompt，欢迎：
1. Fork 本仓库
2. 在 `prompts/community/` 目录下添加您的 Prompt
3. 提交 Pull Request

---

**注意**：所有 Prompt 均基于 Claude 3.5 / GPT-4 等模型测试，使用其他模型时可能需要调整。
