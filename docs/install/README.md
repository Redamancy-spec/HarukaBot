# 已知问题

::: warning 注意
HarukaBot 目前仍存在以下**问题**，计划在未来版本改进。初次使用请**仔细阅读**，确认可以接受后继续。
:::

## 推送延迟

受限于 B站 对 api 爬取频率限制，目前 HarukaBot 会将需要推送的所有 UP主 排进一个队列，每隔十秒检查一位。因此假设 HarukaBot 订阅了 x 位 UP主，最高延迟就是 10x 秒。计划在 v2 中通过登录账号提高爬取效率。

##  动态推送失效

部分机器人在早晨约**两点到八点**期间，动态推送功能会遭到 B站 封禁**无法使用**，具体原因不明。预计在 v2 中通过登录账号改善。