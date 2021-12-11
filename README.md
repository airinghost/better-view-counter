
# 独立访客(IP)计数服务

A visitor badge counting unique IP


## 用法 Usage

在你个人网站的页脚或某个特定页面，按下述方式之一插入图片即可：

Insert image into your personal website: 

**HTML**

```html
<img src="https://visitors.zhangjet.com/badge/YOUR_USERNAME/SET_UNIQUE_ID?unique=true" loading="lazy" alt="N/A">
```

**Markdown**

```markdown
![N/A](https://visitors.zhangjet.com/badge/YOUR_USERNAME/SET_UNIQUE_ID?unique=true)
```

**说明**

`YOUR_USERNAME` 设置成你的用户名（用以区分用户）

`SET_UNIQUE_ID` 设置成一串独特的字符（用以区分你名下的不同链接）

`N/A` 部分为图片无法正常加载时显示的文字，可自定义


服务器位于广州，国内连通性良好。

**The service is deployed on a server in southern China, and it may be slow to reponse in other areas in the world.**


## 项目来源

[better-view-counter @hi019](https://github.com/hi019/better-view-counter)

这是我用过的安装起来最简单的计数器👍

你可以根据 README 的步骤在自己的服务器上部署该服务


## 其他

本服务无法在 GitHub 的个人 Profile 页面或仓库页面正常计数，

如有这项需求，可使用下列两项服务： [HITS @dwyl](https://github.com/dwyl/hits) 或 [git-badges @Julian Pufler](https://github.com/puf17640/git-badges)

[![N/A](http://hits.dwyl.com/airinghost/better-view-counter.svg?style=flat)](https://github.com/dwyl/hits) [![N/A](https://badges.pufler.dev/visits/airinghost/better-view-counter)](https://badges.pufler.dev)

还有，若仅需统计页面浏览量(Page Views)，那么你可以自己用 Vercel 很方便地部署这个项目： [visitor-badge-node @WangNingkai](https://github.com/WangNingkai/visitor-badge-node)

[![N/A](https://visitor-badge-node-airinghost-airinghost.vercel.app/p/better-view-counter)](https://github.com/WangNingkai/visitor-badge-node) 
