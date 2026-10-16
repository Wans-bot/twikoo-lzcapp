# Twikoo 留言系统的懒猫 LPK 打包仓库

懒猫微服（LazyCat）应用 `cloud.lazycat.app.twikoo` 的打包工程。构建与商店提交由
`.github/workflows/lazycat.yml` 调用 `ca-x/lazycat-github-action` 完成，定时检查上游镜像
`docker.io/imaegoo/twikoo` 的新版本并自动提审。

- 上游：https://github.com/twikoojs/twikoo（MIT）
- 应用镜像：`docker.io/imaegoo/twikoo`，版本族 2.x.y
- 平台凭据：仓库 Secret `LZC_API_TOKEN`（开发者中心 PAT），不写入文件
- 实机验收与商店截图仍在本机与盒子上完成，见懒猫知识库 `10-打包LPK/skill/实测记录/`
