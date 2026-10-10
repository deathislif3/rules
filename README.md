# rules

个人自用的规则与插件合集，规则每天自动同步上游。

## 内容

**规则镜像**
- `rule/Loon/`、`rule/Surge/`：同步自 blackmatrix7/ios_rule_script
- `rule-set/`：loon、surge、egern 三份，同步自 QuixoticHeart/rule-set

**插件（modules/）**
- CertGuard：屏蔽苹果证书吊销验证域名，防 P12 侧载应用掉签
- LocalDevVPN：为本机开发工具提供 10.7.0.1 回环

**描述文件（profiles/）**
- CertGuard.mobileconfig：系统级屏蔽苹果证书验证域名，不开代理软件也生效

**公开配置（config/）**
- eyeskeleton-2.lcf：Loon 通用配置，订阅地址与 MITM 证书已替换为占位符，换成自己的就能用

## 自动同步

GitHub Actions 每天北京时间约 10:15 从上游拉取，只更新 rule 与 rule-set，其余目录不受影响。

## 说明

规则版权归上游原作者，本仓库只做个人选择性镜像与整理。插件、配置为本人自用维护。
