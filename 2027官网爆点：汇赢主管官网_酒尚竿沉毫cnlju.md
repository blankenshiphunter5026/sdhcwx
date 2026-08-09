汇赢主管官网【Q-——333307——】汇赢主管官网【 辋芷《888yx●vip》 】
汇赢主管官网【Q-——333307——】汇赢主管官网【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hugo 完整部署指南（2025最新版）

还在羡慕别人的技术博客又酷又专业？其实，利用 GitHub Pages 和 Hugo 这两大神器，你也能在半小时内拥有一个高速、免费且完全可控的专属博客站点。这篇教程将手把手带你从环境配置到一键部署，全程干货，建议直接收藏，跟着操作不迷路。

 为什么选择 Hugo + GitHub Pages？

- 极速构建：Hugo 是 Go 语言编写的静态站点生成器，号称“世界上最快”，几十个页面秒速生成。
- 零成本托管：GitHub Pages 提供无限流量和 HTTPS 支持，完全免费。
- 版本管理：文章即 Markdown 文件，天然集成 Git 工作流，写稿历史一目了然。

 第一步：本地环境搭建

1.  安装 Hugo：前往 Hugo 官网下载适合你系统的 Extended 版本。macOS 用户可直接使用 `brew install hugo`，Windows 用户可以尝试 `choco install hugo-extended`。
2.  创建新站点：打开终端，运行 `hugo new site my-blog`，然后 `cd my-blog`。
3.  下载主题：去 themes.gohugo.io 挑选一个心仪的主题（比如 PaperMod 或 LoveIt），将其 clone 到 `themes` 文件夹，并在 `hugo.toml` 配置文件中指定主题名称。

 第二步：写文章与本地预览

在 `content/posts` 目录下，运行 `hugo new posts/my-first-post.md` 创建文章。编辑器打开后，你会看到头部有 `title` 和 `date` 等参数，直接修改即可。

> 互动提问：你平时写技术笔记时，更习惯用 Typora 还是 VS Code？欢迎在评论区交流你的写作利器！

写完内容后，运行 `hugo server -D`，浏览器访问 `http://localhost:1313` 就能实时预览效果了。

 第三步：部署到 GitHub

1.  创建仓库：在 GitHub 上新建一个名为 `你的用户名.github.io` 的公开仓库（注意：必须是用户名，且后缀是 io）。
2.  一键推送：在项目根目录打开终端，依次执行：

```bash
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:你的用户名/你的用户名.github.io.git
git push -u origin main
```

3.  开启 Pages 服务：进入仓库的 Settings -> Pages，在 Branch 下拉框选择 `main` 分支，文件夹选择 `/ (root)`，点击 Save。等待一分钟，你的博客就上线了！

 进阶技巧：绑定自定义域名与自动部署

若想使用自己的域名，只需在仓库根目录添加一个 CNAME 文件，里面写上你的域名，并在域名服务商处配置解析即可。同时，利用 GitHub Actions 可以实现在每次 `git push` 后自动构建并重新部署，真正实现“写文章零操作”的飞一般体验。

---

行动号召：如果在操作中遇到任何报错（比如端口冲突或主题配置问题），别慌！欢迎在评论区留下你的问题截图或报错信息，我会逐一解答。如果你已经成功部署，不妨在评论区晒出你的博客地址，让大家一起围观学习！觉得教程有用，记得点赞、在看、转发三连，让更多朋友告别 CSDN，拥有自己的独立小窝。

相关推荐：

https://github.com/milleranthony6850/pwnvke/blob/main/2027%E7%AC%AC%E4%B8%80%E7%83%AD%E7%82%B9%EF%BC%9A%E6%B1%87%E8%B5%A2%E7%BD%91%E5%9D%80%E5%AE%A2%E6%9C%8D_%E9%A2%91%E8%A4%82%E8%BE%89%E5%BD%B0%E8%94%A1kjpbo.md

<img src="https://i.postimg.cc/pVfDZQ4j/mei-nu-bei-jing-zhao-shang-tu-zhi-zuo-(78).png" />

相关推荐：

https://github.com/milleranthony6850/pwnvke/commit/e0703f5412c19e07bfb0884b9dc3e4471788e061

<img src="https://i.postimg.cc/rsk5Tz0n/mei-nu-bei-jing-zhao-shang-tu-zhi-zuo-(76).png" />
相关推荐：

https://github.com/adamsjonathan8709/jjgpxy/blob/main/2027%E6%9D%83%E5%A8%81%E5%B9%B2%E8%B4%A7%EF%BC%9A%E6%B1%87%E8%B5%A2%E7%BD%91%E5%9D%80%E7%99%BB%E5%BD%95_%E5%A3%AB%E6%89%8D%E6%96%AF%E8%95%89%E4%B8%9Boatms.md

<img src="https://i.postimg.cc/J0Lj8tD5/mei-nu-bei-jing-zhao-shang-tu-zhi-zuo-(75).png" />
相关推荐：

https://github.com/adamsjonathan8709/jjgpxy/commit/2bb5f2f75006f99a2fac2e6519d83da88758c138

<img src="https://i.postimg.cc/yd9020dS/mei-nu-bei-jing-zhao-shang-tu-zhi-zuo-(73).png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
