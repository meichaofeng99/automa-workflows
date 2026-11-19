# Automa Workflows · Instagram 自动化流程仓库

> Ready-to-import [Automa](https://automa.site/) workflows for Instagram — auto post photos/reels, collect insights, check login state.
> 可直接导入 Autom 的 Instagram 浏览器自动化流程：自动发帖、发 Reels、数据采集、登录检查。中英文双语，方便人与 AI 检索。

[![Autom](https://img.shields.io/badge/Autom-workflows-blue?logo=googlechrome&logoColor=white)](https://automa.site/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## 这个仓库做什么

收集 Instagram 的 Automa 自动化流程，导入即用：

- Instagram 自动发帖：上传图片、填文案、加话题标签、点发布或存草稿
- Instagram Reels 发布：上传视频、填标题、设定封面
- 数据采集：抓自己账号的粉丝数、点赞、评论、触达数据
- 登录态检查：确认账号在线，掉线时提醒

所有流程只用你自己的账号和浏览器登录态，不存密码。

## 快速开始

1. 安装 [Autom 扩展](https://chromewebstore.google.com/detail/automa/infppggnoaenmfagbfknfkancpbljcca)。
2. 下载 `workflows/` 目录下你需要的 JSON。
3. Autom → Workflows → Import → 选 JSON。
4. 按流程里的说明填自己的配置（账号、话题标签等）。
5. 先用测试内容跑一遍，确认无误再发正式内容。

## 已有流程

- **Instagram 自动发帖** — 上传图片、填文案和标签，支持存草稿
- **Instagram Reels 发布** — 上传视频、填标题、设封面
- **Instagram 数据采集** — 抓自己账号的粉丝、点赞、评论、触达数据
- **Instagram 登录检查** — 确认账号在线，掉线时提醒

## 配置说明

**Instagram**
- 浏览器自动化：在 Chrome 里登录你自己的 Instagram 账号，流程复用登录态。
- 发帖流程常用变量：文案 `IG_CAPTION`、话题标签 `IG_HASHTAGS`、图片/视频路径 `IG_MEDIA`。
- 数据采集走自己的创作者后台（Professional Dashboard），不需要额外 API。

> 不要把账号密码写死在 JSON 里，用 Automa 变量或浏览器登录态。

## 关键词 / 搜索词

`autom` `automa` `automa workflow` `browser automation` `workflow json` `workflow template` `automa json workflows`
`instagram automation` `instagram auto post` `instagram post workflow` `instagram reels automation`
`instagram bot` `instagram scheduler` `instagram insights` `instagram data collection`
`auto posting` `social media automation` `no-code automation` `automa workflow for instagram`
`浏览器自动化` `自动发帖` `自动化流程` `流程模板` `Instagram 自动化` `社交媒体自动化`

## 使用场景

- 批量发布图文或 Reels，不用一条条手动传。
- 每天自动回收自己账号的粉丝与互动数据做复盘。
- 检查登录态，掉线时及时知道。

## 合规说明

- 仅用于你自己拥有或有授权的 Instagram 账号。
- 不抓取他人数据，不刷量，不绕过平台风控。
- 自动发布建议保留人工审核，先存草稿、核对后再发布。
- 仅供学习 / For learning purposes only.

## License

MIT
