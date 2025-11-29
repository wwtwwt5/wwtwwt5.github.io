# 🌟 wwtwwt5 的个人博客源码

个人博客源代码仓库。
博客基于 [Hexo](https://hexo.io/) 框架，使用 [Butterfly](https://butterfly.js.org/) 主题。

- **在线浏览**: [https://wwtwwt5.github.io](https://wwtwwt5.github.io)
- **源码分支**: `source` (本分支)
- **部署分支**: `main` (由 Hexo 自动生成)

---

## 🛠️ 环境准备

如果你更换了电脑，需要重新搭建环境，请按以下步骤操作：

1.  **安装基础工具**:
    - [Node.js](https://nodejs.org/) (建议 LTS 版本)
    - [Git](https://git-scm.com/)

2.  **安装包管理器 pnpm**:
    ```bash
    npm install -g pnpm
    ```

3.  **安装 Hexo CLI**:
    ```bash
    pnpm add -g hexo-cli
    ```

4.  **克隆源码并安装依赖**:
    ```bash
    # 1. 克隆仓库（注意要克隆 source 分支）
    git clone -b source [https://github.com/wwtwwt5/wwtwwt5.github.io.git](https://github.com/wwtwwt5/wwtwwt5.github.io.git) myblog
    
    # 2. 进入目录
    cd myblog
    
    # 3. 安装依赖
    pnpm install
    
    # 4. (关键) 补全 pnpm 幽灵依赖
    pnpm add moment-timezone
    ```

---

## ✍️ 日常操作指南

### 1. 新建文章
在终端运行：
```bash
hexo new "文章标题"