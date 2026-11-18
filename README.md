# SR

[Shadowrocket](https://apps.apple.com/us/app/shadowrocket/id932747118) 分流配置，由[向晚](https://t.me/xiangwanguan)维护。

---

### 重要声明
**本项目仅供个人学习测试使用，严禁用于违法及盈利目的，因使用产生的一切后果，均由使用者承担！**  

---

### 分流配置
默认使用 Tun 模式接管所有网络。  
优先使用加密的 **DoH** 解析域名，并配合系统 DNS 实现全局劫持与高可用容错。  
按**国内**与**国际**划分通用规则，实施差异化分流策略。  

配置已内置**国内直连、国际代理**的分流策略，默认使用**首页节点**进行代理，配置轻量，不含代理分组。  

- [Rules.conf](https://raw.githubusercontent.com/XiangwanGuan/SR/main/Release/Rules.conf)：直接可用的配置文件  
- [Rulesets](https://github.com/XiangwanGuan/SR/tree/main/Rulesets)：配置引用的规则集，每日自动构建  

规则集源自 [v2fly/domain-list-community](https://github.com/v2fly/domain-list-community) 与 [v2fly/geoip](https://github.com/v2fly/geoip)，**每日自动同步更新**。  

### 使用
Shadowrocket → 配置 → 右上角 `+` → 粘贴地址 → 下载。  

```
https://raw.githubusercontent.com/XiangwanGuan/SR/main/Release/Rules.conf
```

### 更新
- `Rulesets/` 由 `SyncRulesets` 工作流每日从 v2fly 构建并提交，无需手动维护。  

#### 更新提示
如希望定期更新远程资源，且不希望自定义配置被覆盖，可点击**配置** - **编辑纯文本**，删除或注释 **update-url** 所在的行。  

### 特别鸣谢
[*@v2fly*](https://github.com/v2fly)
