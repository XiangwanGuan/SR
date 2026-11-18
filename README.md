# SR

[Shadowrocket](https://apps.apple.com/us/app/shadowrocket/id932747118) 分流配置，由[向晚](https://t.me/xiangwanguan)维护。

## 分流配置

- [Rules.conf](https://raw.githubusercontent.com/XiangwanGuan/SR/main/Release/Rules.conf)：直接可用的配置文件
- [Rulesets](https://github.com/XiangwanGuan/SR/tree/main/Rulesets)：配置引用的规则集，每日自动构建

规则集数据源自 [v2fly/domain-list-community](https://github.com/v2fly/domain-list-community) 与 [v2fly/geoip](https://github.com/v2fly/geoip)。

## 使用

Shadowrocket → 配置 → 右上角 `+` → 粘贴地址 → 下载。

```
https://raw.githubusercontent.com/XiangwanGuan/SR/main/Release/Rules.conf
```

配置已内置国内直连、国际代理的分流策略，默认使用首页节点进行代理，不含代理分组。

## 更新

- `Rulesets/` 由 `SyncRulesets` 工作流每日从 v2fly 构建并提交，无需手动维护。

## 声明

仅供个人学习测试使用，严禁用于违法及盈利目的，因使用产生的一切后果均由使用者承担。
