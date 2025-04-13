# Prompt Comparison Tool

![Prompt Comparison Tool](https://github.com/user-attachments/assets/3d8c0a80-caa0-466a-8a17-471d39962c6a)


## 📝 描述

Prompt Comparison Tool 是一个用于创建、测试和比较不同 AI 提示词（prompts）的工具。该工具让用户能够管理多个提示词模板，配置不同的模型参数，并比较它们的表现，以优化生成式 AI 的输出结果。
示例

### 📊 使用场景

- 优化不同提示词版本
- 测试不同指令格式对输出的影响
- 研究人员比较不同参数设置对结果的影响
- 比较不同模型在相同提示词下的表现


## ✨ 主要特点

- **提示词管理**：创建、编辑和组织不同类别的提示词
- **双模式操作**：
  - **编辑模式**：设计和修改提示词
  - **比较模式**：测试和比较不同提示词的效果
- **版本控制**：维护开发版本和稳定版本
- **系统提示词和用户提示词**：分别编辑系统指令和用户输入
- **参数配置**：调整模型参数（如温度、top_p 等）
- **变量占位符**：使用 `${variable}` 语法在提示词中设置动态内容
- **测试输入**：提供 JSON 格式的测试数据替换占位符
- **实时字符计数**：监控提示词长度

## 🛠️ 技术栈

- HTML/CSS/JavaScript
- 响应式设计，适配不同设备
- 本地存储功能保存用户数据

## 🚀 安装与部署

1. 克隆项目仓库
```bash
git clone https://github.com/zhangtyzzz/prompt_comparison.git
```

2. 通过网页服务器部署，或直接在浏览器中打开 `index.html`

3. 或者访问在线版本：[https://prompt.lovu.zone.id/](https://prompt.lovu.zone.id/)

## 💡 使用指南


### 添加api配置
支持OpenAi格式请求，点击右上角设置按钮，录入
1. 服务商名
2. baseUrl，支持openAi格式请求，示例：https://api.openai.com/v1
3. 密钥
4. 可手动输入，或点击刷新按钮，一键获取可用模型列表


### 创建新提示词

1. 点击 "New" 按钮创建新的提示词类别和名称
2. 在编辑模式下，填写系统提示词和用户提示词
3. 添加所需的模型参数（温度、top_p 等）
4. 点击 "Save as Stable" 保存稳定版本

### 测试提示词

1. 添加测试输入数据（用于替换占位符）
2. 点击 "Test" 按钮查看生成结果
3. 使用不同参数配置进行测试比较

### 比较提示词

1. 在 "Compare Mode" 中，选择不同的提示词版本
2. 输入相同的测试数据
3. 比较不同提示词生成的结果

## 🤝 贡献

欢迎提交 Pull Requests 或开设 Issues 来改进项目功能和修复问题。贡献前请先参考以下指南：

1. Fork 本仓库
2. 创建你的特性分支 (`git checkout -b feature/amazing-feature`)
3. 提交你的更改 (`git commit -m '添加一些很棒的功能'`)
4. 推送到分支 (`git push origin feature/amazing-feature`)
5. 开启一个 Pull Request

## 📄 许可证

该项目使用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情

---

*注意：此项目仅用于管理和比较提示词。实际的 AI 模型处理需要通过单独的 API 或服务实现。*
