---
trigger: always_on
---

始终使用行注释 放弃JavaDoc和多行注释
代码里的注释内容 同时写上行注释 和 log.info(内容) 两行
放弃Controller Service Mapper 三层模式 直接在Controller调用Mapper
API接口 不用遵守Restful风格 路径尽可能简单 使用动词名词组合明确表明接口用途 参数尽可能使用?key=xxx的形式传递
redis 缓存时间必须小于15秒
尽可能应用@Slf4j注解进行控制台日志显示
mysql 配置为 192.168.31.127:3306 数据库test 账户密码都是root
redis 配置为 192.168.31.127:6379 密码是root
