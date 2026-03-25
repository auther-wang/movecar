# MoveCar - 多用户智能挪车系统 (v2.2)

基于 Cloudflare Workers 的智能挪车通知系统，扫码即可通知车主，保护双方隐私。**v2.2 版本补充企业微信推送。**

##
####原项目地址：https://github.com/lesnolie/movecar
####引申项目地址：https://github.com/nbbk/movecar
####感谢大佬分享，代码增加修改由千问AI调整验证，版本引用nbbk大佬版本号。

##原有使用说明地址：https://github.com/nbbk/movecar/blob/main/README.md
不再复述

##
####2026.3.25日更新日志：
####1.增加推送方式
原有基础上增加企业微信的webhook推送，旨在处理pushpuls需付费认证才可进行通知的问题。
变量名WECHAT_WORK_WEBHOOK，同样支持多用户模式，使用方法一致，即在变量名后增加{_xiaowang}用户名即可。

####2.内置原项目安全设置方案2在 Worker 代码中过滤的防护方案，仅限中国地区ip访问。

####3.增加用户检查，未配置必要变量的访问请求返回404

##
## 📄 许可证
本项目采用 [MIT License](LICENSE) 开源。
