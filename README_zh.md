# JourneyMind

一款基于大语言模型的智能旅行规划助手，可生成个性化行程、景点推荐和旅行计划。

## 目录
- [JourneyMind](#journeymind)
  - [目录](#目录)
  - [功能特性](#功能特性)
  - [安装指南](#安装指南)
    - [环境要求](#环境要求)
    - [安装步骤](#安装步骤)
  - [使用说明](#使用说明)
    - [命令行](#命令行)
  - [开发指南](#开发指南)
    - [项目结构](#项目结构)
    - [运行测试](#运行测试)
  - [贡献指南](#贡献指南)
  - [许可](#许可)

## 功能特性
✨ **核心功能**
- 基于NLP处理的智能节点生成
- 实时协作编辑会话
- 跨平台知识整合
- 可视化分析仪表盘

🔌 **集成支持**
- Jupyter Notebook兼容
- Markdown导入/导出
- 外部系统REST API接口

## 安装指南

### 环境要求
- Python 3.9+
- Neo4j 4.4+ (知识图谱支持)
- Graphviz 2.50+ (可视化渲染)

### 安装步骤
1. 克隆仓库：
```bash
git clone https://github.com/yourusername/JourneyMind.git
```

2. 创建并激活虚拟环境：
```bash
python -m venv venv
venv\Scripts\activate
```

3. 安装依赖：
```bash
pip install -r requirements.txt
```

## 使用说明

### 命令行
```bash
python src/main.py --theme=dark  # 使用暗色主题启动
```

## 开发指南

### 项目结构

```
JourneyMind/
├── src/
│   ├── core/          # Business logic
│   ├── api/           # REST endpoints
│   └── visualization/ # Rendering engine
└── tests/
    ├── unit/          # Isolated tests
    └── integration/   # System tests
```

### 运行测试

```bash
pytest tests/ --cov=src --cov-report=html
```

## 贡献指南

欢迎提交Pull Request来改进JourneyMind，请确保遵循现有代码风格。

## 许可

JourneyMind 根据 [MIT](LICENSE) 许可发布。