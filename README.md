# 📁 AI File Tools

AI文件处理工具，支持文件转换、批量处理、文件分析。

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?logo=python" />
  <img src="https://img.shields.io/badge/OpenAI-API-green?logo=openai" />
  <img src="https://img.shields.io/badge/License-MIT-yellow" />
</p>

## ✨ 特性

- 🔄 文件格式转换
- 📦 批量处理器
- 📊 文件结构分析
- 📂 文件整理器
- 👁️ 文件监控器
- 🔍 文件去重工具

## 🚀 快速开始

```bash
pip install openai

python tools.py
```

## 📖 使用

```python
from ai_file_tools import create_tools

tools = create_tools()

# 文件转换
converter = tools.convert_file("CSV", "JSON", "销售数据")

# 批量处理
processor = tools.generate_batch_processor("图片压缩", ["jpg", "png"])

# 文件分析
analysis = tools.analyze_file_structure("E:/projects")

# 文件整理
organizer = tools.generate_file_organizer(rules)

# 文件监控
monitor = tools.generate_file_monitor("E:/downloads", ["自动分类"])

# 去重工具
dedup = tools.generate_dedup_tool("E:/photos", "hash")
```

## 📁 项目结构

```
ai-file-tools/
├── tools.py       # 文件工具核心
└── README.md
```

## 📄 许可证

MIT License
