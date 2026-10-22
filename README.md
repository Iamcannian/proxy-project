# 代理项目

手机 Bettbox 与 Windows Clash Party 的独立覆写项目。手机、电脑分别维护，不包含联想商城。

| 平台 | 覆写链接 | 使用说明 |
|---|---|---|
| 手机 Bettbox | [手机覆写](https://raw.githubusercontent.com/Iamcannian/proxy-project/main/mobile/bettbox.js) | [手机说明](mobile/README.md) |
| 电脑 Clash Party | [电脑覆写](https://raw.githubusercontent.com/Iamcannian/proxy-project/main/desktop/clash-party.js) | [电脑说明](desktop/README.md) |

## 目录

- `mobile/`：手机覆写和说明。
- `desktop/`：电脑覆写、设置参考、可选设置导入包。
- `tests/`：隔离、配置、故障转移等测试。
- 根目录旧版脚本：历史兼容文件，日常使用以上手机/电脑入口。
- `THIRD-PARTY-NOTICES.txt`：来源和许可。

## 使用提醒

已经手动调整好 Clash Party 设置的用户，只需导入电脑覆写并绑定订阅，不需要再导入 ZIP。ZIP 会替换应用偏好，使用前先备份。

项目由原 `Iamcannian/-` 仓库中的代理文件迁移而来；联想商城继续保留在原仓库。覆写逻辑不因迁移而更改。
