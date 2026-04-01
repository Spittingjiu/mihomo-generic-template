# Clash Generic Template

用于 `sui-sub` 拉取的 Clash 通用模板（JSON 结构）。

## 文件
- `clash-template.json`：通用基础模板（动态节点由 `sui-sub` 注入）。

## 在 sui-sub 中使用
环境变量：
- `SUI_SUB_CLASH_TEMPLATE_URL`（可选）
- 默认指向本仓库 raw：
  `https://raw.githubusercontent.com/Spittingjiu/clash-generic-template/main/clash-template.json`

说明：
- 若远程模板拉取失败，`sui-sub` 会自动回退到内置模板。
- 你可以直接编辑本仓库模板并提交，`sui-sub` 会按缓存周期自动更新。
