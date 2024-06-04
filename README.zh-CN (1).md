<div align="center"><a name="readme-top"></a>

[![](https://github.com/freeCB/balala/blob/main/balala%E7%9A%84banner.jpg)](https://github.com/freeCB/balala)

<h1>Blala</h1>

让项目变得更加轻便<br/>
打造专业高效的**管理平台**（[这是链接](https://github.com/freeCB/balala)）插件系统<br/>
这是一条很长的文字

[English](https://github.com/freeCB/balala/blob/main/README.md) · **简体中文** · [更新日志](https://github.com/freeCB/balala/releases) · [文档](https://github.com/freeCB/balala/releases) ·  [Bug反馈](https://github.com/freeCB/balala/issues) · [讨论专区](https://github.com/freeCB/balala/discussions)
<!-- SHIELD GROUP -->

[![][GitHub Release]][GitHub Release link]
[![][web vercel]][web vercel link]
[![][GitHub Discussions]][GitHub Discussions link]
[![][GitHub issues]][GitHub issues link]
[![][GitHub star]][GitHub star link]


**分享 Balala 给你的好友**

111
[![][share-tel-shield]][share-tel-link]
[![][share-x-shield]][share-x-link]
[![][share-whatsapp-shield]][share-whatsapp-link]
[![][share-weibo-shield]][share-weibo-link]
222

</details>
<div align="left">
  
## 👋🏻 开始使用 & 交流

我们是一群充满热情的设计工程师<br/>
希望为企业管理提供现代化的设计组件和工具，并以开源的方式分享。<br/>
我们希望能够为开发者和用户提供一个更加开放、更加透明友好的产品生态。<br/>

不论普通用户与专业开发者，Balala 旨在寻找更便捷的项目管理办法。
Balala目前正在积极开发中，有任何需求或者问题，欢迎提交 [issues][issues-link]

## ✨目录结构
```
+ balala
  + .env                // 启动配置文件
  + compose.yaml        // docker-compose配置文件
  + README.md           // 项目说明
```

## 📘开始：

```
git clone https://github.com/freeCB/balala.git
```

```
cd balala
```
### 🤖启动
```
docker compose up -d
```

### 🌐访问
打开游览器访问：http://localhost:8080/

⚡️超级管理员

用户名：**super**<br/>
初始密码：**Passw@rd**

### 停止
```
docker compose stop
```

### 重启
```
docker compose restart
```


## 启动配置修改
配置文件：.env
```
# 项目名称
COMPOSE_PROJECT_NAME="balala"
# mysql root 账号密码
MYSQL_ROOT_PASSWORD="123456"
# mysql 映射端口号
MYSQL_PORT=3306
# web 映射端口号
WEB_PORT=8080
# 版本
VERSION=v1.3.3
```

### 项目自定义
连接到mysql
1. LOGO
```sql
update config set value = "https://example.com/logo.png" where config_key = "balala.logo";
```
value 的值是图片的url，也可以是base64

2. 网页标题
```sql
update config set value = "new title" where config_key = "balala.title";
```

3. 修改项目地址
```sql
update config set value = "https://example.com" where config_key = "notify.redirect.domain";
```









</details>

Copyright © 2023 [LobeHub][profile-link]. <br />
This project is [MIT](./LICENSE) licensed.

<!-- LINK GROUP -->

[GitHub Release]: https://img.shields.io/github/v/release/freeCB/balala?style=flat-square&labelColor=%23000000&color=%2375FA61
[GitHub Release link]: https://github.com/freeCB/balala/releases
[web vercel]: https://img.shields.io/badge/build-online-brightgreen?style=flat-square&logo=vercel&label=Balala&labelColor=%23000000&color=%2373FBFD
[web vercel link]: https://github.com/freeCB
[GitHub Discussions]: https://img.shields.io/github/discussions/freeCB/balala?style=flat-square&labelColor=%23000000&color=%23EA3FF7
[GitHub Discussions link]: https://github.com/freeCB/balala/discussions
[GitHub issues]: https://img.shields.io/github/issues/freeCB/balala?style=flat-square&labelColor=%23000000&color=%23FFF840
[GitHub issues link]: https://github.com/freeCB/balala/issues
[GitHub star]: https://img.shields.io/github/stars/freeCB?style=flat-square&logo=%20&labelColor=%23000000&color=%23FF8787
[GitHub star link]: https://github.com/freeCB/balala/stargazers
[share-tel-shield]: https://img.shields.io/badge/Share%20%20Tel-black?style=flat-square&logo=telegram
[share-tel-link]: https://t.me/share/url%22?text=https://t.me/share/url%22?text=%E6%8E%A8%E8%8D%90%E4%B8%80%E4%B8%AA%20GitHub%20%E5%BC%80%E6%BA%90%E9%A1%B9%E7%9B%AE%20%F0%9F%A4%AF%20Balala%20-%20%E5%BC%80%E6%BA%90%E7%9A%84%E3%80%81%E5%8F%AF%E6%89%A9%E5%B1%95%E7%9A%84%E9%A1%B9%E7%9B%AE%E7%AE%A1%E7%90%86%E7%B3%BB%E7%BB%9F%E3%80%82%0A%E5%AE%83%E6%94%AF%E6%8C%81%E4%B8%80%E9%94%AE%E5%85%8D%E8%B4%B9%E4%B8%93%E5%B1%9E%E7%9A%84%E9%A1%B9%E7%9B%AE%E7%A9%BA%E9%97%B4%EF%BC%8C%E5%B8%AE%E5%8A%A9%E4%BC%81%E4%B8%9A%E6%9B%B4%E8%BD%BB%E4%BE%BF%E7%9A%84%E7%AE%A1%E7%90%86%E9%A1%B9%E7%9B%AE%E8%BF%9B%E5%BA%A6&url=https://github.com/freeCB/balala
[share-x-shield]: https://img.shields.io/badge/Share%20%20X-black?style=flat-square&logo=X
[share-x-link]: https://x.com/intent/post?hashtags=chatbot%2CchatGPT%2CopenAI&text=%E6%8E%A8%E8%8D%90%E4%B8%80%E4%B8%AA+GitHub+%E5%BC%80%E6%BA%90%E9%A1%B9%E7%9B%AE+%F0%9F%A4%AF+Balala+-+%E5%BC%80%E6%BA%90%E7%9A%84%E3%80%81%E5%8F%AF%E6%89%A9%E5%B1%95%E7%9A%84%E9%A1%B9%E7%9B%AE%E7%AE%A1%E7%90%86%E7%B3%BB%E7%BB%9F%E3%80%82%0A%E5%AE%83%E6%94%AF%E6%8C%81%E4%B8%80%E9%94%AE%E5%85%8D%E8%B4%B9%E4%B8%93%E5%B1%9E%E7%9A%84%E9%A1%B9%E7%9B%AE%E7%A9%BA%E9%97%B4%EF%BC%8C%E5%B8%AE%E5%8A%A9%E4%BC%81%E4%B8%9A%E6%9B%B4%E8%BD%BB%E4%BE%BF%E7%9A%84%E7%AE%A1%E7%90%86%E9%A1%B9%E7%9B%AE%E8%BF%9B%E5%BA%A6&url=https%3A%2F%2Fgithub.com%2FfreeCB%2Fbalala
[share-whatsapp-shield]: https://img.shields.io/badge/Share%20%20whatsapp-black?style=flat-square&logo=whatsapp
[share-whatsapp-link]: https://api.whatsapp.com/send?text=%E6%8E%A8%E8%8D%90%E4%B8%80%E4%B8%AA%20GitHub%20%E5%BC%80%E6%BA%90%E9%A1%B9%E7%9B%AE%20%F0%9F%A4%AF%20Balala%20-%20%E5%BC%80%E6%BA%90%E7%9A%84%E3%80%81%E5%8F%AF%E6%89%A9%E5%B1%95%E7%9A%84%E9%A1%B9%E7%9B%AE%E7%AE%A1%E7%90%86%E7%B3%BB%E7%BB%9F%E3%80%82%0A%E5%AE%83%E6%94%AF%E6%8C%81%E4%B8%80%E9%94%AE%E5%85%8D%E8%B4%B9%E4%B8%93%E5%B1%9E%E7%9A%84%E9%A1%B9%E7%9B%AE%E7%A9%BA%E9%97%B4%EF%BC%8C%E5%B8%AE%E5%8A%A9%E4%BC%81%E4%B8%9A%E6%9B%B4%E8%BD%BB%E4%BE%BF%E7%9A%84%E7%AE%A1%E7%90%86%E9%A1%B9%E7%9B%AE%E8%BF%9B%E5%BA%A6&url=GitHub%20-%20freeCB/balala
[share-weibo-shield]: https://img.shields.io/badge/Share%20%20weibo-black?style=flat-square&logo=sinaweibo
[share-weibo-link]: https://service.weibo.com/share/share.php?sharesource=weibo&title=%E6%8E%A8%E8%8D%90%E4%B8%80%E4%B8%AA%20GitHub%20%E5%BC%80%E6%BA%90%E9%A1%B9%E7%9B%AE%20%F0%9F%A4%AF%20Balala%20-%20%E5%BC%80%E6%BA%90%E7%9A%84%E3%80%81%E5%8F%AF%E6%89%A9%E5%B1%95%E7%9A%84%E9%A1%B9%E7%9B%AE%E7%AE%A1%E7%90%86%E7%B3%BB%E7%BB%9F%E3%80%82%0A%E5%AE%83%E6%94%AF%E6%8C%81%E4%B8%80%E9%94%AE%E5%85%8D%E8%B4%B9%E4%B8%93%E5%B1%9E%E7%9A%84%E9%A1%B9%E7%9B%AE%E7%A9%BA%E9%97%B4%EF%BC%8C%E5%B8%AE%E5%8A%A9%E4%BC%81%E4%B8%9A%E6%9B%B4%E8%BD%BB%E4%BE%BF%E7%9A%84%E7%AE%A1%E7%90%86%E9%A1%B9%E7%9B%AE%E8%BF%9B%E5%BA%A6.%20%23Balala%20%23%E9%A1%B9%E7%9B%AE%E7%AE%A1%E7%90%86%20%23%E4%BC%81%E4%B8%9A%E7%AE%A1%E7%90%86&url=https://github.com/freeCB/balala
[issues-link]: https://github.com/freeCB/balala/issues


[back-to-top]: https://img.shields.io/badge/-BACK_TO_TOP-151515?style=flat-square
[chat-desktop]: https://raw.githubusercontent.com/lobehub/lobe-chat/lighthouse/lighthouse/chat/desktop/pagespeed.svg
[chat-desktop-report]: https://lobehub.github.io/lobe-chat/lighthouse/chat/desktop/chat_preview_lobehub_com_chat.html
[chat-mobile]: https://raw.githubusercontent.com/lobehub/lobe-chat/lighthouse/lighthouse/chat/mobile/pagespeed.svg
[chat-mobile-report]: https://lobehub.github.io/lobe-chat/lighthouse/chat/mobile/chat_preview_lobehub_com_chat.html
[chat-plugin-sdk]: https://github.com/lobehub/chat-plugin-sdk
[chat-plugin-template]: https://github.com/lobehub/chat-plugin-template
[chat-plugins-gateway]: https://github.com/lobehub/chat-plugins-gateway
[codecov-link]: https://codecov.io/gh/lobehub/lobe-chat
[codecov-shield]: https://img.shields.io/codecov/c/github/lobehub/lobe-chat?labelColor=black&style=flat-square&logo=codecov&logoColor=white
[codespaces-link]: https://codespaces.new/lobehub/lobe-chat
[codespaces-shield]: https://github.com/codespaces/badge.svg
[deploy-button-image]: https://vercel.com/button
[deploy-link]: https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Flobehub%2Flobe-chat&env=OPENAI_API_KEY,ACCESS_CODE&envDescription=Find%20your%20OpenAI%20API%20Key%20by%20click%20the%20right%20Learn%20More%20button.%20%7C%20Access%20Code%20can%20protect%20your%20website&envLink=https%3A%2F%2Fplatform.openai.com%2Faccount%2Fapi-keys&project-name=lobe-chat&repository-name=lobe-chat
[deploy-on-sealos-button-image]: https://raw.githubusercontent.com/labring-actions/templates/main/Deploy-on-Sealos.svg
[deploy-on-sealos-link]: https://cloud.sealos.io/?openapp=system-template%3FtemplateName%3Dlobe-chat
[deploy-on-zeabur-button-image]: https://zeabur.com/button.svg
[deploy-on-zeabur-link]: https://zeabur.com/templates/VZGGTI
[discord-link]: https://discord.gg/AYFPHvv2jT
[discord-shield]: https://img.shields.io/discord/1127171173982154893?color=5865F2&label=discord&labelColor=black&logo=discord&logoColor=white&style=flat-square
[discord-shield-badge]: https://img.shields.io/discord/1127171173982154893?color=5865F2&label=discord&labelColor=black&logo=discord&logoColor=white&style=for-the-badge
[docker-pulls-link]: https://hub.docker.com/r/lobehub/lobe-chat
[docker-pulls-shield]: https://img.shields.io/docker/pulls/lobehub/lobe-chat?color=45cc11&labelColor=black&style=flat-square
[docker-release-link]: https://hub.docker.com/r/lobehub/lobe-chat
[docker-release-shield]: https://img.shields.io/docker/v/lobehub/lobe-chat?color=369eff&label=docker&labelColor=black&logo=docker&logoColor=white&style=flat-square
[docker-size-link]: https://hub.docker.com/r/lobehub/lobe-chat
[docker-size-shield]: https://img.shields.io/docker/image-size/lobehub/lobe-chat?color=369eff&labelColor=black&style=flat-square
[docs-dev-guide]: https://github.com/lobehub/lobe-chat/wiki/index
[docs-docker]: https://lobehub.com/docs/self-hosting/platform/docker
[docs-env-var]: https://lobehub.com/docs/self-hosting/environment-variables
[docs-feat-agent]: https://lobehub.com/docs/usage/features/agent-market
[docs-feat-local]: https://lobehub.com/docs/usage/features/local-llm
[docs-feat-mobile]: https://lobehub.com/docs/usage/features/mobile
[docs-feat-plugin]: https://lobehub.com/docs/usage/features/plugin-system
[docs-feat-provider]: https://lobehub.com/docs/usage/features/multi-ai-providers
[docs-feat-pwa]: https://lobehub.com/docs/usage/features/pwa
[docs-feat-t2i]: https://lobehub.com/docs/usage/features/text-to-image
[docs-feat-theme]: https://lobehub.com/docs/usage/features/theme
[docs-feat-tts]: https://lobehub.com/docs/usage/features/tts
[docs-feat-vision]: https://lobehub.com/docs/usage/features/vision
[docs-functionc-call]: https://platform.openai.com/docs/guides/function-calling
[docs-lighthouse]: https://github.com/lobehub/lobe-chat/wiki/Lighthouse.zh-CN
[docs-plugin-dev]: https://lobehub.com/docs/usage/plugins/development
[docs-self-hosting]: https://lobehub.com/docs/self-hosting/start
[docs-upstream-sync]: https://lobehub.com/docs/self-hosting/advanced/upstream-sync
[docs-usage-ollama]: https://lobehub.com/docs/usage/providers/ollama
[docs-usage-plugin]: https://lobehub.com/docs/usage/plugins/basic
[fossa-license-link]: https://app.fossa.com/projects/git%2Bgithub.com%2Flobehub%2Flobe-chat
[fossa-license-shield]: https://app.fossa.com/api/projects/git%2Bgithub.com%2Flobehub%2Flobe-chat.svg?type=large
[github-action-release-link]: https://github.com/lobehub/lobe-chat/actions/workflows/release.yml
[github-action-release-shield]: https://img.shields.io/github/actions/workflow/status/lobehub/lobe-chat/release.yml?label=release&labelColor=black&logo=githubactions&logoColor=white&style=flat-square
[github-action-test-link]: https://github.com/lobehub/lobe-chat/actions/workflows/test.yml
[github-action-test-shield]: https://img.shields.io/github/actions/workflow/status/lobehub/lobe-chat/test.yml?label=test&labelColor=black&logo=githubactions&logoColor=white&style=flat-square
[github-contributors-link]: https://github.com/lobehub/lobe-chat/graphs/contributors
[github-contributors-shield]: https://img.shields.io/github/contributors/lobehub/lobe-chat?color=c4f042&labelColor=black&style=flat-square
[github-document-link]: https://lobehub.com/docs
[github-forks-link]: https://github.com/lobehub/lobe-chat/network/members
[github-forks-shield]: https://img.shields.io/github/forks/lobehub/lobe-chat?color=8ae8ff&labelColor=black&style=flat-square
[github-issues-link]: https://github.com/lobehub/lobe-chat/issues
[github-issues-shield]: https://img.shields.io/github/issues/lobehub/lobe-chat?color=ff80eb&labelColor=black&style=flat-square
[github-license-link]: https://github.com/lobehub/lobe-chat/blob/main/LICENSE
[github-license-shield]: https://img.shields.io/github/license/lobehub/lobe-chat?color=white&labelColor=black&style=flat-square
[github-project-link]: https://github.com/lobehub/lobe-chat/projects
[github-release-link]: https://github.com/lobehub/lobe-chat/releases
[github-release-shield]: https://img.shields.io/github/v/release/lobehub/lobe-chat?color=369eff&labelColor=black&logo=github&style=flat-square
[github-releasedate-link]: https://github.com/lobehub/lobe-chat/releases
[github-releasedate-shield]: https://img.shields.io/github/release-date/lobehub/lobe-chat?labelColor=black&style=flat-square
[github-stars-link]: https://github.com/lobehub/lobe-chat/network/stargazers
[github-stars-shield]: https://img.shields.io/github/stars/lobehub/lobe-chat?color=ffcb47&labelColor=black&style=flat-square
[github-trending-shield]: https://trendshift.io/api/badge/repositories/2256
[github-trending-url]: https://trendshift.io/repositories/2256
[image-banner]: https://github.com/lobehub/lobe-chat/assets/28616219/9f155dff-4737-429f-9cad-a70a1a860c5f
[image-feat-agent]: https://github-production-user-asset-6210df.s3.amazonaws.com/17870709/268670869-f1ffbf66-42b6-42cf-a937-9ce1f8328514.png
[image-feat-local]: https://github.com/lobehub/lobe-chat/assets/28616219/ca9a21bc-ea6c-4c90-bf4a-fa53b4fb2b5c
[image-feat-mobile]: https://gw.alipayobjects.com/zos/kitchen/R441AuFS4W/mobile.webp
[image-feat-plugin]: https://github-production-user-asset-6210df.s3.amazonaws.com/17870709/268670883-33c43a5c-a512-467e-855c-fa299548cce5.png
[image-feat-privoder]: https://github.com/lobehub/lobe-chat/assets/28616219/b164bc54-8ba2-4c1e-b2f2-f4d7f7e7a551
[image-feat-pwa]: https://gw.alipayobjects.com/zos/kitchen/69x6bllkX3/pwa.webp
[image-feat-t2i]: https://github-production-user-asset-6210df.s3.amazonaws.com/17870709/297746445-0ff762b9-aa08-4337-afb7-12f932b6efbb.png
[image-feat-theme]: https://gw.alipayobjects.com/zos/kitchen/pvus1lo%26Z7/darkmode.webp
[image-feat-tts]: https://github-production-user-asset-6210df.s3.amazonaws.com/17870709/284072124-c9853d8d-f1b5-44a8-a305-45ebc0f6d19a.png
[image-feat-vision]: https://github-production-user-asset-6210df.s3.amazonaws.com/17870709/284072129-382bdf30-e3d6-4411-b5a0-249710b8ba08.png
[image-overview]: https://github.com/lobehub/lobe-chat/assets/17870709/56b95d48-f573-41cd-8b38-387bf88bc4bf
[image-star]: https://github.com/lobehub/lobe-chat/assets/17870709/cb06b748-513f-47c2-8740-d876858d7855
[issues-link]: https://img.shields.io/github/issues/lobehub/lobe-chat.svg?style=flat
[lobe-chat-plugins]: https://github.com/lobehub/lobe-chat-plugins
[lobe-commit]: https://github.com/lobehub/lobe-commit/tree/master/packages/lobe-commit
[lobe-i18n]: https://github.com/lobehub/lobe-commit/tree/master/packages/lobe-i18n
[lobe-icons-github]: https://github.com/lobehub/lobe-icons
[lobe-icons-link]: https://www.npmjs.com/package/@lobehub/icons
[lobe-icons-shield]: https://img.shields.io/npm/v/@lobehub/icons?color=369eff&labelColor=black&logo=npm&logoColor=white&style=flat-square
[lobe-lint-github]: https://github.com/lobehub/lobe-lint
[lobe-lint-link]: https://www.npmjs.com/package/@lobehub/lint
[lobe-lint-shield]: https://img.shields.io/npm/v/@lobehub/lint?color=369eff&labelColor=black&logo=npm&logoColor=white&style=flat-square
[lobe-midjourney-webui]: https://github.com/lobehub/lobe-midjourney-webui
[lobe-theme]: https://github.com/lobehub/sd-webui-lobe-theme
[lobe-tts-github]: https://github.com/lobehub/lobe-tts
[lobe-tts-link]: https://www.npmjs.com/package/@lobehub/tts
[lobe-tts-shield]: https://img.shields.io/npm/v/@lobehub/tts?color=369eff&labelColor=black&logo=npm&logoColor=white&style=flat-square
[lobe-ui-github]: https://github.com/lobehub/lobe-ui
[lobe-ui-link]: https://www.npmjs.com/package/@lobehub/ui
[lobe-ui-shield]: https://img.shields.io/npm/v/@lobehub/ui?color=369eff&labelColor=black&logo=npm&logoColor=white&style=flat-square
[pr-welcome-link]: https://github.com/lobehub/lobe-chat/pulls
[pr-welcome-shield]: https://img.shields.io/badge/🤯_pr_welcome-%E2%86%92-ffcb47?labelColor=black&style=for-the-badge
[profile-link]: https://github.com/lobehub
[share-mastodon-link]: https://mastodon.social/share?text=Check%20this%20GitHub%20repository%20out%20%F0%9F%A4%AF%20LobeChat%20-%20An%20open-source,%20extensible%20(Function%20Calling),%20high-performance%20chatbot%20framework.%20It%20supports%20one-click%20free%20deployment%20of%20your%20private%20ChatGPT/LLM%20web%20application.%20https://github.com/lobehub/lobe-chat%20#chatbot%20#chatGPT%20#openAI
[share-mastodon-shield]: https://img.shields.io/badge/-share%20on%20mastodon-black?labelColor=black&logo=mastodon&logoColor=white&style=flat-square
[share-reddit-link]: https://www.reddit.com/submit?title=%E6%8E%A8%E8%8D%90%E4%B8%80%E4%B8%AA%20GitHub%20%E5%BC%80%E6%BA%90%E9%A1%B9%E7%9B%AE%20%F0%9F%A4%AF%20LobeChat%20-%20%E5%BC%80%E6%BA%90%E7%9A%84%E3%80%81%E5%8F%AF%E6%89%A9%E5%B1%95%E7%9A%84%EF%BC%88Function%20Calling%EF%BC%89%E9%AB%98%E6%80%A7%E8%83%BD%E8%81%8A%E5%A4%A9%E6%9C%BA%E5%99%A8%E4%BA%BA%E6%A1%86%E6%9E%B6%E3%80%82%0A%E5%AE%83%E6%94%AF%E6%8C%81%E4%B8%80%E9%94%AE%E5%85%8D%E8%B4%B9%E9%83%A8%E7%BD%B2%E7%A7%81%E4%BA%BA%20ChatGPT%2FLLM%20%E7%BD%91%E9%A1%B5%E5%BA%94%E7%94%A8%E7%A8%8B%E5%BA%8F%20%23chatbot%20%23chatGPT%20%23openAI&url=https%3A%2F%2Fgithub.com%2Flobehub%2Flobe-chat
[share-reddit-shield]: https://img.shields.io/badge/-share%20on%20reddit-black?labelColor=black&logo=reddit&logoColor=white&style=flat-square
[sponsor-link]: https://opencollective.com/lobehub 'Become ❤ LobeHub Sponsor'
[sponsor-shield]: https://img.shields.io/badge/-Sponsor%20LobeHub-f04f88?logo=opencollective&logoColor=white&style=flat-square
[submit-agents-link]: https://github.com/lobehub/lobe-chat-agents
[submit-agents-shield]: https://img.shields.io/badge/🤖/🏪_submit_agent-%E2%86%92-c4f042?labelColor=black&style=for-the-badge
[submit-plugin-link]: https://github.com/lobehub/lobe-chat-plugins
[submit-plugin-shield]: https://img.shields.io/badge/🧩/🏪_submit_plugin-%E2%86%92-95f3d9?labelColor=black&style=for-the-badge
[vercel-link]: https://chat-preview.lobehub.com
[vercel-shield]: https://img.shields.io/website?down_message=offline&label=vercel&labelColor=black&logo=vercel&style=flat-square&up_message=online&url=https%3A%2F%2Fchat-preview.lobehub.com
[vercel-shield-badge]: https://img.shields.io/website?down_message=offline&label=try%20lobechat&labelColor=black&logo=vercel&style=for-the-badge&up_message=online&url=https%3A%2F%2Fchat-preview.lobehub.com
