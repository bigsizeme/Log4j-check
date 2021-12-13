# Log4j-check
支持RC1绕过
log4J burp被扫插件、CVE-2021-44228、支持RC1绕过、支持json数据类型、支持dnslog.cn和burp内置DNS、可配合JNDIExploit生成payload

在@pmiaowu fastjosn插件上做的修改，原作者用dnslog.cn进行出网检查，但在大型攻防演练（HW）过程中由于前期打点，测试的站点较多dnslog.cn会对IP进行封禁操作
导致插件无法正常检测

基础代码为@pmiaow完成 这里就不提供了


#release中提供下载

结果界面
![Alt text](https://github.com/bigsizeme/Log4j-check/blob/main/1.png)
reapter右键
![Alt text](https://github.com/bigsizeme/Log4j-check/blob/main/2.png)
