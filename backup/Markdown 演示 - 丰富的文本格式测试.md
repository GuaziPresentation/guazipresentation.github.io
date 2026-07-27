# Markdown 演示 Issue

这是一个全面展示 GitHub Markdown 功能的测试 Issue。

## 📋 目录

- [文本格式](#文本格式)
- [代码示例](#代码示例)
- [列表](#列表)
- [表格](#表格)
- [引用](#引用)
- [链接和图片](#链接和图片)
- [任务列表](#任务列表)

---

## 文本格式

### 基础文本样式

这是 **粗体文本** 和 *斜体文本* 以及 ***粗体+斜体文本***。

这是 ~~删除线文本~~。

这是 `行内代码` 的示例。

### 标题层级

# H1 标题
## H2 标题
### H3 标题
#### H4 标题
##### H5 标题
###### H6 标题

---

## 代码示例

### JavaScript 代码块

```javascript
function helloWorld() {
  console.log('Hello, World! 🌍');
  return true;
}

helloWorld();
```

### Python 代码块

```python
def fibonacci(n):
    """计算斐波那契数列"""
    if n <= 1:
        return n
    return fibonacci(n-1) + fibonacci(n-2)

result = [fibonacci(i) for i in range(10)]
print(result)
```

### HTML/CSS 代码块

```html
<div class="container">
  <h1>欢迎来到我的网站</h1>
  <p style="color: blue;">这是一个演示段落</p>
</div>
```

### Bash 代码块

```bash
#!/bin/bash
echo "开始部署..."
git pull origin main
npm install
npm run build
echo "部署完成！"
```

---

## 列表

### 无序列表

- 第一项
- 第二项
  - 嵌套项 2.1
  - 嵌套项 2.2
    - 深层嵌套项
- 第三项

### 有序列表

1. 第一步：准备环境
2. 第二步：安装依赖
   1. 安装 Node.js
   2. 安装 npm 包
3. 第三步：构建项目
4. 第四步：部署应用

### 复合列表

- 📌 任务管理
  1. 创建项目
  2. 分配任务
- 🔍 代码审查
  - [ ] 检查代码质量
  - [ ] 性能优化
- ✅ 部署上线

---

## 表格

### 功能对比表

| 功能 | 基础版 | 专业版 | 企业版 |
|:---:|:-----:|:-----:|:-----:|
| 用户数 | 10 | 100 | 无限 |
| 存储空间 | 1GB | 100GB | 1TB |
| API 支持 | ❌ | ✅ | ✅ |
| 24/7 支持 | ❌ | ❌ | ✅ |
| 价格 | 免费 | $9/月 | $99/月 |

### 开发工具对比

| 工具 | 语言 | 性能 | 学习曲线 |
|------|------|------|----------|
| React | JavaScript | ⭐⭐⭐⭐⭐ | 中等 |
| Vue | JavaScript | ⭐⭐⭐⭐ | 简单 |
| Angular | TypeScript | ⭐⭐⭐⭐ | 陡峭 |
| Svelte | JavaScript | ⭐⭐⭐⭐⭐ | 简单 |

---

## 引用

> 这是一个简单的引用。

> 这是一个多行引用。
> 
> 可以包含多个段落。
> 
> 甚至可以包含 **格式化文本**。

> **重要提示** ⚠️
>
> 这是一个强调的引用块。
> - 可以包含列表
> - 还可以包含多个项目

---

## 链接和图片

### 超链接

[这是一个链接到 Google](https://www.google.com)

[这是一个带标题的链接](https://www.github.com "GitHub 官网")

[相对链接到项目 README](./README.md)

### 脚注链接

这是关于 Markdown 的更多信息 [^1]。

[^1]: Markdown 是一种轻量级标记语言，由 John Gruber 在 2004 年创建。

---

## 任务列表

### 项目计划

- [x] ✨ 设计系统架构
- [x] 📝 编写技术文档
- [ ] 🔧 开发核心功能
  - [x] 用户认证模块
  - [ ] 数据库集成
  - [ ] API 开发
- [ ] 🧪 编写单元测试
- [ ] 🐛 修复已知问题
- [ ] 📦 构建和部署
- [ ] 🎉 发布 v1.0.0

---

## 高级功能

### 水平线分隔

---

### 清单符号

✅ 完成
❌ 未完成
⏳ 进行中
⚠️ 警告
💡 提示
🔔 通知

### Emoji 示例

🚀 快速启动 | 🎯 目标 | 📊 数据 | 🛠️ 工具 | 🔐 安全 | 📱 移动 | 💻 桌面 | ☁️ 云服务

---

## 代码块突出显示

### 重要代码片段

```javascript
// 这是一个关键算法
const optimizedSearch = (arr, target) => {
  return arr.find(item => item.id === target);
};
```

### 配置示例

```json
{
  "name": "my-awesome-project",
  "version": "1.0.0",
  "scripts": {
    "dev": "webpack-dev-server",
    "build": "webpack",
    "test": "jest"
  }
}
```

---

## 总结

这个 Issue 展示了 GitHub Markdown 的主要功能：

✨ **文本格式** - 粗体、斜体、删除线等  
📝 **代码块** - 支持多种编程语言  
📋 **列表** - 有序、无序和嵌套列表  
📊 **表格** - 结构化数据展示  
💬 **引用** - 强调重要信息  
🔗 **链接** - 内部和外部导航  
✅ **任务列表** - 项目管理和跟踪

**更新日期：** 2026-07-27  
**状态：** 📌 测试中
