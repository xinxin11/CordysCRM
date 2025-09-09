# 接入 SQLBot 实现智能问数

## 安装 SQLBot

SQLBot 的安装教程请参考：[SQLBot 操作手册](https://dataease.cn/sqlbot/)

---

## 添加 SQLBot 应用

### 创建应用

1. 登录 SQLBot
2. 点击【系统管理】>【嵌入式管理】
3. 点击「创建应用」并选择「高级应用」

> **注意**：跨域配置中应填写 Cordys CRM 的访问地址。为避免跨域异常，Cordys CRM 与 SQLBot 建议保持一致，即要么统一使用域名，要么统一使用 IP 地址。

![创建 SQLBot 应用](../img/user_manual/sqlbot-create-app.png)

### 配置接口

- **接口地址**：填写 Cordys CRM 的部署地址，如 `http://CordysCRM-URL/db/structure` 

- **凭证配置**：用于确保小助手能够访问 Cordys CRM 的 API，直接复制以下参数即可：

| 凭证名称 | 源系统凭证类型 | 目标凭证名称 | 目标凭证位置 |
|---------|---------------|-------------|:-----------:|
| csrfToken | localStorage | csrf-token | header |
| sessionId | localStorage | x-auth-token | header |

![凭证配置](../img/user_manual/sqlbot-credentials.png)
> **注意**：如果在问数过程中出现 401 错误，请检查上图这几个参数是否一致。

## 配置 SQLBot 应用

### 在 Cordys CRM 中配置

1. 登录 Cordys CRM 系统
2. 进入【系统】>【企业设置】>【三方设置】
3. 编辑 SQLBot 并粘贴上述脚本

![Cordys CRM 配置](../img/user_manual/cordys-sqlbot-config.png)

### 验证配置

配置完成后：
1. 开启智能问数功能
2. 在系统右下角查看 SQLBot 应用图标
3. 图标显示即表示配置成功

![SQLBot 配置成功](../img/user_manual/sqlbot-success.png)