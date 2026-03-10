# 🎮 Minestrator-Restart
自动重启 Minestrator 服务器，每天定时运行。

## 🔐 Secrets 配置
**Settings → Secrets and variables → Actions → New repository secret** 添加以下变量：

| Secret 名 | 说明 | 示例 |
|---|---|---|
| `MINESTRATOR_ACCOUNT` | 🧾 Minestrator 登录邮箱和密码，用英文逗号分隔 | `myemail@example.com,mypassword` |
| `MINESTRATOR_SERVER_ID` | 🖥️ 服务器 ID | `123456` |
| `MINESTRATOR_AUTH` | 🔑 API 授权 Token，含 Bearer 前缀 | `Bearer xxxxxxxxxxxxxxxx` |
| `GOST_PROXY` | 🌐 Gost 代理地址 | `socks5://user:pass@1.2.3.4:1080` |
| `TG_BOT` | 📨 Telegram 推送，Chat ID 和 Bot Token 用英文逗号分隔 | `987654321,123456:AAFxxx` |

## 🕐 执行时间
每天北京时间 **09:00 / 13:00 / 17:00 / 21:00** 自动触发，也可在 Actions 页面手动执行。
