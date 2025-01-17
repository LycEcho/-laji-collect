# 辣鸡采集 laji-collect

## 根据关键词生成文章-伪原创免费api (该项目的升级版 可购买程序使用)
在线体验 www.lycecho.com

项目地址 https://github.com/LycEcho/Pseudo-original-AI

## 介绍
辣鸡采集，采集世界上所有辣鸡数据 欢迎大家来采集
# 基于fesiong万能采集器底层开发
[万能采集器](https://github.com/fesiong/collector)
# 开发语言
golang
# 官网案例
[辣鸡采集](http://cj.lycecho.com/)
## 为什么会有这个辣鸡文章采集器
* 市面上有几种采集工具，大多都需要针对不同的网站定制不同的采集规则，才能最终采集到想要的结果。本采集器内置了常用的采集规则，只要添加文章列表连接，就能将内容采集回来。
* 本采集器采用多线程并行采集，可在同一时间采集更多的内容。
* 本采集器只专注于采集文章这一件事，不用来定制采集其他内容，只专心做一件事。

## 辣鸡文章采集器能采集哪些内容
本采集器可以采集到的的内容有：文章标题、文章关键词、文章描述、文章详情内容、文章作者、文章发布时间、文章浏览量。

## 什么时候需要使用到辣鸡文章采集器
当我们需要给网站采集文章的时候，本采集器就可以派上用场了，本采集器不需要有人值守，24小时不间断运行，每隔10分钟就会自动遍历一遍采集列表，抓取包含有文章的连接，随时将文字抓取回来，还可以设置自动发布，自动发布到指定文章表中。

## 辣鸡文章采集器可用在哪里运行
本采集器可用运行在 Windows系统、Mac 系统、Linux系统（Centos、Ubuntu等），可用下载编译好的程序直接执行，也可以下载源码自己编译。

## 辣鸡文章采集器可用伪原创吗
## 伪原创免费api
在线体验 cj.lycecho.com(cj.lycecho.com)
项目地址 https://github.com/LycEcho/Pseudo-original-AI(https://github.com/LycEcho/Pseudo-original-AI)

## 如何安装使用
* 下载可执行文件  
  请从Releases 中根据你的操作系统下载最新版的可执行文件，解压后，然后双击运行可执行文件，在打开的浏览器中的可视化界面，填写数据库信息，完成初始化配置，添加采集源，即可开始采集之旅。  
  如果你是在服务器端运行，或者程序没有自动打开浏览器，请按命令界面提示，在浏览器输入访问地址，默认的访问地址是 https://127.0.0.1:8088
* 自助编译  
  先clone代码到本地，本地安装go运行环境，在collector目录下打开cmd/Terminal命令行窗口，执行命。如果你没配置代理的话，还需要新设置go的代理
```shell script
go env -w GOPROXY=https://goproxy.cn,direct
```
  最后执行下面命令  
```shell script
go mod tidy
go mod vendor
go run main.go

```
编译结束后，运行编译出来的文件，然后双击运行可执行文件，在打开的浏览器中的可视化界面，填写数据库信息，完成初始化配置，添加采集源，即可开始采集之旅。

## 开发计划
* 增加可视化添加采集列表连接、查看修改已采集内容操作界面 ✅
* 增加自动发布到远程服务器网站功能 ✅
* 增加关键词自动替换(伪原创的一部分)
* 增加内容自动分段重组功能(待定)

## 官网微信交流群
<img src="http://static.lycecho.com/code/qunCode.jpg" width="300"/>

## 协助完善
欢迎有能力有贡献精神的个人或团体参与到本采集器的开发完善工作中来，共同完善采集功能。请fork一个分支，然后在上面修改，修改完了提交pull request合并请求。

## 版权声明
© echo_yjl_lyc，LycEcho@163.com

Released under the [MIT License](https://gitee.com/echo_yjl_lyc/laji-collect/blob/master/LICENSE)
