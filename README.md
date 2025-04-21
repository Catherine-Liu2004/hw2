# hw2：多模型大语言模型对话系统（Gradio + API）
本项目为用户交互技术课程作业，基于 Python 和 Gradio 框架，实现了一个可视化的用户对话页面，支持调用多个不同厂商的大语言模型（OpenAI 的 GPT-3.5、Anthropic 的 Claude）。
用户可以通过页面输入问题，选择模型，并查看模型回答。同时支持基础对话、多轮对话和历史记录功能。

---

## 功能简介

 基础对话功能 √
  模型选择：支持调用至少两个 LLM 模型（如 GPT 和 Claude）  
 多轮对话功能 √

---

## 环境安装

使用 Python 3.8 及以上版本。

```bash
git clone https://github.com/yourname/llm-gradio-multimodel.git
cd llm-gradio-multimodel

# 安装依赖
pip install -r requirements.txt
