---
layout:post
title:信息收集
description:资产收集的常见方法
tag:信息收集
---



##web目录扫描
1.御剑扫描
2.目录爬行
3.python脚本dirsearch扫描
##子域名
1.layer子域名挖掘
2.谷歌语法  site:baidu.com
##真实IP，扫描端口
1.获得真实IP地址，进行端口扫描
namp扫描：nmap  -T4  -sT  -p-  -sV  ip
##扫描C段
1.北极熊扫描C段
##敏感目录扫描
御剑扫描
通常我们所说的敏感文件、敏感目录大概有以下几种：

（1）Git

（2）hg/Mercurial

（3）svn/Subversion

（4）bzr/Bazaar

（5）Cvs

（6）WEB-INF泄露

（7）备份文件泄露、配置文件泄露

敏感文件、敏感目录挖掘一般都是靠工具、脚本来找，当然大佬手工也能找得到。

常用的工具有：

（1）御剑（真的很万能，文末附上全家桶）

（2）爬虫（AWVS、Burpsuite等）

（3）搜索引擎（Google、Github等）

（4）wwwscan

（5）BBscan（一位巨佬写的python脚本：https://github.com/lijiejie/BBScan ）

（6）GSIL（也是一位巨佬写的python脚本：https://github.com/FeeiCN/GSIL ）
##网络架构收集
当我们探测目标站点网站架构时，比如说：操作系统，中间件，脚本语言，数据库，服务器，web容器等等，可以使用以下方法查询。

（1）wappalyzer插件——火狐插件

（2）云悉：http://www.yunsee.cn/info.html

（3）查看数据包响应头

（4）CMS指纹识别：http://whatweb.bugscaner.com/look/ 

CMS指纹识别又有很多方法，比如说御剑指纹识别、Webrobot工具、whatweb工具、还有在线查询的网站等等

##whois敏感信息收集
ns记录，服务器记录，whois信息，注册邮箱信息

很多网站上都可以收集到whois信息，比如说：

国外的who.is：https://who.is/ 

站长之家：http://whois.chinaz.com/

爱站：https://whois.aizhan.com/ 

微步：https://x.threatbook.cn/ 

这些网站都可以收集whois信息，而且还很全面，我主要关注：注册商、注册人、邮件、DNS解析服务器、注册人联系电话。

有需要的还可以查企业的备案信息，主要有三种方式：

天眼查：https://www.tianyancha.com/ 

ICP备案查询网：http://www.beianbeian.com/ 

国家企业信用信息公示系统：http://www.gsxt.gov.cn/index.html 

