# rules

个人自用的规则、插件、描述文件与配置合集，规则每天自动同步上游。

## 内容

**规则镜像**
- [`rule/Loon/`](https://github.com/deathislif3/rules/tree/main/rule/Loon)、[`rule/Surge/`](https://github.com/deathislif3/rules/tree/main/rule/Surge)：同步自 [blackmatrix7/ios_rule_script](https://github.com/blackmatrix7/ios_rule_script)
- [`rule-set/`](https://github.com/deathislif3/rules/tree/main/rule-set)：loon、surge、egern 三份，同步自 [QuixoticHeart/rule-set](https://github.com/QuixoticHeart/rule-set)

**插件（modules/）**
- [CertGuard](https://raw.githubusercontent.com/deathislif3/rules/main/modules/CertGuard.plugin)：屏蔽苹果证书吊销验证域名，防 P12 侧载应用掉签
- [LocalDevVPN](https://raw.githubusercontent.com/deathislif3/rules/main/modules/LocalDeviceLoopback.lpx)：为本机开发工具提供 10.7.0.1 回环

**描述文件（profiles/）**
- [CertGuard.mobileconfig](https://cdn.jsdelivr.net/gh/deathislif3/rules@main/profiles/CertGuard.mobileconfig)：系统级屏蔽苹果证书验证域名，不开代理软件也生效

**自用配置（config/）**
- [Loon.lcf](https://raw.githubusercontent.com/deathislif3/rules/main/config/Loon.lcf)：本人的自用配置，敏感信息已剔除，仅作留存

## 自动同步

GitHub Actions 每天北京时间约 10:15 从上游拉取，只更新 rule 与 rule-set，其余目录不受影响。

## 说明

规则版权归上游原作者，本仓库只做个人选择性镜像与整理。插件、配置为本人自用维护。
