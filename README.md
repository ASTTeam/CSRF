# CSRF跨站请求伪造
CSRF漏洞对乙方测试人员来说是容易被忽略的一类漏洞，对红队评估人员来说是容易瞧不起的漏洞，对漏洞赏金人员来说却是比较有收获的一类漏洞。CSRF的危害影响大小一方面取决于系统功能，另一方面取决于测试人员的技术水平。是用户可以做什么操作，CSRF就有什么样的危害！作者：[@ASTTeam团队](https://github.com/ASTTeam/CSRF)

本项目创建于2022年2月6日，最近的一次 更新时间为2022年2月7日。

- [01-CSRF漏洞资源]()
- [02-CSRF漏洞概念]()
- [03-CSRF漏洞原理]()
- [04-CSRF漏洞分类]()
- [05-CSRF漏洞危害]()
- [06-CSRF渗透测试]()
- [07-CSRF代码审计]()
- [08-CSRF漏洞工具]()
- [09-CSRF漏洞修复]()

## 01-CSRF漏洞资源

- https://github.com/topics/csrf
- https://github.com/topics/xsrf

一、书籍资源

- [ ] 《Web前端黑客技术揭秘》

二、其他资源

- https://github.com/symfony/security-csrf
- https://github.com/justinas/nosurf
- https://github.com/1N3/BlackWidow
- https://github.com/gorilla/csrf
- https://github.com/0xInfection/XSRFProbe
- https://github.com/s0md3v/Blazy
- https://github.com/softwaremill/akka-http-session
- https://github.com/s0md3v/Bolt
- https://github.com/pillarjs/csrf
- https://github.com/mike-works/web-security-fundamentals
- https://github.com/gilbitron/EasyCSRF
- https://github.com/twtrubiks/CSRF-tutorial
- https://github.com/tkmru/lazyCSRF
- https://github.com/snsttr/diwa
- https://github.com/praneshn99/web_security_testing
- https://github.com/AdrianCitu/GenericCSRFFilter
- https://github.com/heartsucker/rust-csrf
- https://github.com/Ckrielle/Forgerer
- https://github.com/LIIIs4ma/CSRF-PoC-Generator-26

## 02-CSRF漏洞概念

CSRF(Cross-site request forgery)，中文名称：跨站请求伪造，缩写为：CSRF/XSRF。CSRF与XSS在攻击手段上有点类似，都是在客户端执行恶意代码，CSRF不需要获取用户Cookie。CSRF不仅可以在源站发起攻击，还可以引导用户访问其他危险网站的同时发起攻击。
CSRF攻击是源于WEB的隐式身份验证机制，WEB的身份验证机制虽然可以保证一个请求是来自于某个用户的浏览器，但却无法保证该请求是用户批准发送的。
无意中执行操作。任何操作都是不可信的，但不能所有的操作都添加验证码

## 03-CSRF漏洞原理

## 04-CSRF漏洞分类

## 05-CSRF漏洞危害

## 06-CSRF渗透测试

## 07-CSRF代码审计

## 08-CSRF漏洞工具

- https://github.com/s0md3v/Bolt
- https://github.com/PaulSec/CSRFT
- https://github.com/BlackHole1/autoFindXssAndCsrf

二、Payload生成

- https://www.0e0w.com/csrf
- https://github.com/merttasci/csrf-poc-generator

## 09-CSRF漏洞修复

## 10-CSRF参考资源

- https://github.com/ASTTeam/CSRF