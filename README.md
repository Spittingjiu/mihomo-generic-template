# mihomo-generic-template

用于 `sui-sub` 拉取的远程模板仓库。

## 文件
- `clash-template.yaml`：Clash / Mihomo 模板
- `singbox-template.json`：sing-box 模板

## 在 sui-sub 中使用
可选环境变量：
- `SUI_SUB_CLASH_TEMPLATE_URL`
- `SUI_SUB_SINGBOX_TEMPLATE_URL`

默认地址：
- Clash：`https://raw.githubusercontent.com/Spittingjiu/mihomo-generic-template/main/clash-template.yaml`
- singBox：`https://raw.githubusercontent.com/Spittingjiu/mihomo-generic-template/main/singbox-template.json`

说明：
- `sui-sub` 以远程模板为主。
- 远程拉取失败时，自动回退本地模板/内置模板。
- 直接编辑本仓库模板并提交后，`sui-sub` 会按缓存周期自动生效。
