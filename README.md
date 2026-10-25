# Games

三个英语角色扮演游戏，部署在 GitHub Pages 上就能直接玩：

| 游戏 | 目录 | 玩法 |
|---|---|---|
| English Quest Board | [english-quest-board](./english-quest-board/) | 经营海外 AI 创业公司 Briefly，30 天每日一章 + Boss 战 |
| 敲钟之路 Road to the Bell | [road-to-the-bell](./road-to-the-bell/) | AI 创业公司创始人，16 集，从车库 MVP 到纳斯达克敲钟 |
| 出海之路 Going Global | [going-global](./going-global/) | 中国小生意主做出海，16 集，含每集实务笔记卡 |

每个游戏都是一个自包含的单文件 HTML（图片已内联），打开首页 `index.html` 选游戏即可。进度保存在浏览器 localStorage（各游戏存档键不同，互不干扰），不跨设备同步。

## 本地打开

直接用浏览器打开 `index.html`，或在仓库根目录起一个静态服务：

```bash
python3 -m http.server
```
