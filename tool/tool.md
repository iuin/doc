# 常用工具
[保证高可用Java服务化系统高效运行的必备工具箱](https://mp.weixin.qq.com/s/uDqUqovc2ZwrM8Tuu2qhpg)

[史上最全的高可用服务系统线上问题排查工具单（一）](https://mp.weixin.qq.com/s/d_Tl6eiTmpde6eGT5pTaCg)

[史上最全的高可用服务系统线上问题排查工具单（二）](https://mp.weixin.qq.com/s/6EBgu__zwkYbGDjnVsbDlQ)

## BCompare 文本对比

## RegexBuddy 学习正则

## FSCapture 屏幕取色

## Everything 文件快速搜索 

## markdown [Typora](https://www.typora.io/)

## 绘图 亿图图示

[ 亿图图示(Edraw Max) v9.3破解教程](http://www.zdfans.com/html/17131.html)

## chrome插件之GitZip for github

> It can make the sub-directories and files of github repository as zip and download it.

> 不想Clone整个项目，只想下载单个文件或者单个文件夹时，用这个

## chrome插件之uBlock Origin-屏蔽广告

## 反编译
[JD-GUI](https://github.com/java-decompiler/jd-gui/)


-------------------

### JRebel热部署

http://139.199.89.239:1008/961b283f-db32-499c-9ee4-1b48370e5320

260f6d17-ffe2-4c15-8a9c-be9dae4775a4

2019-07-08
http://jrebel.pyjuan.com/36931214-7bb6-42d4-afd7-26eb5628e004

过期,重新生成guid

https://www.guidgen.com/
 
### freemind

https://sourceforge.net/projects/freemind/ 
 
### [时序图](https://blog.csdn.net/fly_zxy/article/details/80911942)
SequenceDiagram    

Plantuml(uml)

### 在线pdf转word
https://smallpdf.com/cn/pdf-to-word

wind10教育版激活码
XFPNF-X94XM-J8TVJ-3V72K-C7JWD

[web开发者工具](https://developers.weixin.qq.com/miniprogram/dev/devtools/download.html)

-----------------
maven清除下载失败的jar
```
@echo off  
rem create by sunhao(sunhao.java@gmail.com)  
rem crazy coder  
    
rem -- 这里写你的仓库路径  
set REPOSITORY_PATH=C:\Users\Administrator\.m2\repository
rem -- 正在搜索...  
for /f "delims=" %%i in ('dir /b /s "%REPOSITORY_PATH%\*lastUpdated*"') do (  
    del /s /q %%i  
)  
rem 搜索完毕  
pause
```  

### maven

mvn install:install-file -Dfile=C:\Users\Adminstrator\Downloads\\ojdbc6-11.2.0.1.0.jar -DgroupId=com.oracle -DartifactId=ojdbc6 -Dversion=11.2.0 -Dpackaging=jar  