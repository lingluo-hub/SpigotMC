# SpigotMC 中文文档

[国际站](https://lingluo-hub.github.io/SpigotMC/) | [国内站](https://lingluo-hub.gitee.io/spigotmc/)

SpigotMC，也被称为 Spigot，是流行在 Bukkit 服务器模组的一个分支。Spigot 是为了提高性能和效率，同时保持与 Bukkit 插件的兼容性。

许多大型服务器都使用 Spigot，因为它们往往比普通服务器使用更多的资源。Spigot 也是无法购买硬件升级或支付服务器托管费的家庭服务器的理想选择。家庭服务器往往滞后很多，通常是由于网络滞后，以及你的电脑必须处理游戏、服务器和你的操作系统。

本站文档致力于翻译 Spigot 官方文档与系统性总结 Spigot 的插件开发教程所编写的指南。

此为本文档的源码仓库，采用 [Material for MkDocs](https://squidfunk.github.io/mkdocs-material) 作为框架

## 快速开始

首先应具有 Python 环境。

可以前往 [https://squidfunk.github.io/mkdocs-material/getting-started/](https://squidfunk.github.io/mkdocs-material/getting-started/) 了解 Material for MkDocs 的使用。

额外使用的插件: `mkdocs-glightbox`, `jieba`, `mkdocs-git-revision-date-localized-plugin`

```bash
pip install jieba 
pip install mkdocs-glightbox
```

### 如何新增一篇文章

1. 在 `docs/` 目录下对应分类下新建名为 `xxxx.md` 的文件
2. 在对应分类目录下的 `index.md` 的 `## 本节目录` 段落下注册文章位置
3. 在项目根目录 `mkdocs.yml` 的 `nav:` 字段下对应节点下注册文章位置

## 加入我们

如果你对本项目感兴趣，并且希望加入我们，欢迎随时提交 [PR](https://github.com/lingluo-hub/SpigotMC/pulls)。请参考如下步骤：

1. 将本项目 fork 到你的个人 GitHub 帐户，然后 clone 到你的本地机器；
2. 进入项目目录，切换到一个新的分支；
3. 对项目做出一些变更，然后使用 git add、commit、push 等命令将你的本地变更提交到你的远程 GitHub 仓库；
4. 将你的变更以 PR 的形式提交过来，项目的维护人员会在第一时间对你的变更进行 review！
5. 你也可以参考帮助文档 https://help.github.com/cn 了解更多细节。
