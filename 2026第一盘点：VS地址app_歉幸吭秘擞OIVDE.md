VS地址app【Q-——333307——】VS地址app【 辋芷《888yx●vip》 】
VS地址app【Q-——333307——】VS地址app【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整指南

> 想拥有一个完全属于自己的技术博客？不用买服务器，不用懂后端，GitHub Pages 免费托管，Hexo 高效生成静态页面——本文手把手带你上线第一个博客。

 为什么选择 GitHub Pages + Hexo？

很多开发者纠结于博客平台选择。CSDN、掘金有流量但受限于平台规则，自建服务器成本高且维护繁琐。GitHub Pages + Hexo 的组合恰好解决了这些问题：

- 零成本托管：GitHub Pages 免费提供 `username.github.io` 域名
- 极速访问：静态页面加载快，支持 CDN 加速
- 版本管理：文章即代码，天然拥有 Git 版本控制
- 高度定制：主题丰富，支持深度二次开发

 快速搭建三步走

 第一步：创建 GitHub 仓库

登录 GitHub，点击右上角 `+` 号，选择 New repository。仓库名必须命名为 `你的用户名.github.io`（注意大小写）。选择 Public（私有仓库无法启用 Pages 服务），勾选 `Add a README file` 初始化。

 第二步：本地安装 Hexo

确保已安装 Node.js（v18+）和 Git，然后执行：

```bash
npm install -g hexo-cli
hexo init my-blog
cd my-blog
npm install
hexo server
```

浏览器访问 `http://localhost:4000` 即可看到默认博客页面。

 第三步：部署到 GitHub Pages

安装部署插件，修改站点配置文件 `_config.yml` 中的 deploy 参数：

```bash
npm install hexo-deployer-git --save
```

然后推送代码：

```bash
hexo clean && hexo generate
hexo deploy
```

等待 2 分钟，访问 `https://你的用户名.github.io`，你的博客已上线！

 进阶优化建议

自定义域名：在仓库 Settings → Pages 中绑定自己的域名，同时修改 CNAME 文件。

写作效率提升：使用 `hexo new post "文章标题"` 创建新文章，支持 Markdown 语法和代码高亮，专注于内容创作。

SEO 优化：通过安装 `hexo-generator-seo-friendly-sitemap` 插件自动生成 sitemap，提交到百度站长平台，加速收录。

 遇到问题怎么办？

- 部署失败：检查仓库名是否规范，确认 GitHub 邮箱已验证
- 样式错乱：清除浏览器缓存，或执行 `hexo clean` 后重新生成

互动环节：你搭建博客时遇到过哪些坑？欢迎在评论区分享你的踩坑经历，或提出搭建疑问，我会逐一回复解答。

如果这篇文章对你有帮助，点个 Star 支持一下，你的鼓励是我持续输出的动力！

相关推荐：

https://github.com/alvarezcharles0/xilnaw/blob/main/2026%E5%AE%98%E7%BD%91%E7%A7%91%E6%99%AE%EF%BC%9AV8%E5%B9%B3%E5%8F%B0app_%E8%9B%8B%E5%87%A1%E5%B1%85%E7%9F%A3%E6%AF%92INIJJ.md

<img src="https://i.postimg.cc/hGspn7JM/V8-00003.png" />

相关推荐：

https://github.com/alvarezcharles0/xilnaw/commit/317c1e8f15db3aea3927a9bb63dd7c80bf67dccd

<img src="https://i.postimg.cc/fLkFgvHt/V8-00020.png" />
相关推荐：

https://github.com/stoneconnor94/facjpk/blob/main/2026%E7%A7%91%E6%8A%80%E7%88%86%E7%82%B9%EF%BC%9AV8%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C_%E4%B8%94%E9%B9%8A%E5%92%8C%E7%A7%B8%E6%B4%9EJKHEV.md

<img src="https://i.postimg.cc/d0w4g90d/V8-00002.png" />
相关推荐：

https://github.com/stoneconnor94/facjpk/commit/de918dad587504bcbd4591230ac3e90bce56ec89

<img src="https://i.postimg.cc/13Zk5wzH/V8-00013.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
