# Shadowrocket 远程规则（无节点、无密码）

给 Shadowrocket 用的「配置」文件：只含分流规则与常规选项，**不含服务器地址和密码**。
`PROXY` 是 Shadowrocket 内置策略，指向首页当前选中的节点。

## 用法

1. Shadowrocket → 底部「配置」→ 右上角 `+` → **添加远程文件**
2. URL 填：
   - 国内推荐（jsDelivr 镜像）：
     `https://testingcf.jsdelivr.net/gh/chen964224/shadowrocket-rules@master/futu.conf`
   - 备用（GitHub raw）：
     `https://raw.githubusercontent.com/chen964224/shadowrocket-rules/master/futu.conf`
3. 打开「自动更新」，间隔 24 小时
4. 下载后点该配置 →「使用配置」
5. 首页选中节点，全局路由选「配置」

## 更新

改完规则后重新生成并推送到本仓库，手机下次自动更新即生效；
需要立刻生效时，在配置列表里下拉刷新，或点开该配置重新下载。
