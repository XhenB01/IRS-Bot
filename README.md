# IRS-Bot

《我的世界》中国版联机租赁服自动化机器人客户端。

## 简介

IRS-Bot 是一个用 **Go** 编写的 Minecraft（中国版）联机租赁服自动化助手，
附带 **WebView2** 桌面界面与 **Python 插件**系统，用于简化联机服务器的日常管理与内容建设。

## 版本

每次发布提供两个构建，功能相同、**开放范围不同**：

| 构建 | 文件名 | 说明 |
|---|---|---|
| **完整版** | `IRSBot_V0.2.1.73_Full.exe` | 全部功能开放 |
| **精简版** | `IRSBot_V0.2.1.73_Lite.exe` | 关闭：导入导出 · 多房间 · 引流 · 多机器人 · 多账号 · 黑名单 |

> 程序启动时会向界面回报本版本开放了哪些功能，被关闭的入口会自动隐藏。
> 需要完整能力请下载 **完整版**。

## 主要能力

| 能力 | 说明 |
|---|---|
| 账号管理 | 多账号登录与状态维护、邮箱验证码注册登录 |
| 房间管理 | 找房、进房、房间守护与状态巡检 |
| 建筑与地图 | IBI / MCF / BDX 结构导入导出 |
| 消息与公告 | 广播合并、消息中心 |
| 插件系统 | Python 插件扩展，暴露常用接口；内置插件市场 |
| 桌面界面 | WebView2 单页应用，无需独立服务 |
| VIP 与积分 | 账号积分体系、VIP 权益 |
| 3D 世界预览 | 可视化查看建筑结构（VIP 权益，消耗额度） |

## 环境要求

- Windows 10 / 11
- WebView2 Runtime（桌面界面依赖）
- Python 3.12（仅插件功能需要）

## 更新说明

- 客户端启动时会自动检查更新；版本低于 `min` 时将强制更新
- 最新版本号见本仓库 `version.json`

## 许可

<span style="color:#000;font-family:inherit">本</span><span style="color:#000;font-family:inherit">项</span><span style="color:#000;font-family:inherit">目</span><span style="color:#000;font-family:inherit">仅</span><span style="color:#000;font-family:inherit">供</span><span style="color:#000;font-family:inherit">个</span><span style="color:#000;font-family:inherit">人</span><span style="color:#000000;font-family:inherit">使</span><span style="color:#000;font-family:inherit">用</span><span style="color:#000;font-family:inherit">，</span><span style="color:#000;font-family:inherit">请</span><span style="color:#000;font-family: inherit">勿</span><span style="color:#000;font-family:inherit">用</span><span style="color:#000000;font-family: inherit">于</span><span style="color:#000000;font-family: inherit">违</span><span style="color:#000;font-family:inherit">反</span><span style="color:#000;font-family:inherit">游</span><span style="color:#000;font-family:inherit">戏</span><span style="color:#000;font-family:inherit">服</span><span style="color:#000;font-family: inherit">务</span>条款的用途。
