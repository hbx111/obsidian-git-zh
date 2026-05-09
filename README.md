# Obsidian Git 中文汉化版

[原项目](https://github.com/Vinzent03/obsidian-git) 的中文汉化版本。

## 功能特性

- 自动备份 Vault 到 Git 仓库
- 一键拉取/推送/提交
- 源代码管理视图（侧边栏）
- 文件历史与差异对比
- 子模块支持
- 状态栏显示 Git 状态
- 全部界面已翻译为中文

## 安装方式

### 方式一：手动安装（推荐）

1. 下载最新版本的 `main.js`、`manifest.json`、`styles.css`
2. 在你的 Obsidian Vault 中创建目录：`.obsidian/plugins/obsidian-git-zh/`
3. 将下载的三个文件放入该目录
4. 在 Obsidian 设置 → 第三方插件中启用「Git (中文汉化版)」

### 方式二：BRAT 插件安装

1. 安装 [BRAT](https://github.com/TfTHacker/obsidian42-brat) 插件
2. 在 BRAT 设置中添加：`hbx111/obsidian-git-zh`
3. 启用插件

## 配置说明

在插件设置中，你需要先配置：

- **Git 作者名称**：你的名字
- **Git 作者邮箱**：你的邮箱地址
- **基础路径**：你的远程仓库地址（如 `https://github.com/用户名/仓库名`）

## 使用方法

| 操作 | 说明 |
|------|------|
| 拉取 | 从远程仓库拉取最新更改 |
| 推送 | 将本地提交推送到远程仓库 |
| 提交 | 保存当前更改到本地 Git |
| 备份 | 自动执行提交+推送 |
| 源代码管理 | 在侧边栏查看文件变更状态 |

## 版本说明

本插件基于 [obsidian-git v2.38.2](https://github.com/Vinzent03/obsidian-git/releases/tag/2.38.2) 进行汉化。

版本号格式：`原版本号-zh`（如 `2.38.2-zh`）

## 常见问题

### 认证失败怎么办？

如果你使用 GitHub，建议创建 [Personal Access Token](https://github.com/settings/tokens)：
1. 前往 GitHub → Settings → Developer settings → Personal access tokens
2. 创建 token，勾选 `repo` 权限
3. 在插件设置中将 token 填入密码字段

### 推送被拒绝怎么办？

尝试先拉取远程更改，解决冲突后再推送。

## 致谢

- [Vinzent03](https://github.com/Vinzent03) - 原始插件作者
- [denolehov](https://github.com/denolehov) - 原始项目维护者

## 许可证

MIT License - 详见 [LICENSE](LICENSE)
